# Mechanical Engineering Assesment
### Sheil Sarda

The assembly shall have 1 active rotating DOF and shall be used to transmit a driven rotation from a motor to a spinning shaft where a generic appliance can be coupled

- Encoder (off-the-shelf)
- Bearings (off-the-shelf)
- Motor (off-the-shelf)
- Motor housing (custom)
- Shaft (custom)

![image info](/images/motor_assembly.png)

### Electrodynamic Rotary Motors for Precision Positioning

Most precision positioning stages are still driven by rotary motors for reasons such as size, cost, holding force, and controllability.

In addition to electrodynamic (electromagnetic) motors, non-magnetic motors such as piezoelectric linear and rotary motors have recently been adopted by precision motion engineers for unique features such as small size, high precision, low heat generation and self-locking capabilities.

## Off-the-self components

- DC Motor
- Encoder for DC Motor
- Spur gears

## Rationale for selected components and design

Selected a geared mechanism so as to enable scaling up or down the motor torque depending on the application. This is a more generic solution for torque-driven mechanisms using motors than directly connecting the motor shaft to the rotating assembly.

## Free-body diagram analysis for motor shaft

![image info](/images/free_body.png)

The above diagram describes the free-body diagram for the motor with a geared system. A couple of changes to reflect the changes to make this accurate for our assembly is that the Gear box has a gear ratio of 1:1, and the motor wheel on the other end of the gear box (away from the motor) represents the driven sub-assembly.

## Most likely cause of failure

The most likely cause of mechanical failure of this design is likely the motor shaft slipping the gears, causing the driven assembly's RPM to not match the motor's RPM. This can be eliminated if the gears are welded on to the shaft instead of secured purely by friction.

Other causes of failure could involve gears slipping after continued use due to wear-and-tear.

Other design changes could be to place the encoder at the other end of the assembly, closer to the driven part as opposed to the motor, since that would be able to factor in any changing gear ratios and still maintain a consistent RPM.
