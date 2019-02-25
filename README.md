# **Welcome to the OMASE (Optimization, Modeling, Analysis and Space Exploration) Workshop page!!**

## Co-located with [CGO'19](http://cgo.org/cgo2019/)

## Purpose and Scope of OMASE

Current hardware and software trends are proving to be extremely complex and heterogeneous. This poses a serious challenge for developers and scientists when implementing their application code for a wide variety of architectures, network interconnects, deep memory hierarchies, accelerators, stacked run-time layers, among many other features.

This workshop aims to highlight research that automates the derivation of architecture-specific code, thus simplifying the porting, adaptation, and deployment process of applications. Such research encompasses techniques that systematically explore search spaces describing possible optimization strategies to derive the best target implementation. This includes architecture-specific transformations and optimization algorithms, performance and energy modeling, and automatic and hybrid exploration of the search spaces of strategies. 

We are interested in research that spans one or more performance factors such as the synergistic behavior of compile-time and runtime optimizations, application to architecture mapping, and the characterization of input-sensitive programs. The goal of the proposed workshop is to bring together academics, researchers, application scientists and programmers to share their preliminary research in all aspects of tuning and auto-tuning systems. 

---
## Program
```markdown
8:30am
Welcome 
Mary Hall (University of Utah)

8:45am - 9:30am
Opening Talk
Prasanna Balaprakash (Argonne National Laboratory)
Title: Machine-Learning-Based-Search for Automatic Performance Tuning
Abstract:
Empirical performance optimization of computer codes using autotuners has received significant attention in recent years. Given the increased complexity of computer architectures and scientific codes, evaluating all possible code variants is prohibitively expensive for all but the simplest kernels. One way for autotuners to overcome this hurdle is through use of a search algorithm that finds high-performing code variants while examining relatively few variants. In this talk we will discuss the search problem in autotuning from a mathematical optimization perspective. Then, we will describe machine-learning-based search method for autotuning that consists of sampling a small number of input parameter configurations and progressively fitting a surrogate model over the input-output space until exhausting the user-defined maximum number of evaluations.


9:30am - 10:00am
Tomer Morad (Concertio)
Title: Full-stack automatic optimization

10:00am - 10:30am
**Abhishek Patwardhan** and Ramakrishna Upadrasta (Indian Institute of Technology, Hyderabad, India)
Title: Polyhedral Model Guided Automatic GPU Cache Exploitation Framework
Abstract:
We propose a compiler driven method by which parallel computations can be accelerated on GPUs by exploiting the various special varieties of caches (texture, surface and constant for NVIDIA GPUs). 
We show that our method obtains superior performance for certain class of computations when compared with earlier methods that use on-chip shared memory. 
We provide an end-to-end solution by developing a *fully automatic* sound, static framework within a state-of-art source-to-source Polyhedral compiler (PPCG) to exploit these varieties of GPU caches. 
Using Polyhedral model formalism, we reason about the profitability of using each of the particular variety of GPU caches. 
We evaluate our implementation on kernels from PolyBench/C benchmark and report up *to 1.5x* speedups over the existing (default) memory mapping strategy used by PPCG compiler. 
We also consider five sample real-world representative kernels: PageRank, DNN layers (RNN and LSTM), various solvers (Poisson and DWE-FDTD stencil) and show that using the special GPU caches in these programs 
results in up to 2.6x speedup over a standard shared memory based implementation. 
With these use cases, we show the general purpose computing usage of these special GPU caches that were originally designed for image processing applications. With increasing interest in mapping general purpose algorithms on GPUs, we believe that our contribution is towards automatic exploitation of GPU cache/memory hierarchy.

10:30am - 11:00am
**Johannes Doerfert**, Brian Homerding and Hal Finkel (Argonne National Laboratory)
Title: Performance Exploration Through Optimistic Static Program Annotations

11:00am - 11:30am
**Mahdi Javanmard** and Robert Harrison (Stony Brook University)
Title: Dependence Programming and Tiling for Irregular Numerical Applications

11:30am - 12:00m
Riyadh Baghdadi (MIT CSAIL)
Title: A Platform for Exploring Machine Learning Based AutoScheduling
Abstract:
Building a platform for exploring machine learning based auto-scheduling requires many steps. The first step is to build a compiler that has an API that exposes scheduling decisions. In this presentation, we present [Tiramisu](http://tiramisu-compiler.org/). A polyhedral compiler that exposes an API allowing users to control scheduling decisions.  Tiramisu provides a simple C++ API for expressing algorithms (Tiramisu expressions) and controlling scheduling decisions. Tiramisu can be used in areas such as linear and tensor algebra, deep learning, image processing, stencil computations and machine learning.  Currently it targets multicore X86 CPUs, Nvidia GPUs, Xilinx FPGAs (Vivado HLS) and distributed machines (using MPI).

```
---

## Organizers

```markdown
- Mary Hall (University of Utah)
- Martin Kong (Brookhaven National Laboratory)
- Tobias Grosser (ETH Zurich)
```

## Workshop Topics

Topics amenable to our workshop include, but are not limited to, the following:

```markdown
- Compiler auto-tuning frameworks
- Application characterization
- Program optimization for performance and/or power constraints 
- Model-driven analysis and optimizations
- Program generators
- Space exploration techniques
- Domain specific languages
- Adaptive run-times and frameworks

```

## Program Committee

```markdown
• Hal Finkel (Argonne National Laboratory)
• Michel Steuwer (University of Glasgow)
• Daniele Spampinato (Carnegie Mellon University)
• Florina Ciorba (Univ. of Basel, Switzerland) 
• Shoaib Kamil (Adobe)
• Michael Kruse (Argonne National Laboratory) 
• Tze Meng (Carnegie Mellon University)
• Franz Franchetti (Carnegie Mellon University)
• Richard Veras (Louisiana State University)
• Emmanuelle Saillard (INRIA)
```


## Deadlines

- OMASE website live: October 17, 2018
- Call for papers: October 19, 2018
- ~~Abstract registration: December 21, 2018~~
- ~~Abstract registration (NEW): January 4, 2019~~
- **Abstract registration (NEW): January 13, 2019**
- ~~Paper submission deadline: December 28, 2018~~
- ~~Paper submission deadline (NEW): January 8, 2019~~
- **Paper submission deadline (NEW): January 15, 2019**
- ~~Notifications: January 11, 2019~~
- Notifications (NEW): January 23, 2019
- Workshop date: February 17, 2019

## Submission Instructions

Abstracts and papers should  be submitted via the EasyChair conference system:

[OMASE Submission Link](https://easychair.org/conferences/?conf=omase19)

OMASE will accept full papers (8 pages) and short/position papers (5 pages).
Please use version 1.54 or above of the following template to prepare your manuscript:

[Sigplan Template](https://www.acm.org/publications/proceedings-template)

with 10pt font. Make sure to use the sigplan subformat. Visit the 
[SIGPLAN Author Resources page](http://sigplan.org/Resources/Author/) 
for further information on SIGPLAN manuscript formatting.

Papers must be submitted in PDF format (readable by Adobe Acrobat
Reader 5.0 and higher) and formatted for 8.5" x 11" (U.S. Letter).

Papers should present original research and should provide sufficient
background material to make them accessible to the broader community. It
should not be submitted in parallel to any other conference or journal.

Acceptance of a paper commits at least one of the authors to register at
CGO'19 and present the work.

## Questions

For more information please write us at omase.workshop@gmail.com
