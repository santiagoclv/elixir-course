# Notes from Elixir for Programmers 2 from The Coding Gnome

[elixir-for-programmers-2](https://codestool.coding-gnome.com/courses/elixir-for-programmers-2)

* command: **elixir**
* compailer: **elixirc**
* Proyect Manager: **mix**
* repl (Read–eval–print loop): **iex**

## IEx

The repl for elixir, runs over erlang
* Evaluates elixir 
    > IO.put("Hello World")
* it **remembers** the **evaluations** that were run on that instance and can be accessed using arrows.
* it **remembers** the output **value of the evaluations** too, and they can be reuse by accessed using 
    > v(number-of-evaluation)

## Elixir nomenclature

### Difference between Elixir and other programming languages
 * When we talk about **applications** or **projects** in Elixir, we're really talking about **components** inside of **a bigger whole**. Writing code in Elixir as a series of separate (if interdependent) components leads to more flexible, and easier to develop, designs.

## Mix

In general we will create a folder for the whole system and add projects/applications to it by using mix

create a new Elixir project

> mix new <project_name>