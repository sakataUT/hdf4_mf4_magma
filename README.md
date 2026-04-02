# HDF4/MF4 Magma Implementation for MQ Problems

This repository provides a Magma implementation of the proposed algorithms **HDF4** and **MF4** for solving multivariate quadratic (MQ) systems.

---

## Overview

This code implements:

* Hilbert-driven F4 variant (**HDF4**)
* Decreasing phase (**MF4**)
* Supporting routines such as LGB (Leading term prediction via Hilbert series)

The implementation is intended to reproduce the **algebraic behavior** of the proposed method described in the paper.

---

## Requirements

* Magma (tested with recent versions)
* The online Magma calculator is available at:
  https://magma.maths.usyd.edu.au/calc/

---

## Parameters

The main parameters are defined in the code:

* `p` : characteristic of the field
* `q` : extension degree (field size = p^q)
* `n` : number of variables
* `m` : number of polynomials
* `e` : parameter for HDF4

Example:

```
p := 2;
q := 8;
n := 10;
m := 11;
```

