# Basic Ruby Skills Eval

### 1. What will `val1` and `val2` equal after the code below is executed? Explain your answer.

```ruby
val1 = true and false
val2 = true && false
```

***

### 2. Which of the expressions listed below will result in `"false"`

```ruby
true    ? "true" : "false"
false   ? "true" : "false"
nil     ? "true" : "false"
1       ? "true" : "false"
0       ? "true" : "false"
"false" ? "true" : "false"
""      ? "true" : "false"
[]      ? "true" : "false"
```

### 3. Consider the following method:
```ruby
def times_two(arg1);
  puts arg1 * 2;
end
```

What will be the result of each of the following lines of code:
```ruby
times_two 5
times_two(5)
times_two (5)
times_two "abc"
```

### 4. Consider the following method: 
```ruby
def a_number
  20
end

mynum = 10
```

What will the following lines of code return?
```
a_number/mynum

a_number / mynum

a_number/ mynum

a_number /mynum
```

### 5. What's the difference between the following two variables?
```ruby
$my_var
``` 

and 

```ruby 
@my_var
```


### 6. Consider the following code:
```ruby
VAL = 'Global'
 
module Foo
  VAL = 'Foo Local'
 
  class Bar
    def value1
      VAL
    end
  end
end
 
class Foo::Bar
  def value2
    VAL
  end
end
```

What will be the value of each of the following?
```ruby
Foo::Bar.new.value1
Foo::Bar.new.value2
```

### 7. Is the line of code below valid Ruby code? If so, what does it do? 
```ruby
-> (a) {p a}["Hello world"]
```

### 8. What's the difference between `super` and `super()`?

### 9. What's the difference between the following operators? `==`, `===`, `eq?`, `equal?`

### 10. Given:
```ruby
x = "hello"
```

Explain the difference between the two lines of code below:
```ruby
x += " world"

x.concat " world"
```

### 11. You often see the expression `array.map(&:method_name)` as a shorthand form of `array.map {|element| element.method_name}`. How does the first expression work?
