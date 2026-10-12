# Mikroverk

**The microworks.** Open-source emulators, simulators, runtimes and tools for embedded systems.

In Swedish, *verk* can mean the works of a machine (*urverk*, clockwork) or an industrial works—
or a work of art, music or literature (*konstverk*, *mästerverk*).
Mikroverk brings those meanings together: a small workshop, and the things we make in it.
Software that runs on, or pretends to be, very small machines.

## What we build

- **Emulators and simulators** that let you run and debug firmware without the hardware,
  and see inside it: every register, every packet, every cycle.
- **Network simulation** for low-power wireless and IoT, from a single node to thousands.
- **Runtimes and tools** for devices where memory is counted in kilobytes and energy in microjoules.

## Projects

| Project | What it is |
|---|---|
| [esp32sim](https://github.com/mikroverk/esp32sim) | ESP32 simulator |
| [cooja-ng](https://github.com/mikroverk/cooja-ng) | Next-generation network simulator for embedded and IoT systems. Runs real, unmodified Contiki-NG firmware on emulated MSP430, ARM Cortex-M and RISC-V cores — hundreds of mixed nodes on one deterministic, nanosecond-precise clock, with a live web UI. Written in portable C, about ten times faster than Cooja + MSPSim, and passes the full Contiki-NG Cooja test suite. |

## How we work

Every cycle counts. We care about efficiency, determinism and transparency:
a simulator should show you what the real hardware hides.
Everything here is open source, and contributions are welcome.
Please read our [Code of Conduct](https://github.com/mikroverk/.github/blob/main/CODE_OF_CONDUCT.md).
Open an issue, send a pull request, or just try the tools and tell us what broke.
