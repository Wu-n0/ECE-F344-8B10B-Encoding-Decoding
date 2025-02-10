# ECE F344 - Information Theory & Coding  
## 8B/10B Encoding & Decoding

This project implements the **8B/10B encoding scheme**, which is widely used in high-speed data transmission systems like **Ethernet, PCIe, and SATA**. The main goal is to convert **8-bit data into 10-bit symbols** to ensure **error detection, clock recovery, and reliable communication**.

The implementation is done in **Python**, and MATLAB is used for verification to ensure correctness.

---

## What’s This About?
In high-speed networks, raw binary data isn’t sent directly. Instead, it is encoded using a scheme like **8B/10B**, which:
- Ensures **DC balance** (equal number of 0s and 1s to prevent signal distortion).
- Adds **extra transitions for clock synchronization**.
- Provides **basic error detection** to catch transmission errors.

This project covers both **encoding and decoding**, making it a great hands-on example of how real-world digital communication works.

---

## Project Files
The project files are located inside the `Code/` folder:

- `main.py` - The main script for encoding and decoding.
- `decode.py` - The decoder that converts 10-bit symbols back to 8-bit data.
- `matlab_code.m` - MATLAB script to verify the correctness of the implementation.
- `documentation.pdf` - Detailed explanation of how 8B/10B encoding works.

---

## How to Run It
Make sure you have **Python 3+** installed, then you can encode or decode data using:

```bash
python main.py
python decode.py
```

If you want to verify the results using MATLAB, open MATLAB and run:

```matlab
run('matlab_code.m')
```
