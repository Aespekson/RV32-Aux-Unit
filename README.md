# RV32-Aux-Unit

RV32-Aux-Unit is an MMIO accelerator engineered with the goal of working with a custom CPU and operating system, found in the Project Context section. 

The intent is explicitly not to be a production quality GPU, TPU, NPU, etc. This is instead being built with a focus on very simply helping the other two projects' biggest choke point. Project goals and non-goals for this unit will be defined after the other two projects are either complete, functional, or significant enough progress has been made for a clear heading for this project to be visible.

However, general goals that will almost certainly be included regardless of specific purpose can still be defined:
 - MMIO register interface
 - DMA
 - Simple benchmarking
 - Driver interface in MOS

The meta-, non-technical goal of this project is to both serve as a learning experience and to complement the other two projects.

## Status
RV32-Aux-Unit is not currently under development and will likely only be after the completion of RV32-Base and either during or after the development of MOS.

## Project Context
RV32-Aux-Unit is the final project in the below series of projects, which is why its technical processing goals are currently undefined. The other two projects are a RISC-V CPU and a custom minimal operating system, as below:

1. CPU (RV32-Base) [here](https://github.com/Aespekson/RV32-Base)
2. OS (MOS) [here](https://github.com/Aespekson/MOS)
3. Accelerator (RV32-Aux-Unit) [this repo](https://github.com/Aespekson/RV32-Aux-Unit)
