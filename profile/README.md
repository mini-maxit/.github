# MAXIT

## Overview

This application is designed to facilitate the process of uploading problems, providing solutions, and testing them efficiently. It offers a streamlined interface for users to submit problems and solutions, while also providing automated testing to verify the correctness of the submitted solutions.

## Features

- **Upload Problems**: Allows users to upload programming problems with a description, input/output format, and constraints.
- **Upload Solutions**: Enables users to upload solutions for the problems in various programming languages.
- **Automated Testing**: Automatically tests the submitted solutions against predefined test cases to ensure correctness.
- **Result Feedback**: Provides detailed feedback on solution correctness, including which test cases passed or failed.

## Tech Stack

- **Frontend**: Svelte with TypeScript
- **Backend, Worker, FileStorage**: Golang
- **Broker**: RabbitMQ
- **Database**: PostgreSQL
- **Orchestration**: Docker for containerization

## Architecture
![Architecure Diagram](https://github.com/mini-maxit/.github/blob/main/assets/maxit-architecture.svg)
