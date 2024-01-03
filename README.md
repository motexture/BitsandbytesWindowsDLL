# bitsandbytes-windows-dll

## Overview
This repository provides CUDA 11.8 compiled DLLs for `bitsandbytes`, offering a fix for recent versions that caused issues during runtime. Special thanks to [emojiiii](https://github.com/emojiiii/) for the DLL files!

## Installation Instructions

### Step 1: Install the DLL File
1. Download the `libbitsandbytes_cuda118.dll` file.
2. Navigate to the following directory: C:\Users%USERNAME%\AppData\Local\Programs\Python\Python310\Lib\site-packages\bitsandbytes\
3. Paste the `libbitsandbytes_cuda118.dll` file into this directory.

### Step 2: Update the `main.py` File
1. Download the `main.py` file.
2. Go to the following directory: C:\Users%USERNAME%\AppData\Local\Programs\Python\Python310\Lib\site-packages\bitsandbytes\cuda_setup\
3. Replace the existing `main.py` file with the new one.

---

**Note:** Ensure you have the necessary permissions to modify files in the installation directories.

## Credits
DLL files provided by [emojiiii](https://github.com/emojiiii/).

---
