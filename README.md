# Computational Simulation of Decoherence on Nitrogen-Vacancy Centers due to Paramagnetic Impurities in Nanodiamonds

Nitrogen-Vacancy defects in diamond is one of the most well known physical realisation of a quantum bit due to its natural trapping of a two-level quantum system. Its phase information which is an important aspect in quantum computation is constantly affected by its surrounding paramagnetic impurities, causing it to decohere. This work investigates the bulk and surface impurities in a 10×10×10 nm−3 nanodiamond as sources of decoherences through computational modelling simulations using PyCCE. This work also reports observations that further justifies the need for high purity diamond samples that harbours NV qubits, and suggests an optimal NV depth of 2 - 3 nm from the diamond surface and Phosphorous-31 as another alternative for surface termination that improves coherence time T<sub>2</sub>.

## TLDR
- `Tutorial` file contains the basic tutorial and codes for using the PyCCE package, for documentation click [here](https://pycce.readthedocs.io/en/latest/index.html#).
- for BULK impurities, `Carbon 13' and 'Nitrogen' files contains codes and parameters used for simulating decoherence due to substitutional <sup>13</sup>C isotopes and <sup>14</sup>N atoms.
- for SURFACE impurities, `Electron` and `Nuclear Spins` files contains codes and parameters used for simulating decoherence due to dangling bonds modelled by point electron particles that also bonds with fabrication impurites <sup>1</sup>H, <sup>19</sup>F, <sup>31</sup>P atoms.

## Investigation stages
- identified feasibiity of obtaining an estimate decoherence time T<sub>2</sub> by curve fitting method. Due to large isotope configurations and fitting uncertainty, obtained deviation percentage of 26.046%.
- measured decoherence time due to concentration of <sup>13</sup>C and <sup>14</sup>N, and due to distance between NV center and a <sup>14</sup>N atom in a fixed configuration of naturally abundant <sup>13</sup>C spin bath.
- measured decoherence time due to concentration of surface electrons and paramagnetic nuclear impurities <sup>1</sup>H, <sup>19</sup>F, <sup>31</sup>P, and due to distance of NV center from model surface.
