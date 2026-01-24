# LazyIDA
Make your IDA Lazy!

## Installation

### Method 1: Using hcli (Recommended)

```
hcli plugin install LazyIDA
```

### Method 2: Manual Installation

1. Download or clone this repository.
2. Copy `LazyIDA.py` into your IDA plugins directory:
   - **Windows:**  
     `%APPDATA%\Hex-Rays\IDA Pro\plugins\`
   - **macOS/Linux:**  
     `~/IDA/plugins/`
3. Restart IDA.

# Features
  - Remove function return type in Hex-Rays (IDA 7.5+ has this feature built-in):  

![2016-06-12 11 05 29](https://cloud.githubusercontent.com/assets/5360374/15991889/2dad5d62-30f2-11e6-8d4b-e4efb0b73c77.png)

  - Convert data into different formats, output will also be automatically copied to the clipboard:
  
![2016-06-12 11 01 57](https://cloud.githubusercontent.com/assets/5360374/15991854/b813070a-30f1-11e6-931e-08ae85355cca.png)
![2016-06-12 11 03 18](https://cloud.githubusercontent.com/assets/5360374/15991863/e5271146-30f1-11e6-89ac-bafd46eb1e45.png)
  - Scan for format string vulnerabilities:
  
![2016-06-15 8 19 03](https://cloud.githubusercontent.com/assets/5360374/16064234/da39aa8c-32d1-11e6-89b8-1709cef270f5.png)
  - Jump to vtable functions by double clicking
  - Lazy shortcuts:
    - Disasm Window: 
      - `w`: Copy address of current line into clipboard
    - Hex-rays Window: 
      - `w`: Copy address of current item into clipboard
      - `c`: Copy name of current item into clipboard
      - `v`: Remove return type of current item
