# Heap Exploitation Notes

This repository contains notes and examples for understanding
glibc ptmalloc2 heap internals and several classic heap exploitation techniques.

The goal of this repository is **not a full beginner tutorial**, but rather
a structured explanation of heap concepts commonly required when studying
heap exploitation (e.g. how2heap).

The content focuses on:

- basic heap layout
- chunk structure
- bin management
- coalescing / consolidation
- exploitation primitives

## Environment

- Linux x86_64
- glibc ptmalloc2
- examples tested on Ubuntu 20.04

## Contents

1. Heap Basics
2. Fastbin Dup
3. Unsafe Unlink
4. House of Spirit
5. House of Lore

## References

- https://github.com/shellphish/how2heap
- https://sourceware.org/git/?p=glibc.git
- https://www.lazenca.net
