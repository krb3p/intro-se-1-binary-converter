# Converting to Binary

## Intro

We use 10 digits (starting with 0 and ending with 9) to write our numbers. But as you may or may not know, the nature of electricity means that at their core, computers really only have access to two: 1 and 0.

An electrical current is binary - it's either flowing or it isn't. So for each space in a binary number must be represented by a 1 or 0, nothing else.

Here's how to represent a few given objects in each number system:

|Objects |Decimal|Binary |
|--------|-------|-------|
|        |      0|      0|
|       *|      1|      1|
|      **|      2|     10|
|     ***|      3|     11|
|    ****|      4|    100|
|   *****|      5|    101|
|  ******|      6|    110|
| *******|      7|    111|
|********|      8|   1000|

Even though the binary number to represent three objects looks like an "eleven", it's not. It's the number 3 represented in a binary number system.

One way to think of it is like an odometer: when you hit the last digit in a position, it will flip back to zero, and trigger a turn for the next digit over.

###### Decimal odometer

![Traditional Odometer](Odometer.gif)

###### Binary odometer

![Binary Odometer](https://media.giphy.com/media/12eEEIWB4XEt9K/giphy.gif)

### Before you start!

It's critical that you can do this by hand before you try to write a program that can do it. Can you predict what the following decimal numbers will be in binary? Click on any one to check your answer.

<details>
  <summary>10</summary>
  
  `1010`
</details><br>

<details>
  <summary>20</summary>
  
  `10100`
</details><br>

Can you convert these binary numbers back to decimals?

<details>
  <summary>10110</summary>
  
  `22`
</details><br>

<details>
  <summary>1011</summary>
  
  `11`
</details><br>


## The Goal

Write two methods, one called binary_of that takes in a decimal number and returns its binary equivalent, the other called decimal_of that takes in a binary number and returns its decimal equivalent.

Here's some test code you might want to use.

###### Encode tests
```ruby
puts binary_of(7) # => should print out the number "111"

puts binary_of(2) # => should print out the number "10"
```

###### Decode tests
```ruby
puts decimal_of(111) # => should print out the number "7"
```
