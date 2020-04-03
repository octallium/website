# Interactive Elixir Shell

Learn how to interact with the interactive shell and get started.

## IEx

To enter the interactive shell open your terminal and type the following

For mac, freeBSD or linux -

```bash
$ iex
iex(1)>
```

For windows - 

```bash
c:\> iex.bat
iex(1)>
```

Interactive shell provides a convenience method for using elixir. Let's try to explore it.

```bash
iex(1)> IO.puts("Hello, World")
```

You get back a response -

```bash
Hello, World
:ok
```

Don't worry about `:ok`, its called as an `atom` and we will come back to it later. To exit the IEx press `ctrl-c` twice.

## Helper Functions

IEx provides all sorts of helper function, we will see them as required in future tutorials, for now again open the IEx and type the following -

```bash
iex(1)>i 43
```

What output do you see?

```bash
Term
  43
Data type
  Integer
Reference modules
  Integer
Implemented protocols
  IEx.Info, Inspect, List.Chars, String.Chars
```

Using the flag `i` the interactive shell provided you with a lot of data, lets try putting something else this time.

```bash
iex(2)> i "Hello, World"
```

Output

```bash
Term
  "Hello, World"
Data type
  BitString
Byte size
  12
Description
  This is a string: a UTF-8 encoded binary. It's printed surrounded by
  "double quotes" because all UTF-8 encoded code points in it are printable.
Raw representation
  <<72, 101, 108, 108, 111, 44, 32, 87, 111, 114, 108, 100>>
Reference modules
  String, :binary
Implemented protocols
  Collectable, IEx.Info, Inspect, List.Chars, String.Chars
```

Notice the `Data type` is showing `BitString` this time, earlier for `43` the data type was `Integer`, IEx is trying to help by providing all the information that it available.

## Exercises

Now, its time for some fun exercises, type the following and see what output do you get

```bash
iex(1)> i 'a'
iex(2)> i 2.56
iex(3)> i :hello
iex(4)> i true
```

Just read all the outputs, you are not required to understand everything just yet, but try to read and make sense of the output.

{++Don't skip the exercises if you really want to learn Elixir! However simple they may seem, its important to try them out yourself!++}

## Please Consider a Donation ❤️

If you would like to see articles coming up much faster then please consider a small donation. All the work is provided free of cost and completely open source, but it needs your support and love to keep the activity sustainable.

Any support is genuinely appreciated, you can help by sending a small donation by clicking the below link:

[<img src="../../../../images/paypal-logo.png" alt="Paypal" title="Paypal" width="200"/>](https://www.paypal.me/octallium)