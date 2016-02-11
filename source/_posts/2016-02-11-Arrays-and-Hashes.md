---
layout: post
title: "Arrays and Hashes"
date: 2016-02-01 09:52:10 AM
comments: true
description: "Differences"
---

Refrences
<a href= "http://stackoverflow.com/questions/6863771/how-to-add-to-an-existing-hash-in-ruby "> Refrence One: Hash </a>
<a href= "https://teamtreehouse.com/community/when-do-you-use-an-array-versus-a-hash-in-ruby "> Refrence Two: Array vs Hash </a>
<a href= "http://www.linuxtopia.org/online_books/programming_books/ruby_tutorial/Ruby.new_Arrays_and_Hashes.html "> Refrence Three: How to use a hash rather than a array

Arrays are an ordered list where elements are assigned to a numerical index. Arrays have zero or more elements in a specific order, where elements may be duplicated. An array simply contains values and they can be accessed through implied keys that are numbers from 0 up. So if you have this array: array = ["John", "Robert", :name, 557] It means that these are names are John and Robert. [ ] creates an empty array.

Hashes is an order doesn’t matter so keys must be unique for example: {“Theo” => “Glazed}.  Hashes have zero or more elements organized by key, where keys may not be duplicated but the values stored in those positions can be. Hashes in Ruby are very flexible and can have keys of nearly any type you can throw at it. This makes it different from the dictionary structures you find in other languages. You can also index on nearly anything, including classes, numbers, or other Hashes. A index is an alphabetical list of names, subjects, etc., with references to the places where they occur, typically found at the end of a book, but in this case it is inside a hash. In hashes, you define how the keys to those values look like, you can customize them and use anything you want: hash = { "friend1" => "John", "friend2" => "Robert", :attribute => :name, :number_of_hours => 557, 1996 => "Best year!" } { } creates a empty hash. 

Ruby's arrays and hashes are indexed stacks. Both have lots of collections of objects, accessible by using a key. With arrays, the key is an integer, while, hashes’ keys are any objects inside a hash. Both arrays and hashes grow as needed to hold new elements. It's more efficient to access array elements, but hashes provide more flexibility. Any particular array or hash can hold objects of differing types; you can have an array containing an integer, a string.
