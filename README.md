# Purna Kalyan Shakya

Senior Mobile Application Developer specializing in Flutter.

I build reusable libraries and internal tooling with a focus on application architecture, performance, native integration, and real-time systems. Most production work is in private repositories, while the projects here represent the engineering problems I've solved outside of client work.

## Architecture

Tools and libraries that help keep Flutter projects consistent and maintainable.

### clean_feature_arch

CLI for generating feature-based Flutter projects following my Feature First Clean Architecture standard.

- Project scaffolding
- Static analysis
- Architecture validation

### Flutter Architecture Standard

Documentation describing the architectural rules, dependency boundaries, and project structure used across my Flutter projects.

## Performance

Libraries focused on reducing unnecessary work and keeping UI rendering responsive.

### isolate_runner_mixin

Utilities for executing CPU-intensive tasks in background isolates while keeping the UI thread responsive.

### scroll_texts_widget

A scrolling text widget designed for production use. It renders text directly to the canvas instead of rebuilding widget trees, allowing performance to remain consistent even with long strings.

### animated_marker

Animated map markers for Flutter applications with smooth position and scale interpolation.

## Native Integration

Libraries that bridge Flutter with lower-level platform capabilities.

### biometric_secure_vault

Secure credential storage protected by device biometrics.

### ffr_crypto

Experimental Flutter package using Rust through Dart FFI for cryptographic operations. Built as a learning project while exploring Rust and FFI.

## Other Projects

### nbody_sim_core

A framework-independent N-body simulation engine written in Dart.

### nbody_sim_flutter

Flutter visualization built on top of `nbody_sim_core`. The same engine powers my portfolio website.

## Links

- Portfolio: https://shakyapurna.com.np
- Pub.dev: https://pub.dev/publishers/shakyapurna.com.np/packages