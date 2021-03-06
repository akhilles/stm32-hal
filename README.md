# STM32-HAL

This library provides access to several peripherals. It's based on the 
[STM32 Peripheral Access Crates](https://github.com/stm32-rs/stm32-rs) generated by [svd2rust](https://github.com/rust-embedded/svd2rust)

It's designed to provide a consistent API across multiple families, with minimal code repetition.
This makes it easier to switch MCUs within, or across families, for a given project.

It aims to implement features that are similar across families, but not ones
that differ significantly.

This crate errs on the side of exposing peripherals that don't exist for a given
MCU variant.