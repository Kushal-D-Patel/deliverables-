# Release Notes for Version 1.0

## Summary
Version 1.0 includes the implementation of two core features: **User Registration** and **User Login**, ensuring basic user account management for the application. Additionally, a post-release hotfix was applied to correct a validation bug in the User Registration feature.

## Features

### 1. User Registration
- **File**: `UserRegistration.java`
- **Description**: Implements functionality to validate usernames (5–15 characters) and passwords (minimum 8 characters).
- **Outcome**: Users can successfully register with valid credentials.

### 2. User Login
- **File**: `UserLogin.java`
- **Description**: Implements functionality to verify login credentials against a predefined username-password map.
- **Outcome**: Users can successfully log in with correct credentials.

## Bug Fixes

### Hotfix 1.0.1
- **Branch**: `hotfix/1.0.1`
- **File**: `UserRegistration.java`
- **Description**: Fixed a simulated bug in the User Registration feature.
- **Outcome**: The username validation logic now correctly enforces a length of 5–15 characters.
