# n-Puzzle Solver

The n-Puzzle Solver is a Python project that uses the A* search algorithm to find the optimal solution to the n-Puzzle problem, a classic sliding puzzle game. The goal of this project is to solve n-Puzzle boards of various sizes (e.g., 8-puzzle, 15-puzzle) using different heuristic functions and demonstrate their effectiveness.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Heuristic Functions](#heuristic-functions)

## Introduction

The n-Puzzle problem is a well-known puzzle game where a player is presented with a board containing numbered tiles. The objective is to rearrange the tiles from an initial state to a goal state by sliding them into the empty space. This project provides a Python implementation of an n-Puzzle solver using the A* search algorithm, capable of solving puzzles of various sizes.

## Features

- Solves n-Puzzle boards using the A* search algorithm.
- Supports multiple heuristic functions, including:
  - Misplaced tiles heuristic (`h1`)
  - Manhattan distance heuristic (`h2`)
  - Disjoint pattern heuristic (`h3`)
- Verifies the solvability of the puzzle.
- Generates optimal solutions and visualizes the path.

## Heuristic Functions

### Misplaced Tiles Heuristic (`h1`)

This heuristic counts the number of misplaced tiles in the current state compared to the goal state.

### Manhattan Distance Heuristic (`h2`)

The Manhattan distance heuristic calculates the sum of the absolute differences between the current position of each tile and its goal position in a solved configuration.

### Disjoint Pattern Heuristic (`h3`)

This heuristic divides the puzzle into two patterns and calculates the sum of misplaced tiles in each pattern.
