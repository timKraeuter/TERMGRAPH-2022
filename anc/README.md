
# BPMN specific properties

## Safeness

The atomic property **Unsafe** is implemented by the following graph condition in groove:

![Atomic property Unsafe implemented in groove.](./Unsafe.png)

The property matches whenever two tokens of one process snapshot have the same position (but have different identities).

## Soundness

The atomic property **AllTerminated** is implemented by the following graph condition in groove:

![Atomic property AllTerminated implemented in groove.](./AllTerminated.png)

The property matches whenever there is no process snapshot in the state running. This all process snapshots are terminated, i.e., have no tokens.
