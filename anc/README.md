
# BPMN specific properties

## Safeness

The atomic property **Unsafe** is implemented by the following graph condition in groove:

![Atomic property Unsafe implemented in groove.](./Unsafe.png)

The property matches whenever two tokens of one process snapshot have the same position (but have different identities).
