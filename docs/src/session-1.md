# Session 1: Understanding chip design

Have you ever wondered what powers the millions of electronic devices around
you? Which electrical component kickstarted the digital revolution? Starting
with transistors, then gates, logic blocks and ending with entire chips, the
semiconductor industry is an amazing feat of humanity. Chips, or Application
Specific Integrated Circuits (ASICs), are hidden everywhere: in Huawei cell
towers, in Samsung RAM memory controllers, and Apple’s M-series chips. They are
so ubiquitous yet they are nearly forgotten and overlooked.

## The basics

So, how's it all done then? First, let's get some terminology sorted. Chip
design, is also known as **IC design**, IC being short for integrated circuit.
You'll see ASIC thrown around as well, which means the same thing, and expands
to application-specific integrated circuit.

The key piece of intuition here is to grasp the layers of abstraction involved.
Very roughly, the layers are:

1. Electrons
2. Transistors (pn junctions)
3. Logic gates
4. Flops and logic primitives
5. Functional blocks, e.g. adders
6. Processors/cores
7. Systems-on-chip (SoCs)
8. Firmware / bare metal code
9. Operating Systems
10. Userland applications
11. Web applications

The second piece of intuition is that it's all just circuits. We're designing
circuits with logic gates that carry out a particular _logic function_. This
could be anything. For a CPU, it might be an instruction decoder that generates
corresponding control signals for the rest of the pipeline, for a hardware
accelerator like ours, it's a robust matrix multiplier (matmul).

This brings us nicely to FPGAs. FPGAs are extremely useful in hardware design.
They allow us to, among other things, execute these logic functions at a much
higher speed than in simulation. While ASICs and FPGAs provide us with two
different ways of executing these functions, underneath it all, they are still
the same logic functions.

## The waterfall model

## Tools
