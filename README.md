# Robotics Journey

Learning robot control, reinforcement learning and sim2real – from a single
BLDC joint to a learned policy running on a self-built 2-DoF hopping leg.

## Roadmap
- **Phase 0** – Setup: Ubuntu tower (RTX 2080 Super), remote access, Python/C++
- **Phase 1** – One joint: FOC, CAN-FD, PID cascade, impedance control (moteus-c1 + mj5208)
- **Phase 2** – Dynamics, MuJoCo modeling, system identification
- **Phase 3** – RL in simulation (PPO, MuJoCo Playground, domain randomization)
- **Phase 4** – Sim2real: hopping leg with 3D-printed gearbox, Raspberry Pi 5 + PREEMPT_RT
- **Phase 5** – Extras: ROS 2, Docker/CI, MPC, Isaac Lab

## Structure
- `notes/` – theory notes, plots, videos
- `sim/` – simulation code (MuJoCo, JAX)
- `hw/` – hardware control code (Python/C++)
- `cad/` – CAD and STL files
- `LOG.md` – session log

Progress is tracked session by session in [LOG.md](LOG.md).
