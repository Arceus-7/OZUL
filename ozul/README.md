# OZUL Programming Language

![OZUL Language Badge](https://github.com/Arceus-7/OZUL/blob/51d84baf4f94d5cf7dd8a282c4fbca067e9e5a62/Eevee%20Teste.jpg)

OZUL is a minimal Pokémon-themed programming language. It supports basic arithmetic and string operations, using Pokémon-themed keywords and types:

- `Pikachu` — integer (`int`)
- `Psyduck` — floating point (`float64`)
- `Eevee` — string

---

## 🚀 Quick Start (No Coding Required)

**1. Download OZUL**
- Go to the [GitHub Releases](https://github.com/Arceus-7/OZUL/releases) page.
- Download the file named `ozul.exe` (for Windows) or the appropriate binary for your computer (Windows, Mac, or Linux).
- If the file is zipped (`.zip`), double-click it and extract it to a folder (e.g., `OZUL`).

**2. Run Your First OZUL Program**
- Place your `.ozul` program file (e.g., `myprog.ozul`) in the same folder as `ozul.exe`.
- On Windows: Double-click `ozul.exe` or open a Command Prompt in that folder and run:
  ```
  ozul.exe myprog.ozul
  ```
- On Mac/Linux: Open a terminal in that folder and run:
  ```sh
  ./ozul myprog.ozul
  ```

**That’s it!** You’ll see the output of your OZUL program in the window.

---

## 🐾 Example OZUL Program
```ozul
Eevee msg is "Hello!"
release msg
Pikachu x is 5
Psyduck y is 3.14
Eevee name is "Ash"
release x
release y
release name
catch pokemon_number from trainer
```

---

## 🛠️ Advanced: Build from Source
- Install Go (https://golang.org/dl/)
- Open a terminal/command prompt and run:
  ```sh
  cd ozul
  go build -o ozul
  ```

## 🛠️ Advanced: Generate C Code
- To generate C code from your OZUL program:
  ```sh
  ./ozul myprog.ozul -c -o myprog.c
  ```
- Then compile with GCC:
  - **On Windows:**
    ```sh
    gcc myprog.c -o myprog.exe
    myprog.exe
    ```
  - **On Linux/macOS:**
    ```sh
    gcc myprog.c -o myprog
    ./myprog
    ```

## 🐞 Debugging
- Add the `-debug` flag to print tokens and AST for your program:
  ```sh
  ./ozul myprog.ozul -debug
  ```

---

## ❓ Troubleshooting
- **Windows: 'Windows protected your PC'**
  - Click 'More info' > 'Run anyway'.
- **'ozul.exe' won’t run:**
  - Make sure you extracted the file from the zip.
  - Make sure your `.ozul` file is in the same folder.
- **On Mac/Linux: 'Permission denied'**
  - Run: `chmod +x ozul` to make it executable.
- **Still stuck?**
  - Open an issue on GitHub or ask a friend for help!

---

## Distribution
To distribute OZUL:
- Package the `ozul` binary, example `.ozul` files, and this `README.md` into a zip file.
- Users can then follow the instructions above to run OZUL programs on their system.

## License
MIT

---

## 🆘 Getting Help
- **Check the FAQ:** See if your question is answered in the README or on the GitHub Discussions/FAQ page.
- **Open an Issue:** If you have a problem or bug, go to the [Issues](https://github.com/Arceus-7/OZUL/issues) page and click 'New Issue'.
- **Contact the Maintainer:** If you’re really stuck, you can email the maintainer (see the GitHub profile or repository contact info).
- **Ask a Friend:** Sometimes a friend or family member can help you get started! 