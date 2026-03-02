Fixed-priority Scheduler
========================

An example [fixed-priority scheduler](https://en.wikipedia.org/wiki/Fixed-priority_pre-emptive_scheduling).

There are two tasks to complete in this lab.

## Learning Outcomes

After completing this lab, learners will be able to:

1. Explain rate-monotonic scheduling and fixed-priority preemptive scheduling, including their assumptions and limitations
2. Assign static priorities to periodic threads according to rate-monotonic principles
3. Implement a fixed-priority scheduler that selects the highest-priority ready thread and correctly handles preemption

## Task

1. Set the appropriate priorities for the threads in the `threads` array. Consider the theorems we discussed in class regarding [rate-monotonic scheduling](https://en.wikipedia.org/wiki/Rate-monotonic_scheduling)
2. Implement a correct fixed-priority scheduler in the `schedule` function as described in the description in the source code comments.

Testing
-------

Your code can be compiled and tested via simulation by running:

```
make test
```
