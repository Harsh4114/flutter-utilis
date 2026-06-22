# Flutter Community Contribution Rules

This repository is built for the **Flutter Community**. Developers can contribute reusable Flutter utilities, services, helpers, widgets, and common implementations that can be used across multiple Flutter projects.

Before creating a Pull Request, please follow the rules below.

---

# Pull Request Rules

## Branch Naming Convention

Create a new branch using one of the following formats:

```bash
feature/<feature-name>
fix/<issue-name>
docs/<documentation-name>
```

### Examples

```bash
feature/dio-api-client
feature/svg-asset-manager
feature/firebase-service

fix/api-error-handler

docs/update-readme
```

---

## Pull Request Title Format

Use one of the following formats:

```text
feature: Dio API Client
feature: SVG Asset Manager
fix: API Error Handling
docs: Update README
```

---

## Pull Request Description Format

Every Pull Request must contain the following information:

```text
Feature Name:
Dio API Client

Folder Name:
api

Purpose:
Reusable Dio client implementation for Flutter applications.

Dependencies:
dio

Usage:
Used to send HTTP requests and manage API communication.
```

---

## Folder Structure Rules

Each contribution must have its own folder and documentation.

### Example

```text
api/
├── README.md
├── dio_client.dart
├── interceptors/
├── services/
└── models/
```

All contributed modules should follow a similar structure.

---

## Required Documentation

Every contributed folder must contain:

```text
README.md
```

The README should explain:

* Purpose
* Dependencies
* Installation
* Usage Example
* Folder Structure

---

## Contribution Guidelines

✅ Reusable code only

✅ Follow Flutter best practices

✅ Proper folder structure

✅ Include documentation

✅ Add usage examples

✅ Keep code clean and maintainable

❌ No project-specific implementations

❌ No hardcoded business logic

❌ No unnecessary dependencies

---

## Example Contribution

### Feature Name

Dio API Client

### Folder Name

```text
api/
```

### Purpose

Provides a centralized Dio HTTP client for:

* Sending HTTP requests
* Handling API responses
* Managing interceptors
* Error handling
* API configuration

### Required Dependency

```bash
flutter pub add dio
```

### Folder Structure

```text
api/
├── dio_client.dart
├── interceptors/
├── services/
└── models/
```

---

# 1. API Dio Client

## Overview

The `api` folder contains all files related to the Dio HTTP client.

This module is responsible for:

* Sending HTTP requests to the server
* Receiving API responses
* Handling request/response interceptors
* Managing API configurations
* Centralizing network-related logic

Keeping all Dio-related code inside this folder helps maintain a clean and scalable project structure.

---

## Required Dependency

Before using the API client, install the Dio package:

```bash
flutter pub add dio
```
