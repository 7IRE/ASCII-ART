# ASCII ART 
- This project allows you to generate C code for ASCII art using **24-bit BMP format** images. Transform your images into a fun ASCII representation effortlessly!

- The BMP format is converted into equivalent functional block which can be copied and used in other C/C++ programs without using additional libraries .


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
## Credits

- This project uses [stb_image.h](https://github.com/nothings/stb) by Sean Barrett.  
- stb_image is a single-file public domain library for loading images in C/C++.