# How to decide what to eat

How to decide what to eat is also a big problem before I cook.So I can only describe it in mathematics.

## Calculation method

### Calculate the number of meat dishes and vegetarian dishes

* Number of dishes = number of people + 1.
* One more meat dish than a vegetarian dish, or just as much.

This way, you can get the number of meat dishes and vegetarian dishes, and then select it in the recipe in the previous step.

#### Formal language description

When someone counts `N`,
Suppose the `number of vegetarian dishes` is `a` and the `number of meat dishes` is `b`.
`N`, `a`, and `b` are all integers.

At this time, there is the following inequality group:

* a + b = N + 1
* a ≤ b ≤ a+1

I'll understand

* a = floor(N/2)
* b = ceil(N/2)

### Dishes selection

* If the number exceeds 8, consider adding fish meat dishes to the meat dishes.
* If you have children, consider adding sweet dishes.
* Consider adding special dishes and specialty dishes.
* Be careful not to use all the meat of the same animal when making meat dishes.The order of consideration is: `Pork`, `Chicken`, `Beef`, `mutton`, `Duck`, and `Fish`.
* Don’t choose strange animals to make meat dishes.