# 8s-LiPo-Charger

Here is the design of my 8s LiPo charger. The specs are:
- 1 to 8 cells in series
- charge current of up to 5A
- balanced charging (individual cell charging)
- high efficiency (removed most diodes)

# The design is devided into several sections which are simulated in LTSpice:
- Voltage conversion stage
-- buck boost circuit
- current measurement
- voltage measurement
- output switching matrix to access the individual cells
