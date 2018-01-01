# dwitter-cheat-sheet
Tips and tricks I picked up from awesome dweets at https://dwitter.net.


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


## for loops
from [basic dwitter guide](https://www.reddit.com/r/dwitter/comments/7mgcd1/basic_dwitter_guide/) by [Xen](https://www.dwitter.net/u/Xen/top)

- `for( i=9 ; i-- ; second_thing ) thing ;`
