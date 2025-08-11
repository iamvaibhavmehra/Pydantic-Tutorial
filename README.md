# Pydantic Tutorial

Welcome to the Pydantic Tutorial! This repository contains the materials for the tutorial presented on the [DataCamp Channel](https://www.youtube.com/watch?v=aMjGAh4cQTU).

## Overview

In this tutorial you'll learn how to:
- Use **Pydantic** to define data models with type annotations.
- Leverage Pydantic's capabilities for **automatic data conversion** and **validation**.
- Utilize **Field** for adding metadata, validation rules, and aliasing.
- Implement **model validators** (`@model_validator`) and **field validators** (`@field_validator`) to enforce complex business rules.
- Work with **built-in types** like `EmailStr`, `HttpUrl`, and ensure numeric fields meet requirements.
- Build **nested** and **recursive models** for structured data handling.

The tutorial notebooks and supporting assets (such as the `pydantic_validation_flow.png` image) visually explain the validation flow in Pydantic, showing how raw input is transformed into validated data.

## Prerequisites

Before starting the tutorial, ensure you have:
- **Python 3.7+** installed.
- Basic knowledge of **Object-Oriented Programming (OOP)**.
- Familiarity with JSON and data structures.

Also, install Pydantic (version >2.0) using:
```sh
pip install pydantic pydantic[email]