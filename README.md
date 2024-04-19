# FCCM 2024 Poster Presentation
## The BRAM is the Limit: Shattering Myths, Shaping Standards, and Building Scalable PIM Accelerators
MD Arafat Kabir, Tendayi Kamucheka, Nathaniel Fredricks, Joel Mandebi, Jason Bakos, Miaoqing Huang, and David Andrews

### Abstract
Many recent FPGA-based Processor-in-Memory (PIM) architectures have appeared
with promises of impressive levels of parallelism but with performance that
falls short of expectations due to reduced maximum clock frequencies, an
inability to scale processing elements up to the maximum BRAM capacity, and
minimal hardware support for large reduction operations. In this paper, we
propose a “Standard” set of design objectives for PIM array-based FPGA designs.

We then propose a PIM array-based GEMV accelerator architecture as a case study
to show the proposed Standard can be realized in practice. The GEMV accelerator
serves as existence proof that dispels several myths surrounding what is
normally accepted as clocking and scaling FPGA performance limitations.
Specifically, the proposed accelerator clocks at the maximum frequency of the
BRAM and scales to 100% of the available BRAMs. Comparative analyses show
execution speeds over existing PIM-based GEMV engines on FPGAsand achieving a
2.65× – 3.2× faster clock. An AMD Alveo U55 implementation achieves a system
clock speed of 737 MHz, providing 64K bit- serial multiply-accumulate (MAC)
units for GEMV operation.

![Poster](https://github.com/Arafat-Kabir/FCCM-2024-Poster/blob/main/poster-A1.png?raw=true)
