# 33-Direction Proof of Kochen-Specker

While the original **Kochen-Specker theorem** used 117 directions to show the impossibility of pre-assigned spin values, John Conway and Simon Kochen simplified the proof using a configuration of **33 directions**.

## Geometric Construction
The proof is based on the symmetry axes of a cube (and its dual, the octahedron).
- The 33 directions are derived from the centers of faces, midpoints of edges, and vertices of a cube, along with rotations of these cubes by 45 degrees.
- Specifically, Conway uses four cubes: a central white cube, and red, green, and blue cubes rotated 45 degrees about the coordinate axes.

## The Logical Contradiction
The proof proceeds by attempting to color each direction "black" (1) or "white" (0) while satisfying two rules derived from the [[20260704120100-kochen-specker-theorem-101-property|101 Property]]:
1. Two perpendicular directions cannot both be white (0, 0).
2. Three perpendicular directions must contain exactly one white spot (1, 0, 1).

By following the chain of logical deductions for the 33 directions, one eventually reaches a state where two perpendicular directions are forced to be white, which contradicts Rule 1.

## Conclusion
Since no consistent assignment of 0s and 1s exists for these 33 directions, the squared spin components cannot have predetermined values.

---
- **Source**: [[20260704120000-conway-kochen-free-will-lecture-2]]
- **Tags**: #geometry #quantum-mechanics #kochen-specker #mathematics
