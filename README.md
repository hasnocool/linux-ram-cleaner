# Memory Cleanup Script for Linux Systems

## Introduction
This Bash script is designed to clear various types of caches in a Linux system to free up memory. It clears PageCache, dentries, inodes, and also disables and re-enables swap to clear it.

## Prerequisites
- Linux system
- Root access
- Bash shell

## Installation
1. Download the script and save it as `memory_cleanup.sh`.
2. Make the script executable:
   ```bash
   chmod +x memory_cleanup.sh
   ```
Usage
Run the script with root privileges:

```bash
sudo ./memory_cleanup.sh
```
This will display the memory usage before and after the cleanup.

## What the Script Does
Display current memory usage: Uses free -h to show the current memory usage.
Clear PageCache only: Clears only the PageCache.
Clear dentries and inodes: Clears directory entries and inodes.
Clear PageCache, dentries, and inodes: Clears PageCache, directory entries, and inodes.
Disable and re-enable swap: Turns off and then turns on the swap to clear it.
Display memory usage after cleanup: Uses free -h to show the memory usage after the cleanup.
## Disclaimer
This script requires root access. Use it cautiously, as clearing caches might have unintended side effects on running applications.
