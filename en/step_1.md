You can add a group of instructions to a function. This will give that particular piece of music a name.

+ Create a function by defining it and giving it a name. The name of this function is `:two_notes`.

```ruby
define :two_notes do
    # Place your music here
end
```

+ Add your code between `do` and `end`

```ruby
define :two_notes do
    play 60
    sleep 1
    play 65
    sleep 1
end
```

If you run your code like this, nothing will happen. This is because you need to **call** the function for the code to be executed.

+ Call the function by typing its name anywhere after the `end` of the function (leave out the `:`)

```ruby
two_notes
```

+ You can call the function as many times as you like, but you only need to define its contents once. This saves time, makes your code shorter and means that if you need to update the code, you only need to update it in one place.
