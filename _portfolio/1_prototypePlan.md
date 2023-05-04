---
caption: #what displays in the portfolio grid:
  title: Prototype Plan
  subtitle: April 6
  thumbnail: assets/img/portfolio/alu_whiteboard_3x2.jpg
  
#what displays when the item is clicked:
title: Prototype Plan
subtitle: April 6
image: assets/img/portfolio/alu_whiteboard_3x2.jpg #main image, can be a link or a file in assets/img/portfolio
alt: image alt text

---
We met during the regular class time to figure out what we could build for the prototype demonstration. We landed at a half size (16-bit) ALU, and identified what all that would entail. We aimed to be able to perform each of the arithmetic and logical operations included in the RV32E ISA, which are `ADD`, `SUB`, `AND`, `OR`, `XOR`, `SLL`, `SRL`, and `SRA`. We finished with the following diagram:

![A drawing on a whiteboard of the design of our ALU](assets/img/alu_whiteboard.jpg)

This diagram includes:

- Discrete components for performing addition, bitwise OR, and bitwise XOR
- A pair of inverting and non-inverting tri-state buffers on both inputs
- Tri-state buffers for every output, which are selected by a decoder
  - Including an inverting buffer on the output of OR, allowing bitwise AND
- A shift unit that was undecided based on difficulty level, which was later downgraded to a microcontroller