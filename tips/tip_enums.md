### Enums
Enums allow us to define a set of named constants. Using enums
can make it easier to document intent, or create a set of distinct cases. 
TypeScript provides both numeric and string-based enums.

#### Numeric enums
```
enum Direction {
    Up, //=> initilize at 1, 2,3 and so on
    Down,
    Left,
    Right,
}
```
***Note*** *initlized enum should be come first.*

#### String enums
```
enum Direction {
    Up = "UP",
    Down = "DOWN",
    Left = "LEFT",
    Right = "RIGHT",
}
```
***Note*** *string enums don’t have auto-incrementing behavior.*

### Heterogeneous enums
Technically enums can be mixed with string and numeric members:
```
enum BooleanLikeHeterogeneousEnum {
    No = 0,
    Yes = "YES",
}
```
