# Maximum Entropy Principle Mechanism:Path-Selection with the largest energy difference

Analysis of the Maximum Entropy Principle


In the SEQ model, the maximum entropy principle is manifested through the driving tendency of entropy increase: energy not only flows from a higher-energy SEQ to an adjacent lower-energy SEQ, but it also follows the path with the largest energy difference.

For example, consider an SEQ i, which is adjacent to two other SEQ j and k. The energies carried by nodes i, j, and k are A, B, and C respectively, where A > B > C. In this case, there are two possible energy transfer paths from SEQ i according to the principle of entropy increase: path i→j or path i→k. We will analyze the entropy change for each path separately.

Under the constraint of energy conservation (i.e., A + B + C = constant), the entropy of the local system composed of these three SEQ before energy transfer is:S = A×B×C 

Path i→j: transferring energy to node j (which has relatively higher energy):S′= (A − 1)(B + 1)C = (A − 1)(BC + C)

Path i → k: transferring energy to node k (which has lower energy): S″= (A − 1)B(C + 1) = (A − 1)(BC + B)

Here, "1" represents one unit of Planck constant h. Since B > C ⇒ BC + B > BC + C ⇒ S″> S′, the entropy increases more along the i→k path—that is, the path with the larger energy difference leads to a greater increase in entropy.

This deduction can be easily generalized to cases where the number of adjacent nodes is greater than two, so a detailed proof is omitted here.

However, it should be emphasized that the path with the maximum energy difference is not necessarily unique. Therefore, for states that have not yet occurred, the future still retains sufficient degrees of freedom — the evolution is not entirely deterministic.

Zou, Z. K. (2025). Multiplicative Entropy Encodes Time-Causality; Gauge Mediates Mass-Gravity. Zenodo. https://doi.org/10.5281/zenodo.15890328
