# Key For Minimum Value

## Objectives

1. Practice iterating over a hash.

## Instructions 

1. Fork and clone this lab
2. Build a method `key_for_min_value` that accepts an argument of a hash. This method should iterate over the hash and return the *key* (not the value!) that points to the smallest value of the set. If the method is called and passed an argument of an empty hash, it should return `nil`. 

Here are some examples: 

```ruby
ikea = {:chair => 25, :table => 85, :mattress => 450}
key_for_min_value(ikea)
# => :chair

veggies = {"apple" => -45, "banana" => -44.5, "carrot" => -44.9}
key_for_min_value(veggies)
# => "apple"
```

**A Few Restrictions:**
We want you to build this on your own. Some of the following methods are helpful but ***off limits*** for this exercise. We're going to learn more about them in the next lesson: 

* `#keys`
* `#values`
* `#min`
* `#sort`
* `#min_by`

**A Helpful Hint:** 

* Think about how to determine which value is the lowest. Do you need to compare each value to something as you iterate? 
* Think about how to collect or store the correct key. Remember that you need your method to return *just this key*. 
