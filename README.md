# ASCII ART 
- This project allows you to generate C code for ASCII art using **24-bit BMP format** images. Transform your images into a fun ASCII representation effortlessly!

- The BMP format is converted into equivalent functional block which can be copied and used in other C/C++ programs without using additional libraries .

  
![WhatsApp Image 2025-12-09 at 19 25 04](https://github.com/user-attachments/assets/25947b22-e0b3-4bfc-b482-0c43884f2edc)


---
## Features

- Convert 24-bit BMP images to ASCII art.
- Easily include generated code into your C programs.
- Precompiled executable for quick use.

---
## Getting Started

Follow these steps to use the ASCII Art Generator:

1. **Obtain Your BMP File**  
   Find or create a BMP file, which can be downloaded from the internet or made using image generation software.

2. **Rename the File**  
   Rename your BMP file to **image.bmp**.

3. **Run the Program**:
   - You can run the precompiled executable **ASCII-Generator.exe**.
   - Alternatively, you can compile the source code yourself. Open a terminal in the same folder as the source code and run:  
     ```bash
     gcc ASCII-Generator.c -o ASCII-GENERATOR
     ```

4. **Check the Output**  
   After running the generator, check the **Generated.c** file. This file contains the C code for your ASCII art, which you can integrate into other functions or compile to test its output.

5. **Have Fun!**

---

## Note

This repository includes:
- A sample BMP image for testing.
- The generated C code.
- A compiled version of the executable.


---

## Things to Keep in Mind When Writing Programs with This Generator

- 📐 **Pixel Ratio**: Each pixel is represented as `2 x 1`.  
  For example, if you have a `32 x 32` image, the next image should be placed at `row = 0`, `column = 64`.

- 🎯 **Coordinates Reference**: The coordinates you provide to the function represent the **upper-left corner** of the image.

- 🖥️ **Terminal Boundaries**: Always provide coordinates that fit within the terminal view.  
  Placing images outside the visible area may cause issues.  
  You can resize the terminal using **CTRL + Plus (+)** and **CTRL + Minus (-)**.

---
## Credits

- This project uses [stb_image.h](https://github.com/nothings/stb) by Sean Barrett.  
- stb_image is a single-file public domain library for loading images in C/C++.
