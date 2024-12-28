# Elixir Enum.each and List Modification Bug

This repository demonstrates a common mistake when working with lists and iteration in Elixir.  The provided code attempts to remove an element from a list while iterating through it using `Enum.each`. Because Elixir lists are immutable, modifying the list within the `Enum.each` function does not change the original list.

The solution shows how to correctly modify a list while iterating, usually by creating a new list.