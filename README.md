# Intro-to-Ruby-homework

Closing Questions
Please answer the following questions in the spaces provided.

How do you write an if statement in Ruby?
An example of an if statement would be the following :
# your here answer:
number = 10
if (number === 10)
puts ("Its a 10!")
end
It's a 10!
nil => nil
  
Please write code that would take the string "007", reverse it, and return the integer 700.
## your answer here: 
n = "007".reverse
puts n.to_i

Please write code that takes the array [23,56,3,7], sorts it, and then reverses that sorted array 'in place' (i.e. modifying the original array, rather than returning a new array).
## your answer here:
array = [23, 56, 3, 7]
array.sort.reverse

What does an exclamation point at the end of a method name usually signify?
  Your answer here: Methods with an ! attached to the end of the them usually mean that they will modify the value with the memory they are being called on (bang method)

What does a question mark and the end of a method name usually signify?
  ## your answer here:
  Any method that ends with a ? means that it beull return a boolean value.

How do you define a method in Ruby? Give a simple example.
  ## your answer here:
  A method is a set of expressions that returns a value.

  example:
  class NilClass
 def hello
   return "Hey Booo"
 end
end

nil.hello

the example is abocve is giving nil the method called .hello

How do you create a class in Ruby? Give a simple example.
 ## your answer here:
 if you want to create a class for nil it would be nil.class which is would give you NilClass

Please give an example of how iteration can be performed in Ruby.
  ## your answer here: 
  Interations are method that naturally loop over a give set of data and allow you tp operate on each element in the collection.
  Example:names = ['Supriya', 'Smita', 'Avi']
x = 1

names.each do |name|
  puts "#{x}. #{name}"
  x += 1
end

This is out the names in a list starting from the number 1.

If I modify a class in Ruby by adding a method, will instances of that class which have already been created be able to call the new method I added? Please explain why.
  ##Your answer here:
  Yes(I think) I will come back to this one, answer it, and then push the code again.