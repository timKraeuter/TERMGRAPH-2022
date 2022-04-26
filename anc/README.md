
# BPMN specific properties

## Safeness

The atomic property **Unsafe** is implemented by the following graph condition in groove:

![Atomic property Unsafe implemented in groove.](./Unsafe.png)

The property matches whenever two tokens of one process snapshot have the same position (but have different identities).

## Option to complete

The atomic property **AllTerminated** is implemented by the following graph condition in groove:

![Atomic property AllTerminated implemented in groove.](./AllTerminated.png)

The property matches whenever there is no process snapshot in the state running. This all process snapshots are terminated, i.e., have no tokens.

# Implementation
TODO: Link tool repo and tool website

| BPMN feature  | Test class           | Test case |
| ------------- | -------------        | -----           |
| Task          | BPMNToGrooveTaskTest | Sequential Tasks|
| col 2 is      | centered             |       |
| zebra stripes | are neat             |      |

