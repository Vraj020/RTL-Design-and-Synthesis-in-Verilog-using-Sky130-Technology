# RTL Design and Synthesis in Verilog using Sky130 Technology(28 May-6 JUNE'25)
![1748888349855-Photoroom](https://github.com/user-attachments/assets/ca5f31c8-d96d-4f70-99e0-9d18a97e310a)

The “RTL Design and Synthesis using Sky130” workshop, conducted by VSD-IAT, offers a structured and hands-on learning experience focused on digital design using Verilog HDL, RTL-to-gate-level synthesis, and ASIC design methodologies using Sky130, the open-source PDK developed by Google and SkyWater Foundry.

This 10-day workshop is tailored for electronics and VLSI enthusiasts aiming to build a strong foundation in the ASIC frontend design flow using 100% open-source EDA tools. Participants are guided through every step of RTL design, from simulation to synthesis and gate-level analysis, all using real industry workflows.

## 📖 Table of contents

 ## 🟢 Day 1:  Introduction to Verilog, Simulation & Synthesis Tools

- Basics of Verilog RTL coding

- Simulation using Icarus Verilog and waveform viewing with GTKWave

- Introduction to Yosys, an open-source synthesis tool

- Running synthesis on simple designs using the Sky130 standard cell library

## 🟢 Day 2: Timing Libraries and Synthesis Approaches
- Deep dive into timing libraries (.lib files)

- Understanding setup/hold times, propagation delays, and cell parameters

- Flat vs. hierarchical synthesis

- Best practices for writing efficient RTL

## 🟢 Day 3: Combinational & Sequential Optimization
- Logic optimization techniques for combinational designs

- Sequential optimization: flops, latches, and state machines

- Gate-level netlist generation and analysis

## 🟢 Day 4 : Gate-Level Simulation (GLS) & Constraints

- Introduction to Gate-Level Simulation (GLS) using synthesized netlists

- Delay annotation and SDF file generation

- Importance of constraints files (.sdc) in synthesis

- Writing basic SDC for clock definitions and timing constraints

## 🟢 Day 5 :  Design Exercises & Real-World Case Studies

- RTL design and synthesis of real-world digital blocks

- End-to-end flow: from RTL to GLS using Sky130

- Recap of key concepts and discussion on industry relevance

## Day 1 – Introduction to Verilog, Simulation & Synthesis Tools
# 🔰 Objective:
To understand the basics of Verilog HDL, simulate simple RTL designs using open-source tools, and perform basic synthesis using the Sky130 standard cell library.

# 📚 Topics Covered:
- Introduction to Verilog HDL

- Installing and using Icarus Verilog (iverilog) for simulation

- Viewing simulation waveforms with GTKWave

- Basics of logic synthesis using Yosys

- Introduction to the Sky130 open-source standard cell library

# 🛠️ Tools Used:
- Icarus Verilog – Verilog simulation

- GTKWave – Waveform viewer

- Yosys – RTL synthesis

- Sky130 PDK – Standard cells for synthesis
## Screenshots:
![Screenshot (209)](https://github.com/user-attachments/assets/0c694464-ee79-41ca-b248-2a995c5f736c)
![Screenshot (210)](https://github.com/user-attachments/assets/f7da9f24-3087-419b-b1ac-4932128f507a)
![Screenshot (212)](https://github.com/user-attachments/assets/9392ebed-0fd4-42bb-ac05-53d207d93fd6)
![Screenshot (213)](https://github.com/user-attachments/assets/8b017cba-be36-48ff-9568-0fe95a6e33db)
![Screenshot (215)](https://github.com/user-attachments/assets/ac0dfb14-be96-4da7-b4f6-0658afd91c77)

## Lab Screenshots:
![VirtualBox_VSDSQUADRON_29_05_2025_15_08_55](https://github.com/user-attachments/assets/cb6733db-2b9f-4360-9ca5-d17a2799f544)
![VirtualBox_VSDSQUADRON_29_05_2025_15_14_02](https://github.com/user-attachments/assets/a29b0891-7914-433a-b7c2-3e1fe13cfc99)
![VirtualBox_VSDSQUADRON_29_05_2025_15_19_02](https://github.com/user-attachments/assets/3bdb14dd-1025-412e-9952-46fa44f43a30)
![VirtualBox_VSDSQUADRON_29_05_2025_15_23_10](https://github.com/user-attachments/assets/cdcae57f-c9c7-4b04-860e-8a08811f3830)
![VirtualBox_VSDSQUADRON_29_05_2025_15_52_36](https://github.com/user-attachments/assets/eeca955b-61ea-451d-8e8e-4401c7699405)
![VirtualBox_VSDSQUADRON_29_05_2025_16_04_20](https://github.com/user-attachments/assets/d116fc94-5885-4631-9b3a-64b1a4bbde99)
![VirtualBox_VSDSQUADRON_29_05_2025_16_04_31](https://github.com/user-attachments/assets/50251a68-826b-4ced-a9d2-233c8b319d9b)
![VirtualBox_VSDSQUADRON_29_05_2025_16_06_44](https://github.com/user-attachments/assets/a4924675-02d0-4450-9c51-4a41f1f6e7de)
![VirtualBox_VSDSQUADRON_29_05_2025_16_07_32](https://github.com/user-attachments/assets/03a5abab-9bda-4684-9788-bebeb0f44c19)

# 📌 Key Learnings:
- Writing simple combinational and sequential Verilog modules

- Simulating RTL code and debugging using GTKWave

- Understanding the synthesis flow and analyzing synthesized netlists

- Recognizing the role of standard cells and timing libraries in synthesis

## 🗓️ Day 2 – Timing Libraries and Synthesis Approaches

# 🔰 Objective:
To explore timing libraries, understand their parameters, and compare hierarchical vs. flat synthesis. Practice efficient RTL coding styles using Yosys and Sky130 libraries.

# 📚 Topics Covered:
- Structure and significance of .lib (timing library) files

- Parameters: setup time, hold time, delay, power

- Hierarchical vs. Flat Synthesis

- RTL coding styles for flip-flops and latches

# 🛠️ Tools Used:
- Yosys

- Sky130 .lib files
## Lab Screenshots:
![VirtualBox_VSDSQUADRON_29_05_2025_22_44_48](https://github.com/user-attachments/assets/ef2aa2bd-171e-49e2-a8e6-945b0c3750fa)
![VirtualBox_VSDSQUADRON_29_05_2025_22_46_41](https://github.com/user-attachments/assets/f8bfb80b-b522-4b50-b6c1-294afe4cc972)
![VirtualBox_VSDSQUADRON_29_05_2025_22_58_09](https://github.com/user-attachments/assets/154bc64f-dc26-480e-a413-f309498bbf7e)
![VirtualBox_VSDSQUADRON_29_05_2025_22_58_58](https://github.com/user-attachments/assets/4f74714e-fc53-4651-ad4b-a96018a9879f)
![VirtualBox_VSDSQUADRON_29_05_2025_23_01_28](https://github.com/user-attachments/assets/3978e684-3164-4711-bc05-fec88d270a3e)
![VirtualBox_VSDSQUADRON_29_05_2025_23_03_42](https://github.com/user-attachments/assets/2229f629-a07e-4ec0-8e61-0d007126e45f)
![166147855-692033f0-08e1-465f-98b6-5a9fba6a3eb0](https://github.com/user-attachments/assets/1868a0a5-3a41-4c9f-83ec-3396f48450b3)
![VirtualBox_VSDSQUADRON_29_05_2025_23_04_28](https://github.com/user-attachments/assets/b93c2475-660d-43cb-b7d7-9f301156c317)
![VirtualBox_VSDSQUADRON_29_05_2025_23_11_23](https://github.com/user-attachments/assets/2eb0ef20-2b63-4121-8904-7c499459434b)
![VirtualBox_VSDSQUADRON_29_05_2025_23_12_57](https://github.com/user-attachments/assets/efdbf5dc-ea6d-4434-b519-feed153e5505)
![VirtualBox_VSDSQUADRON_29_05_2025_23_17_16](https://github.com/user-attachments/assets/6662e11a-4d53-4599-bf6b-930b163dd57e)
![VirtualBox_VSDSQUADRON_29_05_2025_23_17_46](https://github.com/user-attachments/assets/7f9a6b5b-f0d9-4182-9577-419f17d044de)
![VirtualBox_VSDSQUADRON_29_05_2025_23_21_43](https://github.com/user-attachments/assets/737677fc-1b5e-4b1d-8f60-8c648b23877f)
![VirtualBox_VSDSQUADRON_29_05_2025_23_21_53](https://github.com/user-attachments/assets/bbbd44dc-0427-4bb0-9882-c661094fbe00)

# 📌 Key Learnings:
- Role of timing constraints in ASIC design

- Trade-offs between hierarchical and flat synthesis

- Writing optimized RTL for sequential elements

- Importance of standard cell characteristics in design timing
- 
## 🗓️ Day 3 – Combinational & Sequential Optimization

# 🔰 Objective:
To explore RTL optimization techniques for both combinational and sequential circuits, and understand their impact on synthesized designs.

# 📚 Topics Covered:
- Combinational optimization: constant propagation, redundant logic removal

- Sequential optimization: register retiming, clock gating

- Analyzing Yosys synthesis logs for optimization insight

- Generating gate-level netlists with Sky130 cells

# 🛠️ Tools Used:
- Yosys

- GTKWave

## Screenshots:
![Screenshot (217)](https://github.com/user-attachments/assets/b9fd0be7-5a64-470d-80ae-2cf6901b8549)
![Screenshot (218)](https://github.com/user-attachments/assets/dec1cd1d-ac0c-4675-9b87-2b8fdaff902d)

## Lab Screenshots:
![VirtualBox_VSDSQUADRON_30_05_2025_15_03_22](https://github.com/user-attachments/assets/5fc63fed-e60c-4643-ac7c-375a397727cd)
![VirtualBox_VSDSQUADRON_30_05_2025_15_05_34](https://github.com/user-attachments/assets/71c330ab-f240-4d77-b278-8775c9e03c50)
![VirtualBox_VSDSQUADRON_30_05_2025_15_06_03](https://github.com/user-attachments/assets/ef61de24-3548-4ede-8f82-9516244de678)
![VirtualBox_VSDSQUADRON_30_05_2025_15_08_25](https://github.com/user-attachments/assets/63d6d1ab-47c8-4b07-8500-1fc49a4dcc89)
![VirtualBox_VSDSQUADRON_30_05_2025_15_13_26](https://github.com/user-attachments/assets/e3a5d808-2b60-4233-9c17-76e5f573b1c4)
![VirtualBox_VSDSQUADRON_30_05_2025_15_15_17](https://github.com/user-attachments/assets/10a90d6a-1c71-4971-b9ca-90d8e3434e2d)
![VirtualBox_VSDSQUADRON_30_05_2025_15_42_25](https://github.com/user-attachments/assets/f5f4bdc2-b56c-4b22-905c-557405c29030)
![VirtualBox_VSDSQUADRON_30_05_2025_15_43_14](https://github.com/user-attachments/assets/a8428b3d-ae9a-40e2-9541-29f07369d7cd)
![VirtualBox_VSDSQUADRON_30_05_2025_15_46_04](https://github.com/user-attachments/assets/fa731116-8317-4db7-997b-cc16aa6dac93)
![VirtualBox_VSDSQUADRON_30_05_2025_15_48_42](https://github.com/user-attachments/assets/2f00e986-db75-4839-a075-dd594706dfdf)
![VirtualBox_VSDSQUADRON_30_05_2025_15_50_17](https://github.com/user-attachments/assets/1ecaae0d-e519-442a-8fc7-70c9e82204e9)
![VirtualBox_VSDSQUADRON_30_05_2025_15_51_36](https://github.com/user-attachments/assets/f1c36e24-21a0-4d53-9784-dcb72caab7f9)
![VirtualBox_VSDSQUADRON_30_05_2025_15_55_04](https://github.com/user-attachments/assets/b96eb323-545c-4573-9c78-69c99aed022e)
![VirtualBox_VSDSQUADRON_30_05_2025_15_56_29](https://github.com/user-attachments/assets/3dc645c0-3043-42d9-b257-8b43d3d97ebe)
![VirtualBox_VSDSQUADRON_30_05_2025_15_58_25](https://github.com/user-attachments/assets/e1af244a-2d14-417f-b817-25bad8666856)
![VirtualBox_VSDSQUADRON_30_05_2025_16_19_29](https://github.com/user-attachments/assets/f36170f0-43a0-402d-9c6c-307c63152f29)
![VirtualBox_VSDSQUADRON_30_05_2025_16_20_59](https://github.com/user-attachments/assets/4c27993c-680b-43a1-aefa-4eb38a0d7a96)
![VirtualBox_VSDSQUADRON_30_05_2025_16_21_15](https://github.com/user-attachments/assets/94e14c5e-90bd-4a22-bb7c-009d3e75c761)
![VirtualBox_VSDSQUADRON_30_05_2025_16_25_34](https://github.com/user-attachments/assets/50771cb5-0806-47ef-b99a-15dec8bce900)
![VirtualBox_VSDSQUADRON_30_05_2025_16_26_17](https://github.com/user-attachments/assets/9eba65a7-9066-404c-8939-d3796cbbc9d3)
![VirtualBox_VSDSQUADRON_30_05_2025_15_59_45](https://github.com/user-attachments/assets/5e48efac-c238-4c5f-9a29-8c19038be2e9)
![VirtualBox_VSDSQUADRON_30_05_2025_16_00_52](https://github.com/user-attachments/assets/abe8e9c0-e226-4aa7-9352-ca71254ceacb)
![VirtualBox_VSDSQUADRON_30_05_2025_16_01_11](https://github.com/user-attachments/assets/f055ef7f-18ac-4743-a0c9-5f25235c5bbc)
![VirtualBox_VSDSQUADRON_30_05_2025_16_02_02](https://github.com/user-attachments/assets/5a3bb3f2-fb60-429b-b60c-9a6d55af7ef0)
![VirtualBox_VSDSQUADRON_30_05_2025_16_03_00](https://github.com/user-attachments/assets/70ea0e42-a4bf-4f2c-a2f4-88af53f24e26)
![VirtualBox_VSDSQUADRON_30_05_2025_16_03_18](https://github.com/user-attachments/assets/3b960de4-269b-44c5-8d14-24b4e5eaa54e)
## Lab Task:
![VirtualBox_VSDSQUADRON_30_05_2025_15_16_55](https://github.com/user-attachments/assets/04213300-0a22-4e6d-b2e5-bf6d75fd4810)
![VirtualBox_VSDSQUADRON_30_05_2025_15_18_15](https://github.com/user-attachments/assets/48fe88d7-1ed7-45bf-9e9c-885db3d90afc)
![VirtualBox_VSDSQUADRON_30_05_2025_15_24_12](https://github.com/user-attachments/assets/21088b35-75a4-46db-a294-5cdbad4c8e8d)
![VirtualBox_VSDSQUADRON_30_05_2025_15_24_50](https://github.com/user-attachments/assets/92a14090-a4e1-4ba6-844b-2f8ed35dc35c)
![VirtualBox_VSDSQUADRON_30_05_2025_15_27_28](https://github.com/user-attachments/assets/bfe95c3c-5293-4bd9-bf52-22a9e0854c62)
![VirtualBox_VSDSQUADRON_30_05_2025_15_29_19](https://github.com/user-attachments/assets/6bca3f16-068b-4a60-9c75-3f4b3af05f7b)
![VirtualBox_VSDSQUADRON_30_05_2025_15_30_01](https://github.com/user-attachments/assets/9284b100-70d3-4343-a7f1-11366163fdb1)
![VirtualBox_VSDSQUADRON_30_05_2025_15_30_21](https://github.com/user-attachments/assets/a4c5b599-16f7-47c7-80cd-600404b5bf23)

# 📌 Key Learnings:
- How synthesis tools detect and optimize redundant logic

- Impact of coding styles on gate-level output

- Exploring netlists for optimization evidence

- Differences in netlist for same logic written in various styles

## 🗓️ Day 4 – Gate-Level Simulation (GLS) and SDC Constraints
# 🔰 Objective:
To perform gate-level simulations using synthesized netlists, apply constraints, and understand timing-aware synthesis using .sdc files.

# 📚 Topics Covered:
- What is Gate-Level Simulation (GLS) and when to use it

- Generating SDF files for timing-annotated simulation

- Writing basic SDC (Synopsys Design Constraints) files

- Using clock constraints for timing-aware synthesis

# 🛠️ Tools Used:
- Yosys

- Icarus Verilog

- GTKWave

## Screenshots:
![Screenshot (219)](https://github.com/user-attachments/assets/5f30f7e4-7325-46d5-993c-670a0dcc09c5)
![Screenshot (220)](https://github.com/user-attachments/assets/9753ab6d-2ba5-42ab-b892-590b1bd47da3)
![Screenshot (221)](https://github.com/user-attachments/assets/2a1c057e-f21b-48ef-8270-b40d7d18a530)

## Lab Screenshots:
![VirtualBox_VSDSQUADRON_02_06_2025_18_44_52](https://github.com/user-attachments/assets/e7be6d2c-8fae-4920-ae28-6c7d1575998f)
![VirtualBox_VSDSQUADRON_02_06_2025_18_45_43](https://github.com/user-attachments/assets/7ac7d205-1a45-4e6b-9292-ec4677f59c77)
![VirtualBox_VSDSQUADRON_02_06_2025_18_48_14](https://github.com/user-attachments/assets/66b0991c-57f0-4dc3-a4d7-7a2790313bbf)
![VirtualBox_VSDSQUADRON_02_06_2025_18_48_56](https://github.com/user-attachments/assets/5c47d280-6ac0-4886-b558-e139cf2bc11a)
![VirtualBox_VSDSQUADRON_02_06_2025_18_50_01](https://github.com/user-attachments/assets/089c73b8-a496-4ea6-86e3-44daeafa6071)
![VirtualBox_VSDSQUADRON_02_06_2025_18_50_42](https://github.com/user-attachments/assets/5ac651dc-841e-49bf-9fd4-1f9388d85c2d)
![VirtualBox_VSDSQUADRON_02_06_2025_18_54_31](https://github.com/user-attachments/assets/2865d912-a86d-4f4c-881b-6cb01b10cb0d)
![VirtualBox_VSDSQUADRON_02_06_2025_18_54_58](https://github.com/user-attachments/assets/3a98c7d8-0d99-4476-be7c-df76e1a74c9d)
![VirtualBox_VSDSQUADRON_02_06_2025_18_58_48](https://github.com/user-attachments/assets/1b0ec727-58f6-49a5-8134-d415baedca7c)
![VirtualBox_VSDSQUADRON_02_06_2025_19_06_35](https://github.com/user-attachments/assets/48262e5c-5c81-47b0-86eb-d066906be930)
![VirtualBox_VSDSQUADRON_02_06_2025_19_07_02](https://github.com/user-attachments/assets/cbf317da-778c-42b7-ad49-717afe170010)
![VirtualBox_VSDSQUADRON_02_06_2025_19_09_28](https://github.com/user-attachments/assets/d62eb929-9bcb-46bf-b407-b8b3ccc779e9)
![VirtualBox_VSDSQUADRON_02_06_2025_19_10_03](https://github.com/user-attachments/assets/cf1a0178-7202-4611-811f-aafb01ece53a)
![VirtualBox_VSDSQUADRON_02_06_2025_19_11_57](https://github.com/user-attachments/assets/afd6202c-406d-44fa-bce9-6f80d0675822)
![VirtualBox_VSDSQUADRON_02_06_2025_19_12_30](https://github.com/user-attachments/assets/e4278b23-c791-4f6b-b7ec-07b9aa2a814f)
![VirtualBox_VSDSQUADRON_02_06_2025_19_13_59](https://github.com/user-attachments/assets/8c5d0bb5-3443-4c0f-b522-948f62d571a1)

# 📌 Key Learnings:
- Difference between RTL simulation and GLS

- How to perform simulation on gate-level netlists

- Purpose of timing constraints and their role in synthesis

- Creating and using .sdc files effectively

## 🗓️ Day 5 – Design Implementation & Real-World Applications
# 🔰 Objective:
To integrate all previous concepts and complete an end-to-end ASIC frontend flow for a real-world design. Understand the practical aspects of RTL design, synthesis, constraints, and verification using the Sky130 open-source flow.

# 📚 Topics Covered:
- Full RTL-to-GLS implementation using open-source tools

- Application of SDC constraints in real designs

- RTL coding and synthesis of functional digital blocks

- Recap of best practices in ASIC design flow

- Industry relevance and career opportunities in VLSI frontend

# 🛠️ Tools Used:
- Verilog (RTL Design)

- Yosys (Synthesis)

- Icarus Verilog (Simulation)

- GTKWave (Waveform Analysis)

- Sky130 PDK












































