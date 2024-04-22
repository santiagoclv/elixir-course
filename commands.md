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

* create a new Elixir project

> mix new <project_name>

* see doc about run command with mix

> mix help run 

* Load an application into IEx in the context of your project, to use it interactivily and with auto commpleate.
    > iex -S mix
* In case that the application is modified, it can be reloaded int IEx like this:
    > r <application_name>