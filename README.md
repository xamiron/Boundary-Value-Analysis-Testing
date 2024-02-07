# Boundary-Value-Analysis-Testing

# Introduction

Boundary value analysis (BVA) is a black-box software testing technique that focuses on testing the boundaries of input values. It is based on the assumption that most defects occur at the edges of input domains, where the software is more likely to transition from one state to another.

# BVA Process

The BVA process typically involves the following steps:

    Identify input parameters: Identify all input parameters to the software under test.
    Determine boundary values: For each input parameter, determine the minimum, maximum, and any other relevant boundary values.
    Design test cases: Design test cases that cover all boundary values and combinations of boundary values.
    Execute test cases: Execute the test cases and record the results.
    Analyze results: Analyze the results of the test cases to identify any defects.

# BVA Example

Consider a function that takes an age as input and returns whether the person is eligible to vote. The boundary values for the age input are 0 (minimum), 18 (voting age), and 150 (maximum). The following test cases would be designed to cover these boundary values:
Age	Expected Result
-1	Invalid age
0	Invalid age
17	Not eligible to vote
18	Eligible to vote
19	Eligible to vote
150	Eligible to vote

# BVA Benefits

BVA is a simple and effective technique for identifying defects. It is particularly useful for testing numerical input parameters.

# Getting Started with BVA

This repository provides a step-by-step guide to getting started with BVA, including examples and tutorials. It also includes a Python function that can be used to automate the BVA process.
