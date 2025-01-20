# FizzBuzz

A simple TypeScript implementation of the classic FizzBuzz problem.

## Table of Contents
- [FizzBuzz](#fizzbuzz)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Features](#features)
  - [Usage](#usage)
  - [How to Run](#how-to-run)
  - [Example Output](#example-output)
  - [Contributing](#contributing)
  - [License](#license)

## Overview
This repository contains a TypeScript implementation of the FizzBuzz challenge. The program takes a number `n` as input and prints numbers from `1` to `n`, with the following conditions:

- Print `Fizz` for numbers divisible by 3.
- Print `Buzz` for numbers divisible by 5.
- Print `FizzBuzz` for numbers divisible by both 3 and 5.
- Print the number itself if it is not divisible by 3 or 5.

## Features
- Written in TypeScript for type safety and modern JavaScript features.
- Simple and easy-to-understand logic.
- Console-based output.

## Usage
Clone this repository:
```bash
git clone https://github.com/rulshrm/FizzBuzz.git
```

Navigate to the project directory:
```bash
cd FizzBuzz
```

## How to Run
1. Make sure you have [Node.js](https://nodejs.org/) and [TypeScript](https://www.typescriptlang.org/) installed on your system.

2. Compile and run the script using `ts-node`:
  ```bash
  npm install -g ts-node typescript tsx
  tsx fizzBuzz.tsx
  ```

## Example Output
For `n = 15`, the output will be:
```
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
```

## Contributing
If you would like to contribute to this project, feel free to submit a pull request or open an issue on [GitHub](https://github.com/rulshrm/FizzBuzz).

## License
This project is licensed under the MIT License. See the [LICENSE](/LICENSE) file for details.
