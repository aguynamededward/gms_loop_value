# gms_loop_value

`s_loop_value(_val,_min,_max)`
A simple function for looping values between two limits.

## Installation
Download and import the yymps file as a package.

## Examples:

Loop through items in an array
```gml
var _last_item_index = 7;

s_loop_value(_last_item_index + 2,0,7);

// returns
1
```

Calculate degrees

```gml
s_loop_value(-45,0,359)

// returns
315
```


Hours on a clock
```gml
s_loop_value(13,1,12)

//returns
1
```


