# miptvolf

Student work on [SweRVolf](https://github.com/chipsalliance/Cores-SweRVolf) within MIPT computer modeling course.


#### Run RISC-V compliance tests
Do all necessary steps as described on [SweRVolf](https://github.com/chipsalliance/Cores-SweRVolf) page, but:
  1. RISC-V compliance tests are already added to repo as submodule.
  2. Run make with `make TARGETDIR=$CORES_ROOT/Cores-SweRVolf/riscv-target/ RISCV_TARGET=swerv RISCV_DEVICE=rv32i RISCV_ISA=rv32imc TARGET_SIM=$WORKSPACE/build/swervolf_0.6/sim-verilator/Vswervolf_core_tb RISCV_PREFIX=riscv32-unknown-elf-`. 
