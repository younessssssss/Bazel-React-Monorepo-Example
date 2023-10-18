# Bazel React Monorepo Example

Welcome to the Bazel React Monorepo Example! This repository demonstrates how to use Bazel for orchestrating and building a monorepo containing web development projects, with a focus on React applications.

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Build and Run](#build-and-run)
- [Contributing](#contributing)
- [License](#license)

## Introduction

As a software engineer, I've often encountered challenges when working with web development frameworks due to the layers of abstraction they introduce. Understanding how the source code gets transformed into an executable is essential for effective software engineering. This repository aims to address this by showcasing the use of Bazel, a powerful build tool, for orchestrating multiple web development projects within a monorepository.

For a more detailed explanation and insights into the concepts used in this project, please refer to our accompanying blog post [here](https://younessssssss.github.io/2023/09/22/getting-started-with-bazel-for-web-developper.html).

## Project Structure

The project structure follows the principles discussed in the accompanying blog post. Here's a brief overview of the key directories:

## Getting Started

To use this example and experiment with Bazel in your web development projects, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/younessssssss/Bazel-React-Monorepo-Example.git
   cd bazel-react-monorepo-example
   ```

## Build and Run

run `bazel run -- @pnpm//:pnpm --dir $PWD install --lockfile-only`

then

run `bazel build //packages/my-app:build`

## Contributing
Contributing
Contributions are welcome! If you have improvements or new features to add to this example, please submit pull requests or issues. 

## License
This project is licensed under the MIT License - see the LICENSE file for details.