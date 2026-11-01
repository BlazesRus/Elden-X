# Elden-X

This repository is a fork of Elden-X by Thomas J. Clark.

## Original Purpose

The original Elden-X project was created as a collection of miscellaneous C++ utilities, shared structures, and runtime DLL extension functionality used across multiple ELDEN RING modding projects. Its primary goal was to centralize commonly reused code and avoid duplicating structures and utilities between projects.

Used in mods such as:
- [Transmogrify Armor](https://www.nexusmods.com/eldenring/mods/3596) by Thomas J. Clark
- [Glorious Merchant](https://www.nexusmods.com/eldenring/mods/5192) by Thomas J. Clark
- [Armor Dyes](https://github.com/ThomasJClark/elden-ring-dyes) by Thomas J. Clark
- [Quest Log](https://www.nexusmods.com/eldenring/mods/3585) by TheEldenRingQuestGiver

## Fork Purpose

This fork is intended to modernize and expand Elden-X as part of a broader SDK and Game Mod Framework effort. The long-term goal is to provide reusable infrastructure for ELDEN RING integration, including support for systems such as the Virtual Record System.

The Game Mod Framework itself is intended to remain game-agnostic. ELDEN RING-specific offsets, structures, and implementation details will remain within Elden-X and/or related ELDEN RING integration components rather than the framework core.

In addition to preserving Elden-X's original utility-library goals, this fork aims to provide a foundation for reusable SDK components, record management systems, and framework integration.

## Status

This is an experimental development fork. APIs, structures, offsets, and implementation details may change as framework integration work progresses.

Consider [eldenring-rs](https://github.com/vswarte/eldenring-rs) and/or [libER](https://github.com/Dasaav-dsv/libER) for more direct modding purposes.
