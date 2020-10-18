# ARIES-Algorithm
ARIES algorithm as an example of a recovery algorithm used in database systems.

The ARIES recovery procedure consists of three main steps:

[Analysis](#analysis-table)

[REDO](#redo)

[UNDO](#undo)

## Analysis Table

The analysis step identifies the dirty (updated) pages in the buffer

## Redo

Apply REDO to all operations which are committed after the last system checkpoint.

## Undo

Apply UNDO to all operations which are uncommitted after the last system checkpoint.
