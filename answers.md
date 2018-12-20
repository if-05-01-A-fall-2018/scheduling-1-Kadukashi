# Assignment 7: Basics of Scheduling

## Scheduling -- Process Selection
When we think of a process that creates,verifys and confirms a order.
It is important that the order is verifyed before the order can be confirmed.

---
## Minimizing Turn Around Time
|          Process         | G | B | A |  D |  C |  F |  H |  E |
|:------------------------:|:-:|:-:|:-:|:--:|:--:|:--:|:--:|:--:|
| Expected run time (msec) | 2 | 5 | 8 | 12 | 16 | 21 | 34 | 55 |

Sum: 2  + 7 + 15  + 27  + 43  +  64 +  98  + 153 = __409 msec__

---
## Round-Robin Scheduler --- Discussion
The process which occours twice in the list, would get twice more time then all the other processes.
