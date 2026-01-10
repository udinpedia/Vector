# Vector Framework

## Introduction

**Vector** is a Zygisk module that provides a consistent, Xposed-compatible API layer for module developers and users.
Written in Kotlin, it serves as the high-level interface to the underlying LSPlant C++ ART hooking framework, enabling robust Android application hooking.

> The Xposed framework enables modules to alter system and app behavior at runtime, directly in memory. Since no APK files are permanently modified, changes are easily reversed by deactivating the module and rebooting.
>
> A key advantage of this in-memory approach is its modularity: multiple independent modules can hook the same application concurrently. This avoids the complex process of manual smali patching and recompiling often required to merge traditional APK modifications.

## 🚧 Project Status: The Rewriting Phase 🚧

Vector is currently undergoing a complete rewrite from its predecessor, [LSPosed](https://github.com/JingMatrix/LSPosed).
