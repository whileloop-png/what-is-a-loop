# what-is-a-loop
learn what loops are within Roblox LuaU

# LETS GET THE BASICS

ipairs: ipairs r used to iterate through tables with sequential numeric indices such as arrays. It stops at the first nil value and ensures the iteration happens in order.

Example: ipairs({1, 2, 3}) will iterate over 1, 2, and 3.

pairs: used to iterate through all key-value pairs in a table regardless of the key type or order. It doesnt guarantee any specific iteration order.

Example: pairs({a = 1, b = 2, c = 3}) will iterate over a = 1, b = 2, and c = 3 in an arbitrary order.

----------------------------------------------------------------

# types of loops and their use cases
1. for loops (numerical)
how it works: iterates a specific number of times, defined by a start value, an end value, and optionally, a step.

# use case:

counting numbers.
repeating actions a fixed number of times.
iterating through indices of arrays or ranges.

# for loops (generic)

# use case:

processing lists of objects, such as game items or player data.
iterating over a dictionary for settings or configurations.
example in security: checking for misconfigurations in a list of settings or permissions. for example, iterating through player roles to ensure all have appropriate access levels.

# while loops

how it works: continues looping as long as a condition evaluates to true.

# use case:

waiting for a condition to be met, such as a players action.
polling for updates or changes in game state.

# repeat...until loops

how it works: pretty similar to while but always executes the loop body at least once before checking the condition.

# use case:

shits useful when you need to guarantee at least one iteration before validating a condition.
