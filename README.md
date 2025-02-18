# SymJul

Symbolic Mathematics in Julia

# Introduction

There are many Computer Algebra Systems (CAS) software such as:

- Mathematica (not free)
- Maple (not free)
- SymEngine
- SageMath (free)
- Sympy (free)

The first two in the list are not free but are the most powerful. However, they suffer from syntax that is not user friendly for highly complex mathematics. SymEngine is free & opensource but written in C++, making it difficult for a large variety of users to contribute, along with it having limited capabilities at the moment. SageMath is free & opensource but a collection of libraries with python scripting, making it difficult to know how to optimize. Sympy is free and & opensource. Sympy is probably the most straightforward of the opensource softwares and has the most capabilities in terms of algebraic manipulation. However, for very complex mathematics, it suffers in speed. 

`SymJul` is written in `Julia` and wraps around `SymbolicUtils.jl`. It has the capabilities of being as fast as C++ while being easily modified by users. 

# Requirements

- `Julia`
- `SymbolicUtils.jl`

