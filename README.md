# Advent of Code Python Template

This template provides a base repository for solving the [Advent of Code](https://adventofcode.com/) puzzles in Python.
It provides auto-formatting, linting, and testing.
Furthermore, it contains GitHub Actions to automatically run the tests and linting on every push and pull request, as well as a template for the README including badges about the progress.

## Usage
### Setup
1. Create a new repository from this template
2. Clone the repository
3. Install the dependencies with 
    ```shell
    poetry install
    ```
4. Install pre-commit
    ```shell
    poetry run pre-commit install
    ```
5. Run the tests with 
    ```shell
    poetry run pytest
    ```
6. Run the linter with 
    ```shell
    poetry run flake8
    ```
7. Run the formatter with 
    ```shell
    poetry run black .
    ```
8. Solve the puzzles
9. Commit and push your changes
10. Celebrate 🎉
11. Repeat
12. Profit
13. (Optional) Add your own badges to the README
14. (Optional) Add your own GitHub Actions to the repository
15. (Optional) Add your own linter rules to the repository
16. (Optional) Add your own formatter rules to the repository

# Advent of Code 20XX
## Badges
[![Tests](https://github.com/S3-D1/advent-of-code-python-template/actions/workflows/test.yml/badge.svg)](https://github.com/S3-D1/advent-of-code-python-template/actions/workflows/test.yml)

Tests
Coverage
Linting

## Progress
| Day | Part 1                                                                                                                                                                                                 | Part 2                                                                                                                                                                                                 |
|-----|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1   | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day1_1.svg"></a>  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day1_2.svg"></a>  |
| 2   | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day2_1.svg"></a>  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day2_2.svg"></a>  |
| 3   | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day3_1.svg"></a>  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day3_2.svg"></a>  |
| 4   | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day4_1.svg"></a>  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day4_2.svg"></a>  |
| 5   | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day5_1.svg"></a>  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day5_2.svg"></a>  |
| 6   | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day6_1.svg"></a>  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day6_2.svg"></a>  |
| 7   | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day7_1.svg"></a>  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day7_2.svg"></a>  |
| 8   | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day8_1.svg"></a>  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day8_2.svg"></a>  |
| 9   | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day9_1.svg"></a>  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day9_2.svg"></a>  |
| 10  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day10_1.svg"></a> | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day10_2.svg"></a> |
| 11  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day11_1.svg"></a> | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day11_2.svg"></a> |
| 12  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day12_1.svg"></a> | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day12_2.svg"></a> |
| 13  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day13_1.svg"></a> | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day13_2.svg"></a> |
| 14  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day14_1.svg"></a> | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day14_2.svg"></a> |
| 15  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day15_1.svg"></a> | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day15_2.svg"></a> |
| 16  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day16_1.svg"></a> | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day16_2.svg"></a> |
| 17  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day17_1.svg"></a> | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day17_2.svg"></a> |
| 18  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day18_1.svg"></a> | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day18_2.svg"></a> |
| 19  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day19_1.svg"></a> | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day19_2.svg"></a> |
| 20  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day20_1.svg"></a> | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day20_2.svg"></a> |
| 21  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day21_1.svg"></a> | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day21_2.svg"></a> |
| 22  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day22_1.svg"></a> | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day22_2.svg"></a> |
| 23  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day23_1.svg"></a> | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day23_2.svg"></a> |
| 24  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day24_1.svg"></a> | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day24_2.svg"></a> |
| 25  | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day25_1.svg"></a> | <a href="https://github.com/S3-D1/advent-of-code-python-template/actions"><img alt="Actions Status" src="https://github.com/S3-D1/advent-of-code-python-template/workflows/Solutions/day25_2.svg"></a> |