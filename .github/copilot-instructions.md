# Flutter Utils Repository - Copilot Instructions

## Repository Purpose

This repository contains reusable Flutter utilities, services, helpers, widgets, architectures, and implementations contributed by the Flutter community.

The goal is to provide production-ready code that can be reused across multiple Flutter projects.

Contributors should focus on scalability, maintainability, clean architecture, and developer experience.

---

# Technology Requirements

Always generate code compatible with:

* Latest stable Flutter SDK
* Latest stable Dart SDK
* Dart null safety
* Modern Flutter APIs

Avoid deprecated APIs and outdated patterns.

---

# Code Quality Rules

All generated code must:

✅ Follow Flutter and Dart best practices

✅ Be reusable across multiple projects

✅ Be production-ready

✅ Support null safety

✅ Be properly documented

✅ Be easy to maintain

✅ Follow SOLID principles where applicable

✅ Prefer composition over inheritance

✅ Use meaningful naming conventions

✅ Handle errors gracefully

✅ Include usage examples when applicable

---

# Security Requirements

Never generate or accept code that contains:

❌ Malicious code

❌ Data theft logic

❌ Hidden network requests

❌ Cryptocurrency miners

❌ Obfuscated code

❌ Tracking without user consent

❌ Hardcoded credentials

❌ API keys

❌ Secrets

❌ Tokens

❌ Passwords

❌ Private URLs

❌ Unsafe platform code

Review all pull requests for potential security issues.

Reject any contribution that appears suspicious or harmful.

---

# Dependency Rules

Dependencies must:

* Have a clear purpose
* Be actively maintained
* Be widely adopted when possible

Avoid:

❌ Unnecessary dependencies

❌ Duplicate functionality

❌ Heavy packages for simple tasks

Every dependency should be documented inside README.md.

---

# Reusability Rules

Contributions must be generic.

Allowed:

✅ Dio API Client

✅ Firebase Services

✅ Local Storage Helpers

✅ Network Utilities

✅ Responsive Widgets

✅ Form Validators

✅ Theme Helpers

✅ Asset Managers

✅ State Management Utilities

Not Allowed:

❌ Project-specific code

❌ Business-specific logic

❌ Company-specific implementations

❌ Hardcoded URLs

❌ Hardcoded environments

❌ Application-specific workflows

---

# Folder Structure Rules

Every contribution must be contained inside its own folder.

Example:

api/
├── README.md
├── dio_client.dart
├── interceptors/
├── services/
└── models/

Each module must remain isolated and self-contained.

---

# Required Documentation

Every contributed folder must contain:

README.md

README.md should include:

1. Purpose
2. Features
3. Dependencies
4. Installation
5. Usage Example
6. Folder Structure
7. Notes
8. Limitations (if any)

Pull requests without documentation should be rejected.

---

# Flutter Code Standards

Prefer:

* const constructors
* final variables
* extension methods where appropriate
* sealed classes when applicable
* pattern matching where useful
* immutable models
* clear separation of concerns

Avoid:

* Global mutable state
* Excessive singleton usage
* Deep widget nesting
* Business logic inside UI
* Massive files
* Duplicate code

---

# Networking Standards

For networking modules:

Required:

✅ Centralized API client

✅ Configurable base URL

✅ Request interceptors

✅ Response interceptors

✅ Error handling

✅ Timeout configuration

✅ Logging support

Never:

❌ Hardcode production URLs

❌ Hardcode authorization tokens

❌ Store secrets in source code

---

# Pull Request Validation Rules

Before approving a pull request, verify:

* Folder structure is correct
* README exists
* Code is reusable
* No malicious code exists
* No hardcoded secrets exist
* Documentation is complete
* Example usage is provided
* Code follows Flutter best practices

---

# Branch Naming Convention

Allowed:

feature/<feature-name>

fix/<issue-name>

docs/<documentation-name>

Examples:

feature/dio-api-client

feature/firebase-service

fix/network-timeout

docs/update-readme

---

# Pull Request Title Format

Use one of:

feature: Feature Name

fix: Fix Description

docs: Documentation Update

Examples:

feature: Dio API Client

feature: Firebase Service

fix: API Error Handling

docs: Update README

---

# Pull Request Description Format

Every Pull Request must use the following structure:

Feature Name: <feature name>

Folder Name: <folder name>

Purpose: <why this contribution exists>

Dependencies: <dependency list>

Flutter Version Tested: <flutter version>

Dart Version Tested: <dart version>

Usage: <short usage explanation>

Documentation:
README.md included

Security Check:
No secrets, tokens, credentials, or malicious code included.

Checklist:

* [ ] Reusable implementation
* [ ] Documentation added
* [ ] Usage examples included
* [ ] No hardcoded business logic
* [ ] No malicious code
* [ ] No secrets or credentials
* [ ] Flutter best practices followed

---

# Review Behavior

When reviewing pull requests:

1. Prioritize code quality.
2. Verify reusability.
3. Verify maintainability.
4. Check documentation quality.
5. Check security concerns.
6. Suggest improvements politely.
7. Reject code that is project-specific.
8. Reject code containing secrets or malicious behavior.
9. Encourage community-friendly contributions.

The repository should remain a trusted collection of reusable Flutter utilities for the entire Flutter community.
