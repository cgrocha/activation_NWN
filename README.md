# activation_NWN
Simulation of the electrical activation of a silver nanowire network (NWN).

* (left panel) Wires are mapped as red sticks and their connections (black dots) are initially described by capacitors. Charge is sourced and drained on the electrodes (blue vertical sticks) and gradually some capacitive junctions can be activated (turned into resistors) if the voltage drop across the junction overcome their characteristic breakdown voltage. Yellow stars represent junctions activated at the present step which subsequently turn green (past activated junctions).

* (right panel) Graph representation of the network (left panel) which monitors the evolution of the network connectivity offset and detects the formation of a percolative path linking the electrodes (blue circles). Wires are represented initially by disconnected red nodes. As the network is gradually "awaken", the nodes acquire edges and breadth-first search algorithm is set to determine the shortest path linking the electrodes once it is formed.
