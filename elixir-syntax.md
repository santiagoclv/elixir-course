# Elixir Syntax

* Modules (**defmodule**) group functions (**def**) and everything is always betweem **do** and **end**
* Module names must be an Elixir atom, capitalized
* function names are either names or one of the Elixir operators. Names must start with a lowercase letter or underscore, and may contain letters, digits, and underscores. The name may end with an exclamation point or a question mark.

```elixir
defmodule Dictionary do
  # body of module . . .

  def hello() do
    # body of function . . .
  end

end
```

