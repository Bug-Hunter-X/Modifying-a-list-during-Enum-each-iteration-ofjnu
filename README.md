# Elixir List Modification During Enum.each Iteration

This example demonstrates a common mistake in Elixir when attempting to modify a list while iterating over it using `Enum.each`. The provided code intends to remove the element `3` from the list, but due to immutability and the way `Enum.each` works, the list remains unchanged.

The solution demonstrates a correct approach using `Enum.filter` or `Enum.reject` to create a new list without modifying the original list during iteration.