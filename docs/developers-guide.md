# BrightSign Mobile App Developer's Guide

## Introduction

This guide is intended for developers who will be working with the BrightSign ...

## Table of Contents


## Prerequisites

Before you begin, ensure you have the following installed:

For detailled instructions on setting up your environment for ...

## Environment Setup

### 1. Clone the Repository

If you haven't already, clone the BrightSign Client UI repository:

```bash
git clone <>
cd <>
```

### 2. Install Dependencies

Install all project dependencies 

### 3. Initial Project Setup
### 4. Install Platform-Specific Tools

## Building and Running the Application

**TL;DR**: To quickly build and run the app:

```bash
# For iOS
pnpm bs-mobile-app:run:ios

# For Android
pnpm bs-mobile-app:run:android
```

These commands will build the web assets, sync them to the native projects, and launch the app on your selected platform.

### Development Server

To start the development server for local web development:

```bash
pnpm start:bs-mobile-app
```

This will launch the application in a web browser, which is useful for rapid UI development. Note that native features like UDP will not work in browser mode.

### Building for Native Platforms

#### Building the Web Assets

Before running on a native platform, build the web assets:

```bash
pnpm build:bs-mobile-app
```

## Debugging

## Common Issues and Solutions

## Project Structure

```
<tree>
>```


## Security Considerations


## Additional Resources

