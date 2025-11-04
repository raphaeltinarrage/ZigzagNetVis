# ZigzagNetVis

Repository relative to our paper <a href="https://ieeexplore.ieee.org/document/10844578">ZigzagNetVis: Suggesting temporal resolutions for graph visualization using zigzag persistence</a><br>
Raphaël Tinarrage, Jean R. Ponciano, Claudio D. G. Linhares, Agma J. M. Traina, and Jorge Poco.<br>
IEEE Transactions on Visualization and Computer Graphics **31**, 1–18 (2025)

In data analysis, **temporal graphs** constitute a powerful framework for modeling dynamic and complex systems. In this context, our work has focused on two questions:
- the automatic suggestion of **temporal resolution** (or timeslice length), a crucial parameter at the basis of many analysis techniques,
- the **visual representation** of the temporal graph, allowing the user to explore the data and detect patterns or anomalies.

We adress both problems from the perspective of Topological Data Analysis, and more specifically zigzag persistent homology.

## Software demonstration

Link to prototype: http://visualdslab.com/zigzagnetvis/

A Jupyter notebook, including our implementations of resolutions suggestion and colored barcodes, is found at https://github.com/raphaeltinarrage/ZigzagNetVis/blob/main/Demo.ipynb

## Example

An example of the ZigzagNetVis system using the Primary School network.

![TDANETVis](img/TDANetVis_Frontend.png?raw=true "TDANetVis")
