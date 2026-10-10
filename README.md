
# Nucleus Engine
A modern, fast game engine written in C++.

# 🚀 Getting Started

# Installation guide

## Option 1: Prebuilt Binaries (Recommended)
There are currently no releases.

## Option 2: Build from Source (Not recommended)

### List of requirements
```
C++17       or newer
CMake       3.20++
GLFW 
OpenGL  
Glad
Freetype2
```

### Installing prerequisites & compiling

<details>
<summary><b>🐧 Linux</b></summary>

<br>

> <details>
> <summary><b>Pacman</b> — Arch Linux</summary>
>
> To make sure you have a smooth experience compiling everything you first need to download the prerequisites using this command:
> ```bash
> sudo pacman -Syu --needed base-devel gcc cmake ninja glfw freetype2 mesa
> ```
> After all the necessary packages are installed you can simply run from the root project directory
> ```bash
> chmod +x build.sh
> ./build.sh
> ```
>
>
> </details>
>
> <details>
> <summary><b>APT</b> — Debian / Ubuntu</summary>
> To be implemented.
</details>

</details>

<details>
<summary><b>🪟 Windows</b></summary>

<br>

Installation instructions coming never.

</details>

# Troubleshooting

<details>
<summary><b>"Failed to load font" when opening editor</b></summary>
Make sure the working directory contains the executable, and make sure the folder "Assets" exists
<img src="https://github.com/roguerousseau/Nucleus/blob/other/tree_of_build.png?raw=true">
</details>
