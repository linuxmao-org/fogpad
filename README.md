# Fogpad

[![Build Status](https://travis-ci.com/linuxmao-org/fogpad.svg?branch=master)](https://travis-ci.com/linuxmao-org/fogpad)

A reverb effect in which the reflections can be frozen, filtered, pitch shifted and ultimately disintegrated

## About

This is a port of the Fogpad plugin created by Igorski.
It is based on the DISTRHO plugin framework (DPF) to provide support of
GNU/Linux and other platforms.

Based on the upstream revision: d5b2a27

## Downloads

**Development**

- All: download from [Automatic builds](https://github.com/linuxmao-org/fogpad/releases/tag/automatic).

## Build instructions

1. Obtain prerequisites

Install needed packages:

- `git`
- `build-essential`
- `pkg-config`
- `libx11-dev`
- `libcairo2-dev`
- `libjack-jackd2-dev` or `libjack-dev`
- `mesa-common-dev`

2. Check out the repository and submodules

```
git clone https://github.com/linuxmao-org/fogpad.git
cd fogpad
git submodule update --init
```

3. Compile

```
make
```

4. Install

```
sudo make install  # to install in system directories, or
make install-user  # to install in the home directory
```
