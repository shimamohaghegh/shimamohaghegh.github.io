---
title: "A Novel Multiplier Hardware Organization for Finite Fields Defined by All-One Polynomials"
collection: publications
category: manuscripts
permalink: /publication/2022-aop-multiplier-tcas2
excerpt: 'A new multiplier hardware organization for finite fields defined by all-one polynomials (AOPs), targeting lower power and smaller area.'
date: 2022-12-01
venue: 'IEEE Transactions on Circuits and Systems II: Express Briefs, vol. 69, no. 12, pp. 5084-5088'
paperurl: 'https://doi.org/10.1109/TCSII.2022.3188567'
citation: '<b>S. Mohaghegh</b>, S. Kondo, G. Yemiscioglu and A. Muhtaroglu, &quot;A Novel Multiplier Hardware Organization for Finite Fields Defined by All-One Polynomials,&quot; <i>IEEE Transactions on Circuits and Systems II: Express Briefs</i>, vol. 69, no. 12, pp. 5084-5088, Dec. 2022.'
---
This brief proposes an energy-efficient hardware organization for a finite field multiplier based on irreducible all-one polynomials (AOPs). The design splits the computation into three submodules: a left-shifting network for reduction, an AND network for multiplication, and a three-input XOR tree for accumulation. State-of-the-art implementations instead distribute these operations across a systolic array, which is regular in layout but costly in staging registers. Flattening the organization lowers latency and register count, which removes bypassing problems and reduces cost and power dissipation at a given clock frequency constraint.

Both the proposed and the previously reported organizations were implemented in Verilog for GF(2^162), GF(2^268) and GF(2^562) using a TSMC 90 nm standard cell library, and synthesized at three frequency targets with the Cadence Genus tool. Across field sizes and frequencies, the proposed organization achieved average reductions of 18% in leakage, 31% in dynamic capacitance and 19% in area, making it a candidate for compact, energy-constrained systems such as wireless sensors and wearable devices that rely on elliptic curve cryptography.

[Read the paper (DOI: 10.1109/TCSII.2022.3188567)](https://doi.org/10.1109/TCSII.2022.3188567)
