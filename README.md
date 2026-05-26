# Entropy as a Utility Function in Econophysics

## Overview

This project explores how concepts from statistical physics can be applied to economics and financial decision-making. Specifically, it studies entropy as a utility function for resource allocation problems.

The project starts from the combinatorial definition of entropy, derives an entropy-based utility function, and then applies it to a binary allocation model. Finally, the analytical results are compared with numerical simulations in Python.

## Motivation

Entropy is commonly used in statistical physics to measure the number of possible configurations of a system. In an economic context, this idea can be interpreted as a measure of diversity, dispersion or flexibility in the allocation of resources.

This project investigates how entropy can be used as a utility function to model the value of diversified allocations and to penalize excessive concentration in a single category.

## Objectives

The main objectives of this project are:

- Derive an entropy-based utility function from combinatorial principles.
- Analyze the binary allocation case.
- Show that normalized entropy is maximized when the allocation is balanced.
- Formulate a constrained optimization problem using Lagrange multipliers.
- Solve the resulting nonlinear equation numerically.
- Interpret the results from an economic and decision-making perspective.

## Mathematical Framework

The number of microstates for distributing N elements among K categories is given by:

```math
\Omega = \frac{N!}{N_1!N_2!\cdots N_K!}
