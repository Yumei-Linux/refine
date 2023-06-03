# Refine

Refine is a little bash script tool that just makes the base system bootstrapping to let it working before getting
into the packaging installation phase.

> This tool has to be ran after running [akari](https://github.com/Yumei-Linux/akari)

## Installation

```sh
sudo make PREFIX=/usr install
```

## Usage

> run as root and inside the actual system (you might want to use [yumei-chroot](https://github.com/Yumei-Linux/yumei-chroot)).

```sh
refine
```