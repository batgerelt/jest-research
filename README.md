# jest-research

## coverage

```
npm test -- --coverage
```

<img width="551" alt="Screenshot 2023-11-02 at 14 38 50" src="https://github.com/batgerelt/jest-research/assets/32481226/0f9c7813-1c80-417a-9e20-cc53c3e9a692">

#

* **Statement** coverage нь анализ хийсэн statements ийг шичилдэг.
* **Branch coverage** analyzes the percentage of the program’s edge cases that have been executed.
* **Function coverage** analyzes the percent of the program’s functions that have been called during testing.
* **Line** coverage analyzes the percentage of the program’s executable lines in the source file that have been executed.


.toBeDefined() is used to verify that a variable is not undefined. This is often the first thing checked.
.toEqual() is used to perform deep equality checks between objects.

.toBe() is similar to .toEqual() but is used to compare primitive values.

.toBeTruthy() is used to verify whether a value is truthy or not.

.not is used before another matcher to verify that the opposite result is true

.toContain() is used when we want to verify that an item is in an array. In this case, since the .not matcher is used, we are verifying that "Ice Cream" is NOT in the array

