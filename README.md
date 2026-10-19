# Geometric Reconstruction and Mechanical Analysis of the B&M Clamshell Lap Restraint

**An independent working paper by u/lucky_3838**  
19 October 2026 revision · 67 pages · English  
First edition: 17 October 2026 · 54 pages

**[Read the revised paper (PDF)](Geometric_Reconstruction_and_Mechanical_Analysis_of_the_BM_Clamshell_Lap_Restraint.pdf)**

How does the B&M Hyper-family clamshell lap restraint lock, release and transfer loads? This study reconstructs its internal geometry from publicly available drawing captures and photographs, then develops mechanical models around the reconstructed components.

The paper covers component identification, CAD sections and closing sequences on both sides; pawl-sector contact and the release linkage; axial arrangement and load paths; internal forces and nominal stresses; and conditional upward, forward and combined load scenarios.

## New in the 19 October revision

- Numerical motion readings recovered from 2,898 identified frames of CoasterStats' chest-mounted Mako recording, with source-video timing and explicit recognition gaps.
- Comparisons using confirmed longitudinal and vertical readings from the same frame. Interpolation completes the presentation curves only and is excluded from the structural comparisons.
- Separate contact assumptions for upward loading, combined upward and forward loading, and braking while the seat remains loaded.
- Comparisons across seven conditional closure pairs and three assumed pad-contact positions, with sensitivity to material and stiffness assumptions.
- Revised explanations, vector figures and native LaTeX subfigures.

The recovered longitudinal and vertical minima occur 9.5 seconds apart. Combining those separate minima would create a load vector that was not observed in the recovered record. The recording also contains an unresolved disagreement between its overview's written longitudinal minimum and its onride numerical minimum indicator; both are documented.

## An example of what the results mean

The most demanding selected comparison assumes braking through the pad, a force directed 60 degrees above the forward horizontal, and application at the outer end of the ideal contact segment:

| Assumed occupant mass | Calculated resultant force on the bar | Model nominal yield threshold for that direction and configuration |
|---|---:|---:|
| 150 kg | 2.502 kN | 3.251 kN |
| 200 kg | 3.335 kN | 3.251 kN |

The threshold is the applied force at which an included calculated nominal section stress first reaches its assumed yield strength of 355 MPa. The 150 kg force is below that threshold and the 200 kg force above it. These comparisons do not establish actual yielding, fracture, release, an allowable passenger mass or who can physically fit. Contact geometry, installed material properties, transmission and anchorage resistance, and dynamic effects remain unresolved.

This combined-load threshold uses a different force direction and contact position from the original 4.66 kN purely upward reference at the central contact position.

## Authorship and scope

I performed the reverse engineering from images and the complete CAD reconstruction, developed the mechanical interpretation and dimensional estimates, directed the calculations, and critically reviewed the analysis and manuscript throughout the project.

AI assistance was used for calculations and to improve the clarity of the text.

This is a personal technical study, outside my professional specialism. I have no affiliation with B&M, and this work is not part of an accident investigation. Its numerical estimates depend on reconstructed geometry and stated assumptions; they do not establish certified capacities, passenger mass limits or operating criteria.

Image credits and source references are included in the paper. The motion recording is by [CoasterStats](https://www.youtube.com/watch?v=7z4nijr7ExM); readings recovered from its video display are not original instrument data or measured pad forces.
