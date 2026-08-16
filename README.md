# Nexis (coming Soon)


Nexis is a open source recovery and system-assistance tool designed specifically for Arch Linux and Arch-based systems.

Nexis is designed to help users recover and repair their Linux installation when common system problems occur, including issues involving system files, Wi-Fi, Bluetooth, and other essential components.

# Architecture

Nexis is built around two main components:

* nexis-core — the core CLI engine responsible for the underlying recovery and system operations.
* nexis-gui — a graphical interface built with GTK4/libadwaita, providing a user-friendly way to interact with Nexis.

# Recovery System

One of Nexis’s main features is its dedicated recovery mechanism.

Nexis uses a small Tiny Core Linux recovery environment that can be stored on a separate partition. This environment is designed to provide a way to start Nexis even when the main Linux installation or kernel is no longer bootable.

Nexis maintains a system state snapshot containing information such as:

* Partition UUIDs
* fstab configuration
* Kernel information
* Bootloader information

This allows Nexis to understand the system configuration and assist with recovery operations when the primary installation encounters serious problems.

# System Assistance

Nexis is designed to assist with common Arch Linux system issues, including:

* Installing applications
* Repairing system files
* Fixing Wi-Fi problems
* Fixing Bluetooth problems
* Recovering from system-level issues
* Restoring a system after critical changes to the main installation

# Distribution Support

The initial release will target Arch Linux and Arch-based distributions only.

Initial support is planned for Arch-based systems, with compatibility for additional Linux distributions planned for future updates.

# Development Status

Nexis is currently under active development.

The project is Coming Soon, and the architecture, recovery system, GUI, and supported configurations are still being developed and tested.

Roadmap

* Core architecture
* nexis-core concept
* nexis-gui concept
* Recovery environment concept
* Tiny Core Linux recovery partition concept
* Initial Arch-based release
* Recovery system testing
* GUI completion
* Additional Arch-based distribution support
* Support for other Linux distributions in future updates

Nexis is currently a work in progress. More details, installation instructions, and release information will be published when the first version is ready.

i hope for ur support guys <3 .
