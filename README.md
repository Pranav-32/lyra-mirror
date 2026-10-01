# Lyra - A Minecraft Bedrock Client (Unofficial Mirror)

This repository functions as an unofficial, unmaintained mirror of **Lyra**, a custom utility client designed for Minecraft Bedrock Edition. Development on the official project has been discontinued. This source code is hosted strictly for historical preservation, educational analysis, and community archiving.

> ⚠️ **Disclaimer:** This project is discontinued and provided AS-IS. No future official updates, bug fixes, or feature additions will be provided by the original development team. This project may also miss some files or contain broken functionalities; therefore, the creators and contributors accept no liability for the code or its execution.

---

## Features

* **Performance Optimizations:** Enhanced rendering tweaks to maximize frames-per-second (FPS) and reduce input latency.
* **Custom UI/UX:** A streamlined, highly customizable user interface tailored for Bedrock players.
* **Module Framework:** An extensible architecture supporting custom gameplay utilities, HUD elements, and visual modifications.
* **Enhanced Input Handling:** Tweaked keystroke and mouse inputs designed for competitive responsiveness.

---

## Build & Compilation

To compile Lyra from source, ensure you have the required build environment set up for Minecraft Bedrock development.

### Prerequisites
* Windows 10/11 (Minecraft Bedrock platform standard)
* Visual Studio (2022 or newer recommended) with the **Desktop development with C++** workload installed
* CMake (3.15 or newer recommended)
* Windows SDK (matching your target Minecraft version architecture)

### Step-by-Step Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Pranav-32/lyra-mirror.git
   cd lyra-mirror
   ```

2. **Configure the Project:**
   Open your terminal in the project root directory and run the configuration command to generate the build files for the `x64` architecture:
   ```bash
   cmake -B build -A x64
   ```

3. **Build the Solution:**
   Compile the project using CMake by specifying your target build configuration:
   
   For production builds:
   ```bash
   cmake --build build --config Release
   ```
   For debugging/development builds:
   ```bash
   cmake --build build --config Debug
   ```

---

## Repository Structure

```text
├── src/            # Core C++ source files and client logic
├── lib/include     # Third-party stand-alone libraries
├── _deps/          # Third-party dependency libraries
```

---

## Contributing & Forks

Because this project is discontinued, pull requests to this specific mirror repository will not be reviewed or merged into an official branch. However, you are entirely welcome to **fork this repository** to patch bugs, port it to newer Minecraft versions, or build your own client variations on top of the Lyra framework.

---

## License & Attribution

This project is open-source and distributed under the terms of the project's root `LICENSE`. 

* Copyright (c) 2024 **Lyra-team** & **Pranav Sanjeevi Kumari** (Core client framework, UI systems, and rendering optimization)
* Copyright (c) 2026 **Pranav Sanjeevi Kumari** (CMake build migration & modern repository archival structural updates)

All credit for the foundational codebase belongs to the original creators and contributors, which includes my own core development contributions to the official client during its 2024 lifecycle.