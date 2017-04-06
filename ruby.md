# Command line application template for Ruby

Implement CLI application by editing [main.rb](app/main.rb).  
You may add new files to keep your code clean, if it is allowed in your challenge.

## How to get input parameters

In [main.rb](app/main.rb), there is a function called `main`, which gives command line arguments as `argv`.

``` rb
def main(argv)
  # code to run
end
```

`argv` passed here is came from [index.rb](index.rb) which passes `ARGV` to `main` function.

## How to output result
Use the standard `puts` method to output results to `stdout`.

``` ruby
puts "Hello World"
```

## Install External Libraries
If you want to use external libraries, do the following:

- Write the library name in [Gemfile](Gemfile)
