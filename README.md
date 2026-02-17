# Rent A Car Backend (.NET – Layered Architecture)

This project is a structured backend application developed using **ASP.NET Core** following a **Layered Architecture** approach.

It represents a car rental management system backend designed with clean separation of responsibilities, business rule abstraction, and scalable architecture principles.

---

# Project Purpose

The main goal of this project is to implement a maintainable and extensible backend system for a car rental platform.

It demonstrates how to:

- Design layered backend architecture
- Apply business rule management
- Separate API, business logic, and data access layers
- Implement clean dependency injection
- Build scalable service-based backend systems

This project serves as a strong architectural foundation for real-world rental management systems.

---

# Architecture Overview

The solution is structured into multiple layers:

## WebAPI Layer
- Handles HTTP requests
- Contains Controllers
- Manages routing and middleware
- Configures dependency injection

This is the entry point of the application.

---

## Business Layer
- Contains business logic
- Implements service interfaces
- Applies validation rules
- Manages rental conditions and operational logic

This layer ensures that business rules are centralized and independent from controllers.

---

## DataAccess Layer
- Responsible for database interactions
- Implements repository pattern
- Handles CRUD operations
- Abstracts database communication

---

## Entities Layer
- Contains domain models
- Represents core system entities such as:
  - Cars
  - Brands
  - Customers
  - Rentals
  - Colors

These models define the structure of the application data.

---

## Core Layer
- Shared utilities
- Cross-cutting concerns
- Base abstractions
- Common result handling patterns

---

# Technology Stack

- ASP.NET Core
- C#
- Entity Framework Core
- SQL-based database
- Layered Architecture Pattern
- Dependency Injection

---

# Core System Capabilities

The system supports:

- Car management
- Brand management
- Customer management
- Rental operations
- Business rule validation
- Service abstraction
- Repository-based data access

Each module follows clean architectural separation.

---

# Solution Structure

