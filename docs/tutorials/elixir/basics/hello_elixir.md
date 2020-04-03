# Hello Elixir

Learn how to make your first `Hello World` program in Elixir.

## Using IEx

Open your terminal and start IEx -

```bash
$ iex
iex(1)>
```

Write the following into your IEx -

```bash
iex(1)> IO.puts("Hello World")
```

Output -

```bash
Hello World
:ok
```

## Using Script File

Create a file `hello_world.exs` and enter the following - 

```elixir
IO.puts("Hello World")
```

Elixir files can be created using two extension `exs` or `ex`, `exs` is normally used for creating scripts and `ex` for creating compiled files.

Here we will be working with script file, later we will explore working with `ex` extensions for compiled files.

To run the script, open the terminal and navigate to the folder that contains the `hello_world.exs` file and run the following -

```bash
$ elixir hello_world.exs
```

Output

```bash
$ elixir hello_world.exs
"Hello World"
```

That's it! You just created your file Elixir program.

## IO

Wondering what is this `IO` ? It is simply a built-in module provided by Elixir, it is automatically imported and is made available to use, we will cover more about modules later. In addition to `IO` there are a lot of modules made available, be sure to check out the official documentation for a complete list.

`puts` is simply a function defined in `IO` module, we invoke the function by passing a argument `IO.puts("Hello World")` , this in turn prints "Hello World" to our terminal.

Elixir is pretty flexible about its syntax, you can omit the brackets and it will work just the same -

```bash
iex(1)> IO.puts "Hello World"
Hello World
:ok
```

The choice of using brackets or not is upto you, personally I like using brackets, it makes the code easier to read, but it's just my personal preference.

## Exercises

1) Create and run a script file that will print the following. Make sure to make a new file with `exs` extension and run it from your terminal.

`"Elixir Rocks!!!"`

2) And one more script that will print -

`"Hi, my name is Octallium and I am learning Elixir"`

3) What is the result of -

```bash
iex(1)> IO.puts 7 + 6
```

4) And

```bash
iex(1)> IO.puts "7 + 6"
```

5) For some fun try running this -

```bash
iex(1)> IO.puts "Hello " <> "World"
```

{++Don't skip the exercises if you really want to learn Elixir! However simple they may seem, its important to try them out yourself!++}

## Please Consider a Donation ❤️

If you would like to see articles coming up much faster then please consider a small donation. All the work is provided free of cost and completely open source, but it needs your support and love to keep the activity sustainable.

Any support is genuinely appreciated, you can help by sending a small donation by clicking the below link:

[<img src="../../../../images/paypal-logo.png" alt="Paypal" title="Paypal" width="200"/>](https://www.paypal.me/octallium)