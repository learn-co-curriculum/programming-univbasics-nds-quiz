# Nested Data Structures Quiz

???

# Quiz

?: Which NDS does the following code represent?

```ruby
[ { :name => "James" }, { :name => "LeBron" }, { :name => "O'Shea" }]
```

( ) `Array` of `Array`s 
(X) `Array` of `Hash`es 
( ) `Hash` of `Array`s 
( ) `Hash` of `Hash`es

?: Which NDS does the following code represent?

```ruby
[ ['X', 'O', 'X'], ['O', 'X', 'O'], ['O', 'X', 'O'] ]
```

(X) `Array` of `Array`s ( ) `Array` of `Hash`es ( ) `Hash` of `Array`s ( ) `Hash` of `Hash`es

?: Which NDS does the following code represent?

```ruby
{ 
  :label => "Water",
  :component => {
    :label => "Hydrogen",
    :component => nil
  },
  :component => {
    :label => "Oxygen",
    :component => nil
  }
}
```

( ) `Array` of `Array`s ( ) `Array` of `Hash`es ( ) `Hash` of `Array`s (X) `Hash` of `Hash`es

?: Which NDS does the following code represent?

```ruby
power_lifter_jones = {
  :bench_press => [ [60, 3], [65, 10], [60, 3]],
  :lat_pulldown => [ [90, 3], [95, 10], [90, 3]]
}
```

( ) `Array` of `Array`s ( ) `Array` of `Hash`es (X) `Hash` of `Array`s ( ) `Hash` of `Hash`es

?: Which structure does the following real-world description suggest?

"We want to build a clone of minesweeper where some cells are 'safe' but others trigger a game failure."

(X) `Array` of `Array`s ( ) `Array` of `Hash`es ( ) `Hash` of `Array`s ( ) `Hash` of `Hash`es

?: Which structure does the following real-world description suggest?

"We're going to run a set of tests on a patient. For statistical purposes, we
will take three samples on 4 breathing tests."

( ) `Array` of `Array`s ( ) `Array` of `Hash`es (X) `Hash` of `Array`s ( ) `Hash` of `Hash`es

?: Which structure does the following real-world description suggest?

"We're going to make a network request for a collection of products that match
a `String` we provide in the request. The collection will have objects holding
two facts, a product-identifier and a price."

( ) `Array` of `Array`s (X) `Array` of `Hash`es ( ) `Hash` of `Array`s ( ) `Hash` of `Hash`es

?: Which structure does the following real-world description suggest?

"We want to model a decision structure. At every step, from the first decision,
there will be a positive choice and a negative choice. All choices are
uniform."

( ) `Array` of `Array`s ( ) `Array` of `Hash`es ( ) `Hash` of `Array`s (X) `Hash` of `Hash`es

?: Given the following NDS:

``ruby
trios = [
  ["Geddy", "Alex", "Neal"],
  ["Raekwon", "ODB", "The RZA"],
  ["The Micke", "Joltin' Joe", "Say Hey Kid"]
]
``

What does the following code produce?

```ruby
trios[0][5] = "John"
trios[0] #=>  ???
```

( ) `["Geddy", "Alex", "Neal", "John"]`, ( ) `["Geddy", "Alex", "Neal", nil, nil, "John"]`, (X) `["Geddy", "Alex", "Neal", nil, "John"]`, ( ) `["Geddy", "Alex", "Neal", "John", nil]`,

?: True / False: It is not possible, in Ruby, to nest an Array of Arrays inside of
another nested data structure

( ) True
(X) False

???
