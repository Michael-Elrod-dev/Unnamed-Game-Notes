### Summary

Resources sit on map tiles outside the city. Workers are assigned to a node, travel to it, and collect until the node is exhausted or the job is cancelled.

### Rules

- The player assigns a number of workers to a node. More workers finish the job faster.
- Before committing, the job previews its full cost in turns, covering travel out, collection, and travel back.
- Collection is incremental. Resources accumulate each turn the workers are on the node. A job that never finishes still returns everything it gathered up to that point.
- A job in progress can be cancelled. The workers turn around and walk home.
- Movement is a fixed number of tiles per turn, so a late cancel can still get everyone killed.
- Sending workers on a job that cannot finish before the fog arrives is allowed and not blocked.
- Anything caught in the fog when it rolls in is lost immediately. See [[Raid Sequence]].

### Workers are expendable

Because collection is incremental, spending workers to squeeze a last batch out of a node is real play and not a mistake. This matters most before a boss, where the economy has no future and material does. Workers being cheap is what makes that a decision instead of a trap.

### Distance

Richer nodes sit farther from the city, so reward scales with exposure.

- **Open:** How steeply value scales with distance.

### Open

- **Open:** The resource types.
- **Open:** Whether workers outside the fog can be attacked or captured during a raid, the way Civ settlers can.
- **Open:** Whether nodes are finite per run or regenerate.

### Interacts with

- [[Units]]
- [[Turns & Days]]
- [[Raid Sequence]]
