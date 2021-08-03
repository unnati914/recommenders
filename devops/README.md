# CI Pipeline (Refactored)

This folder contains refactored CI pipelines with the following motivations:
    1. Boost mantainability by minimizing the .yml duplicates with a matrix strategy
        - One pipeline can be ran on multiple environment setups
    2. Simplify pipeline structure by using more templates to isolate each common build step
    3. Accelerate build process by parallelizing the workflows into multiple machines.