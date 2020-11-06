# Teach Your Peers JavaScript: freeCodeCamp Teach EloquentJS \(Chapter 7\)

## Chapter 7: Project: A Robot

> **Brandon Knox**

### Graph Concept

* Graphs are collections of points with lines in between them
  * The points will be our places in the village

### Graph Implementation

_Add function_

### Project Details

* The robot will pick up parcels from different places, each addressed to another place.

### Object Orientation

* To simulate the environment for this project, we have to define a virtual world that can describe it.

#### Issues

* Too complex
* Programs that are hard to understand and easy to break

### Village State

Rename this shit...

```javascript
class VillageState {
  constructor(place, parcels) {
    this.place = place;
    this.parcels = parcels;
  }
  
  move(destination) {
    if (!roadGraph[this.place].includes(destination)) {
      return this;
    } else {
      let parcels = this.parcels.map(p => {
        if (p.place != this.place) return p;
        return {place: destination, address: p.address};
      }).filter(p => p.place != p.address);
      return new VillageState(destination, parcels);
    }
  }
}
```

### Persistent Data

* A data structure that doesn't change can be called immutable or persistent

### Design and Simulation

```text
function runRobot(state, robot, memory) {
  for (let turn = 0;; turn++) {
  
  }
}
```

### Solving a State

* Many options available...

### Solving State Randomly



### Creating a New State



### Mail Trucks

* If a route exists that passes all places in the village, the robot could run the route twice and be guaranteed to be done.

### Pathfinding



### Pathfinding Robot



## Chapter 8: Bugs and Errors



