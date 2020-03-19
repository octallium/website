title: Introduction to Elixir
description: Understand what Elixir is all about

# Introduction

![Introduction to Elixir](../../../images/pages/octallium-elixir-introduction.jpg)

Considering **Elixir** ? Or maybe just curious ? Chances are you already have some experience with programming or if you are a complete beginner, I couldn't be any more happy!

Before getting along with actual coding, let's get a couple of things straight, Elixir is not a silver bullet to all your problems, ever heard of **Hammer Syndrome**? 

It implies that, _"If you only have a hammer, every problem looks like a nail!"_, but in the practical world things are very different, problems are various and in different domains. Then where would you use Elixir?

## Scenario

Let's consider this, the world basically works by **communication**, means communication is required in every aspects of life, products communicate their utility, services communicate their usability, consumer communicate their requirements, etc, and in this world of communication **data** is constantly being passed from one point to another.

**Elixir** is extremely well suited for these applications, it really shines when data has to be transferred in a highly distributed and fault tolerant manner. Often, data has to be transformed to suit the end users, Elixir with all its eco-system is a perfectly capable system for it. Perhaps, that's why products like WhatsApp, Discord & Telecom sector rely so highly on it.

If you are more interested in generating data, analysing data or manipulating data or create really low level applications, then you should consider having a look at other programming languages.

## Why Erlang/Elixir And Phoenix?

There is this typical marketing pitch that Erlang/Elixir really offers excellent distributed concurrency, planet scalability, immutable values and fault tolerant systems, etc etc, but lets keep them aside for a while.

The only pitch is, let yourself to be exposed to this really excellent eco-system and then decide your own choice of demon 🐲

Chances are that you must have heard about **WhatsApp**, **Discord**, **Bleacher Report**, **Pinterest**, etc, they runs on Erlang/Elixir and about more than 50% of all telecom providers on the planet.

If its so great why haven't I heard about it earlier? Carry on...

## About Erlang/Elixir

We need to give it, other languages did a fantastic job of presenting themself in a much better way, also the amount of marketing, conferences, sponsorships, etc have really shaped them to be much popular and widely used.

Erlang/Elixir looks as if it has a cryptic syntax and functional programming makes them look difficult on the surface, but its really not the case, they are really great to work with and specially **Elixir** is designed to make developers feel **happy**.

Feeling curious, what the hell is all this? Carry on...

## What is Erlang, Elixir And Phoenix

[Erlang/OTP](https://www.erlang.org/) is a concurrent functional programming language that forms the basic foundation, it was developed by Ericsson in 1986 and made open source in 1998. Erlang runs on its virtual machine called as the **BEAM**. OTP simply stands for **Open Telecom Platform**.

[Elixir](https://elixir-lang.org/) builds on top of Erlang and provides a nice and easy way of interacting with the underlying system. It provides abstraction over Erlang, so that its easier for developers to code and finally it compiles to Erlang byte code.

[Phoenix Framework](https://www.phoenixframework.org/) is a great set of tooling to create mature and blazing fast web applications, its based on Elixir and offers excellent framework to create highly scalable and concurrent distributed applications.

We would be more focused on **Elixir & Phoenix**, but keep it mind that finally everything is compiled to Erlang byte code and runs on the BEAM.

Elixir & Phoenix also has very good set of online documentation and the communities are also generally warm and helpful.

Let the force be with you!

## Code Sample

All code will be in the form of following block

```elixir
# Elixir code
defmodule Hello do

  def say do
    :World
  end
  
end
```

## Understanding Elixir

Elixir is a functional programming language, the word **functional** is important as it does not have the concept of **Objects or Classes**, if you come from a **Object Orientated Language** then you need to unlearn a lot of concepts in order to understand the functional paradigm.

Programming need not only be object oriented, functional programming is a beautiful way of thinking, also it takes away a lot of pain as you don't need to keep a track of the state of objects.

## How it works?

Elixir acts like a thin layer on top of **Erlang**, under the hood it maps everything to Erlang and also compiles to Erlang byte code. This byte code runs on the Erlang virtual machine called as **BEAM**.

Elixir brings a lot of simplicity and easy to understand syntax, the idea is to make the developer feel happy while coding yet maintain the high performance.

Erlang offers more than 30 years of rock solid performance and also the availability of huge eco-system of modules, these modules can be easily used in Elixir.

## Getting Help

Elixir has a set of very nice online [documentation](https://elixir-lang.org/docs.html) and [guides](https://elixir-lang.org/learning.html).

[Elixir Forum](https://elixirforum.com/) is an excellent place to post queries and interact with the community.
