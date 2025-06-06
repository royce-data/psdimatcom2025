+++
title = "General learning of Electric Response in Inorganic Materials"
template = "item.html"
[extra]
author = "Bradley Martin"
institution = "University College London"
author_url = ""
time = "12:45 BST"
highlight = false
+++

Polar materials with spontaneous polarisation are a promising approach to novel photovoltaics. However, few of these materials have sufficient optical absorption to function in devices. Therefore, we seek materials with large shift currents, polarisations and optical absorption.

While Density Functional Theory is a powerful tool for linking structure to properties, it struggles with the scale and complexity of chemical space and is limited to smaller system sizes. Equivariant graph neural networks (EGNN) have emerged as efficient and scalable alternatives for material design, though they typically predict energies and forces, not response properties.

We extend the MACE EGNN architecture to include external electric fields, enabling prediction of response properties—polarisation, Born effective charges, and polarisability. This "MACE-field" inherits and expands upon pre-trained MACE foundation models.

We fine-tune MACE-field on the MACE-MPA-0 foundation model and response properties calculated for 5,000 dielectric materials from the MP-dielectric dataset. We demonstrate the model's ability to capture nonlinear ferroelectric properties such as polarisation hysteresis, domain switching, and shift currents. Future work will target high-throughput screening for new polar photovoltaic materials.