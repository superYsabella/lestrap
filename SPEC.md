# Lestrap - Custom FFLAG Injector for Android

## Project Overview
- **Project Name**: Lestrap
- **Type**: Android Application with Xposed Module
- **Core Functionality**: Allows Android users to add custom FFLAGS (feature flags) to Roblox without root access by using app cloning (Parallel Space/Island) and Xposed framework.

## Technology Stack & Choices
- **Language**: Kotlin 1.9.x
- **Min SDK**: 24 (Android 7.0)
- **Target SDK**: 34 (Android 14)
- **Architecture**: MVVM with Clean Architecture
- **UI Framework**: Jetpack Compose with Material Design 3
- **Dependencies**:
  - AndroidX Core KTX
  - Jetpack Compose (BOM)
  - Room Database (for storing FFLAGS)
  - Hilt (Dependency Injection)
  - Coroutines + Flow
  - Xposed API

## Feature List
1. **App Clone Detection** - Detect if Parallel Space, Island, or similar cloning app is installed
2. **FFLAG Manager** - CRUD operations for custom FFLAGS (add, edit, delete, toggle)
3. **FFLAG Presets** - Pre-built FFLAG configurations for common modifications
4. **Roblox Setup Guide** - Step-by-step guide to install and clone Roblox
5. **Xposed Module** - Module to inject FFLAGS into Roblox at runtime
6. **Import/Export** - Backup and restore FFLAG configurations

## UI/UX Design Direction
- **Visual Style**: Material Design 3 with Roblox-inspired colors (red accent)
- **Color Scheme**: Primary red (#E2231A), secondary dark gray, white backgrounds
- **Layout**: Tab-based navigation (FFLAGs, Presets, Settings, Help)
- **Typography**: Clean, readable with Roblox-style headers