# RISC-V RTL DESIGN
## INTRODUCTION
The RISC-V (pronounced "risk-five") processor is an open-source instruction set architecture (ISA) that has gained significant attention and popularity in recent years. It is designed to be simple, modular, and extensible, making it suitable for a wide range of applications, from embedded systems to high-performance computing.

RISC-V follows the principles of Reduced Instruction Set Computing (RISC), emphasizing simplicity and efficiency. Its clean and elegant design features a small number of core instructions that perform basic operations. Additional functionality can be added through optional extension modules, allowing for customization and scalability based on specific application requirements.

One of the key advantages of RISC-V is its open nature. The ISA specification is freely available, allowing anyone to study, implement, and modify it without any licensing restrictions. This openness has fostered a vibrant ecosystem of hardware and software developers, resulting in a wide variety of RISC-V implementations, tools, and libraries.

Modularity is another significant aspect of RISC-V. The ISA is divided into different base integer instruction sets (RV32I, RV64I, RV128I) with optional extensions for floating-point operations, multiplication and division, atomic operations, vector processing, and more. This modular approach enables system designers to tailor their RISC-V implementations to meet specific performance, power, and area requirements.

RISC-V processors have found applications in diverse fields, including embedded systems, Internet of Things (IoT) devices, smartphones, data centers, and supercomputers. The flexibility and scalability of the architecture, combined with the growing ecosystem, make it an attractive choice for both academic research and industrial development.

Thus, the RISC-V processor offers an open and flexible architecture that combines simplicity, modularity, and extensibility. Its broad range of applications, along with the active community support, has positioned RISC-V as a promising alternative to traditional closed-source ISAs, driving innovation and fostering collaboration in the processor design space. With its open nature and adaptability, RISC-V is poised to shape the future of computing and enable advancements in various domains.

## Output Waveforms
<br>
<p align="center">
  <img src="./TopModule.png" alt="Image Alt Text" style="margin-bottom: 2px" /><br>
  Top Module
</p>
<br>
<p align="center">
  <img src="./PCMux.png" alt="Image Alt Text" style="margin-bottom: 2px" /><br>
  PC Mux
</p>
<br>
<p align="center">
  <img src="./RegBlock1.png" alt="Image Alt Text" style="margin-bottom: 2px" /><br>
  RegBlock 1
</p>
<br>
<p align="center">
  <img src="./ImmediateGenerator.png" alt="Image Alt Text" style="margin-bottom: 2px" /><br>
  Immediate Generator
</p>
<br>
<p align="center">
  <img src="./ImmediateAdder.png" alt="Image Alt Text" style="margin-bottom: 2px" /><br>
  Immediate Adder
</p>
<br>
<p align="center">
  <img src="./IntegerFile.png" alt="Image Alt Text" style="margin-bottom: 2px" /><br>
  Integer File
</p>
<br>
<p align="center">
  <img src="./WireEnableGenerator.png" alt="Image Alt Text" style="margin-bottom: 2px" /><br>
  Wire Enable Generator
</p>
<br>
<p align="center">
  <img src="./InstructionMux.png" alt="Image Alt Text" style="margin-bottom: 2px" /><br>
  Instruction Mux
</p>
<br>
<p align="center">
  <img src="./BranchUnit.png" alt="Image Alt Text" style="margin-bottom: 2px" /><br>
  Branch Unit
</p>
<br>
<p align="center">
  <img src="./Decoder.png" alt="Image Alt Text"
  style="margin-bottom: 2px" /><br>
  Decoder
</p>
<br>
<p align="center">
  <img src="./Decoder1.png" alt="Image Alt Text"
  style="margin-bottom: 2px" /><br>
  Decoder
</p>
<br>
<p align="center">
  <img src="./MachineControl.png" alt="Image Alt Text"
  style="margin-bottom: 2px" /><br>
  Machine Control
</p>
<br>
<p align="center">
  <img src="./MachineControl1.png" alt="Image Alt Text"
  style="margin-bottom: 2px" /><br>
  Machine Control
</p>
<br>
<p align="center">
  <img src="./MachineControl2.png" alt="Image Alt Text"
  style="margin-bottom: 2px" /><br>
  Machine Control
</p>
<br>
<p align="center">
  <img src="./CSRFile.png" alt="Image Alt Text"
  style="margin-bottom: 2px" /><br>
  CSR File
</p>
<br>
<p align="center">
  <img src="./CSRFile1.png" alt="Image Alt Text"
  style="margin-bottom: 2px" /><br>
  CSR File
</p>
<br>
<p align="center">
  <img src="./CSRFile2.png" alt="Image Alt Text"
  style="margin-bottom: 2px" /><br>
  CSR File
</p>
<br>
<p align="center">
  <img src="./RegBlock2.png" alt="Image Alt Text"
  style="margin-bottom: 2px" /><br>
  Reg Block 2
</p>
<br>
<p align="center">
  <img src="./RegBlock2 1.png" alt="Image Alt Text"
  style="margin-bottom: 2px" /><br>
  Reg Block 2
</p>
<br>
<p align="center">
  <img src="./StoreUnit.png" alt="Image Alt Text"
  style="margin-bottom: 2px" /><br>
  Store Unit
</p>
<br>
<p align="center">
  <img src="./LoadUnit.png" alt="Image Alt Text"
  style="margin-bottom: 2px" /><br>
  Load Unit
</p>
<br>
<p align="center">
  <img src="./ALU.png" alt="Image Alt Text"
  style="margin-bottom: 2px" /><br>
  ALU
</p>
<br>
<p align="center">
  <img src="./WBMuxSelectionUnit.png" alt="Image Alt Text"
  style="margin-bottom: 2px" /><br>
  WB Mux Selection Unit
</p>
<br>
<p align="center">
  <img src="./Result.jpg" alt="Image Alt Text"
  style="margin-bottom: 2px" /><br>
  Result
</p>