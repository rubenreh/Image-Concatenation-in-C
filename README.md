# UNIX Process Management

This project is a project focusing on UNIX process creation, inter-process communication, and signal handling in C. The objective is to deepen understanding of how processes are managed and interact in a UNIX environment, specifically using `fork()`, `exec()`, `pipe()`, and signal-related system calls.

## Overview

The lab involves writing a C program that:
- Creates multiple child processes using `fork()`.
- Uses pipes to communicate between the parent and child processes.
- Employs `exec()` to replace a process's memory space with a new program.
- Handles UNIX signals to control the execution of processes.

## Key Concepts

- **Process Creation**: Using `fork()` to create child processes from a parent.
- **Inter-process Communication**: Utilizing `pipe()` to allow data flow between parent and children.
- **Program Replacement**: Implementing `exec()` to execute different binaries in forked processes.
- **Signal Handling**: Capturing and responding to signals like `SIGINT`, `SIGUSR1`, and `SIGUSR2`.

## Features

- Robust signal handler for graceful termination and debugging.
- Flexible process control through signal sending and piping.
- Clear separation of concerns between parent and child logic.
- Error handling for all system calls.

## File Descriptions

- `lab3.c`: Main source file implementing process creation and communication.
- `README.md`: Project overview and documentation.
- `lab3_manual.pdf`: Official lab instructions outlining the problem statement and goals.

## Educational Goals

By completing this project, students will:
- Learn how to manage concurrent processes.
- Understand the lifecycle of UNIX processes.
- Gain practical experience in low-level I/O and signal handling.
- Develop debugging skills for multi-process applications.
