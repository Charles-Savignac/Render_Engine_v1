# Weekend Ray Tracer (C++ + Vulkan)

A minimal C++ rendering engine built using *Ray Tracing in One Weekend* as a base, with **Vulkan** used for real-time scene visualization.

---

## Preview

![Render Preview](docs/images/preview.png)

---

## Features

- Disney Principled material model with PDF support
- CPU-based path tracing
- Multiple Importance Sampling (MIS)
- Next Event Estimation (NEE)
- Basic camera system
- Anti-aliasing (stochastic sampling)
- Vulkan-based rendering pipeline for display

---

## More Examples

| Scene 1 | Scene 2 |
|--------|--------|
| ![Scene 1](docs/images/scene1.png) | ![Scene 2](docs/images/scene2.png) |

---

## Requirements

- C++17 compatible compiler (`g++`, `clang++`, or MSVC)
- Vulkan SDK (**1.4.341 recommended**)
- GPU with Vulkan support
- CMake (optional but recommended)

---

## Setup & Execution

### Prerequisites

First, install a compatible version of the Vulkan API on your machine.  
This project was developed using **Vulkan SDK 1.4.341**.

During installation, it is recommended to include the **GLM** library to simplify integration and development.

---

### Getting the Project

Clone or download the engine from the GitLab repository.

---

### Generate Build Files

Once the project is retrieved, generate the configuration files using CMake:

```bash
cmake -S . -B build