#Condition Operators Quiz
## Objectives

1. Test your understanding of the ternary operator
2. Understand when to use the ternary operator
3. Understand that use of statement modifiers (trailing if and trailing unless statements)
4. Understand the use of trailing unless statement 

???

# Quiz

?: Which of the following `if` statements is a good candidate for using a ternary operator instead?

(X)

```ruby
if condition_a
  something
else
  something_else
end
```
( )

```ruby
if condition_a
  something
elsif condition_b
  something_else
else
  something_even_more_different
end
```

?: Let's convert the correct answer above using a ternary operator. Which of the following is the correct way to do that?

( )

```ruby
condition_a ? something : condition_b
```

( )

```ruby
condition_a ? something : (conditional_b ?something_else : something_even_more_different)
```

(X)

```ruby
condition_a ? something : something_else
```

( )

```ruby
condition_a ? something_else : something
```

?: When is it a good idea to use an `if` conditional over a ternary?

( ) When the `if` statement is complex with multiple `elseif` conditions
( ) When it would require a nested ternary statement
( ) When the ternary statement takes up more than one line
(X) All of the above


?: What will this code print out:

```ruby
name = "Steven"
puts "Hi, #{name}" if name == "Steven"
``` 

( ) "Hi, #{name}"
(X) "Hi, Steven"
( ) Nothing

?: What will this code print out:

```ruby
name = "Steven"
puts "Hi, #{name}" unless name == "Steven"
``` 

( ) "Hi, #{name}"
( ) "Hi, Steven"
(X) Nothing


?: If you are unsure whether to use the ternary operator, or the if statement, which should you use?

(X) `if` statement
( ) ternary statement

???