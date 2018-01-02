# dwitter-cheat-sheet
Tips and tricks I picked up from awesome dweets at [Dwitter](https://dwitter.net).

You can find my [dweets here](https://www.dwitter.net/u/rippedspine) :)


## even/odd using `&` ([bitwise AND](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_Operators#Bitwise_AND))
instead of i%2==0 to get even/odd, do x&1

- `1&1 -> 1`
- `2&1 -> 0`
- `3.2&1 -> 1`


## to the power of

- `2**3` == `Math.pow(2,3)`


## less bits to write 1000, 20000, 300000 etc...

- `1e3 -> 1000`
- `2e4 -> 20000`
- `3e5 -> 300000`
- ...


## shortest way to clear canvas using `|` ([bitwise OR](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_Operators#Bitwise_OR))
not sure how this works...

- `c.width|=0`
- edit: `c.width^=0` seem to have the same effect, interesting.


## for loops
from [basic dwitter guide](https://www.reddit.com/r/dwitter/comments/7mgcd1/basic_dwitter_guide/) by [Xen](https://www.dwitter.net/u/Xen/top)

- `for( i=9 ; i-- ; second_thing ) thing ;`


## initiate values
If you need to initiate a value at the beginning of the loop, like for a counter.

- `t||(count=0);count++`
