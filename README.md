# Java-Hash-Table-Analysis
Hash Table Benchmarking Suite
  This project is a Java-based tool designed to analyze and compare the efficiency of different collision resolution strategies in Hash Tables. It focuses on how these strategies perform under high-density scenarios.  
Features
  Custom Implementation: Includes from-scratch implementations of Robin Hood Hashing and Linear Probing.  
Stress Testing: Evaluates data structure performance under a 0.9 load factor.  
Precise Measurement: Uses System.nanoTime() and volatile sinks to ensure timing accuracy by preventing JIT (Just-In-Time) compiler optimizations from skipping dead code.  
Technical Goal
  The main objective is to measure:
    Average and Maximum Displacement: Tracking how far elements move from their original hash index.  
    Probe Lengths: Analyzing the number of lookups required to find or insert an element.  
