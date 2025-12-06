# VSD-RTLDesign_And_Synthesis

This repository documents learnings and lab work from the “RTL Design using Verilog with Sky130"


Welcome to the RTL Design Workshop — a practical learning journey into the world of digital logic design using Verilog. This repository is organized as a multi-day series, with each day featuring guided labs, annotated code, and step-by-step explanations to help you build, simulate, and synthesize real digital circuits from scratch.

📘 About This Workshop
This hands-on workshop is designed for students, hobbyists, and early-career engineers looking to build a strong foundation in digital design using open-source tools. You’ll explore the entire flow from writing Verilog code to synthesizing it with the Sky130 PDK.

🔧 What You’ll Learn:
Writing and simulating RTL designs using Verilog

Running functional simulations with Icarus Verilog and visualizing waveforms in GTKWave

Performing logic synthesis with Yosys and the Sky130 open-source process design kit

Hands on practice using Linux terminal or open-source FPGA environments

Understanding core concepts like:

Basics of Verilog Coding
Testbench creation
Standard cell libraries and their verilog modules
D Flip-Flop styles
Hold and setup time concepts
Basic optimization techniques
if-else, case, for, and generate statements
Gate level Synthesis
Inferred Latches
Simulation and Synthesis mismatch
🛠️ What You’ll Need Before You Start
To get the most out of this workshop, make sure you're comfortable with the following:

Fundamentals of digital circuits — logic gates, flip-flops, muxes, etc.

Basic command-line usage in a Linux terminal

A working Linux setup (or WSL if you're using Windows/macOS)

Installed tools:

git for version control
iverilog for compiling Verilog
gtkwave for viewing simulation waveforms
yosys for logic synthesis
Any code editor of your choice (e.g., VS Code, Vim, Nano)
📁Workshop Structure
The workshop is organized by day, each with a dedicated folder and Readme:

Day 1: Introduction to Verilog RTL Design & Synthesis (Introduction to Verilog RTL design and Synthesis/Readme.md)
Day 2: Timing Libraries, Synthesis Approaches, and Efficient Flip-Flop Coding (Hierarchical and Flat Synthesis/Readme.md) and (Synthesis_of_DFF_with_asynchronous_reset/Readme.md)
Day 3: Combinational and Sequential Optimization (Combinational and Sequential Optimizations/Readme.md)
Day 4: Gate-Level Simulation (GLS), Blocking vs. Non-Blocking in Verilog, and Synthesis-Simulation Mismatch (Gate Level Synthesis and its Importance/README.md)
Day 5: Optimization in Synthesis (Optimization in synthesis/README.md)
You don’t need a big budget to start designing chips.

When I first got into VLSI, I remember thinking:

“How does anyone even afford these tools?”

It felt like a field reserved for those with access to expensive licenses and high-end setups.

But that’s not the full story.

There’s now a powerful lineup of free, open-source tools that let you explore everything from RTL design to physical layout — right from your laptop.

If you’re serious about learning VLSI on your own terms, there are open source tools for RTL simulation and synthesis like:

Icarus Verilog + GTKWave – For simulation & waveform analysis
Yosys – End-to-end synthesis and layout
These tools are free, beginner-friendly, and used in real-world academic and open-source projects.

You don’t need perfect tools — just the right ones to begin.

📄License
This project is licensed under the Attribution 4.0 International License - see the LICENSE file for details.

🙏Acknowledgements
Shon Taware
Kunal Ghosh
Open-source tools providers like Yosys and Sky130 PDK.
