# Customized Oppo/Realme SM8750 Kernel

This repository is a personal fork of the [original repository](https://github.com/cctv18/oppo_oplus_realme_sm8750) with a few quirky, non-standard modifications tailored to my own needs.

## Features Added

So far, I have only added a handful of features:

- **ZWSP Bypass Fix**: Fixed zero-width space issues based on `utf8data`.  
  [Source](https://t.me/newqianzhuang/52?comment=59)

- **HymoFS Support**: Integrated [HymoFS](https://github.com/Anatdx/HymoFS/) for custom filesystem handling.

- **Baseband-Guard Enhancements**: Implemented Baseband-guard's unusual random rejection logic.  
  [More Info](https://github.com/cctv18/Baseband-guard/)

- **KernelSU Handling**: No arbitrary KernelSU compilation included — keep it clean and simple.

- **Modifiable SukiSU repository link** – to prevent a certain developer from breaking SukiSU, or to make it easier to switch to ReSukiSU.

---

> ⚠️ This fork is not intended for mainstream use. It's purely experimental and serves my personal workflow.
