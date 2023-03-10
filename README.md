# Engineering-Optimization-Algorithms-for-pressure-vessel-and-welded-beam-design using a gradient-based algorithm; Augumented Lagrangian Multiplier (ALM) with DPN and golden search methods and Particle Swarm Optimization respectively. 
The design variables, objective functions and constraint functions are already defined, these algorithms were used to search for the best design variables to optimize the objective.
1. The Pressure Vessel Design Problem Formulation.
1.1) The Design Variables.
There are four(4) design variables:
  The thickness of the shell (Ts), The thickness of the head (Th), The inner radius (R), The length of the cylindrical section of the vessel, not including the head (L).
1.2) The Objective Function.
  πππππππ§π π(π, πΏ,Ts, Th) = 0.6224TsππΏ + 1.7781Thπ2 + 3.1661(Ts)2πΏ + 19.84(Ts)2π
1.3) The Constraint Functions.
  Subject to: 0.0193π β€ Ts
  0.00954π β€ Th
  ππ2πΏ + 4/3ππ3 β₯ 1296000
  πΏ β€ 240
  0.1 β€ Ts β€ 99
  0.1 β€ Th β€ 99
  10 β€ π β€ 200
  10 β€ πΏ β€ 200
  
2. The Welded Beam Design Problem Formulation.
2.1) The Design Variables.
  There are four(4) design variables:
  The Height of weld (h), The Length of weld (L), The Height of the beam (t), The Width of the beam (b).
2.2) The Objective Function.
  πππππππ§π π(h,L,t,b) = 1.10471β2πΏ + 0.04811tπ (14.0 + πΏ)
2.3) The Constraint Functions.
  Subject to: π β€ πmax
  π β€ πmax
  β β€ π
  0.10471β2 + 0.04811 π‘ π (14.0 + πΏ) β€ 5
  0.125 β€ β
  πΏ β€ πΏmax
  π β€ πc
