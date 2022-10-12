# Awesome rustsbi

> A curated list of awesome things related to rustsbi

# RustSBI libraries

- [rustsbi](https://github.com/rustsbi/rustsbi) - RISC-V Supervisor Binary Interface (RISC-V SBI) implementation in Rust [![crates.io](https://img.shields.io/crates/v/rustsbi.svg)](https://crates.io/crates/rustsbi)
- [sbi-testing](https://github.com/rustsbi/sbi-testing) - RISC-V SBI environment test suite [![crates.io](https://img.shields.io/crates/v/sbi-testing.svg)](https://crates.io/crates/sbi-testing)
- [sbi-rt](https://github.com/rustsbi/sbi-rt) - Simple RISC-V SBI runtime library; designated for supervisor use [![crates.io](https://img.shields.io/crates/v/sbi-rt.svg)](https://crates.io/crates/sbi-rt)
- [sbi-spec](https://github.com/rustsbi/sbi-spec) - Definitions and constants in RISC-V Supervisor Binary Interface (RISC-V SBI) [![crates.io](https://img.shields.io/crates/v/sbi-spec.svg)](https://crates.io/crates/sbi-spec)

# Platform support

- [rustsbi-k510](https://github.com/Gstalker/rustsbi-k510) - RISC-V SBI firmware support for Kendryte K510 platform
- [rustsbi-d1](https://github.com/rustsbi/rustsbi-d1) - RustSBI bootloader firmware and debug suite for Allwinner D1 SoC boards, including Nezha, Lichee and more 
- [rustsbi-hifive-unmatched](https://github.com/rustsbi/rustsbi-hifive-unmatched) - RustSBI support on SiFive FU740 board; FU740 is a five-core heterogeneous processor with four SiFive U74 cores, and one SiFive S7 core
- [rustsbi-qemu](https://github.com/rustsbi/rustsbi-qemu) - QEMU platform SBI support implementation
- [rustsbi-k210](https://github.com/rustsbi/rustsbi-k210) - Kendryte K210 SBI support using RustSBI, provides privileged spec 1.12 environment by emulating it using 1.9.1

# Kernels and firmwares

- [zCore](https://github.com/rcore-os/zCore) - Reimplement Zircon microkernel in Rust
- [rCore-Tutorial-v3](https://github.com/rcore-os/rCore-Tutorial-v3) - Let's write an OS which can run on RISC-V in Rust from scratch!
- [oreboot](https://github.com/oreboot/oreboot) - oreboot is a fork of coreboot, with C removed, written in Rust

# Documents

- [slides](https://github.com/rustsbi/slides) - All public report slides and articles related to RustSBI

# Bare metal support crates

- [hpm6750-pac](https://github.com/rustsbi/hpm6750-pac) - Embedded Rust Peripheral Access Crate for HPMicro HPM6750 chip series
- [xuantie](https://github.com/rustsbi/xuantie) - Low level access to T-Head Xuantie RISC-V processors [![crates.io](https://img.shields.io/crates/v/xuantie.svg)](https://crates.io/crates/xuantie)

# Useful Rust crates for implementations

- [dtb-walker](https://github.com/YdrMaster/dtb-walker) - Iterator device tree blob using cursor semantics [![crates.io](https://img.shields.io/crates/v/dtb-walker.svg)](https://crates.io/crates/dtb-walker)
- [os-xtask-utils](https://github.com/YdrMaster/os-xtask-utils) - Program executation for xtask in os or bootloader project [![crates.io](https://img.shields.io/crates/v/os-xtask-utils.svg)](https://crates.io/crates/os-xtask-utils)
- [serde-device-tree](https://github.com/rustsbi/serde-device-tree) - Serialize & deserialize device tree binary using serde [![crates.io](https://img.shields.io/crates/v/serde-device-tree.svg)](https://crates.io/crates/serde-device-tree)

# Prototypes

- [rustsbi-nezha](https://github.com/ez4yunfeng2/rustsbi-nezha) by @ez4yunfeng2
- [rustsbi-D1](https://github.com/wangtao-creator/rustsbi-D1) by @wangtao-creator
