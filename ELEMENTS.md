# Example elements

---

> ### 1. Setup
> ### 2. Info
> ### 3. Usage
> ### 4. Build
> ### 5. Custom
> ### 6. More
> ### 7. Details
 
---

> # 1. Setup

> [!IMPORTANT]
> # Setup
> **example command**
> ```sh
> git clone https://github.com/Szmelc-INC/Zen-Docs && cd Zen-Docs
> ```
> **desc 2**
> ```sh
> make && sudo make install && make clean
> ```

---

> # 2. Info

> [!NOTE]
> # ***Info***
> >
> > ## **desc**
>> ### Data tables / Info
>> | some value | value 2 | 3 |
>> |---|---|---|
>> | ❌ | Example / 2 / 3 | **4** |
>> | ✅ | Whatever | **E** |
>> | ⭐ | XYZ / AAA / BBB | **CCC** |
>>
> > #### **desc**
>> <details>
>> <summary><b><h2>TITLE</b></summary>
>>
>> ### Data tables / Info
>> | some value | value 2 | 3 |
>> |---|---|---|
>> | ❌ | Example / 2 / 3 | **4** |
>> | ✅ | Whatever | **E** |
>> | ⭐ | XYZ / AAA / BBB | **CCC** |
>> </details>

---

# 3. Usage

> [!TIP]
> Details on usage and available options
> # Usage
> ```bash
> cdvd [-f fps] [-s speed] [-t decay_sec] [-L logo.txt] [--info] [--mask-edges|--mask-blanks]
> ```
>
>### Hotkeys (at runtime)
>| Action | Key(s) |
>|---|---|
>| Toggle trail | `t` |
>| Toggle info HUD | `i` |
>| Speed ± | `←` / `→` |
>| FPS ± | `↑` / `↓` |
>| Decay ± | `y` / `u` |

---

# 4. Build

> [!IMPORTANT]
> # Build
> You can change logo to anything you preffer before compilation, to bake it into binary, or with a `-L` flag in runtime \
> Make sure you have `logo.txt` with ASCII art before compiling \
> ## Buld
> With Makefile:
>```c
>#   make                 # build
>#   make run             # run with nice defaults
>#   sudo make install    # install to /bin/cdvd  (override BINDIR/INSTALL_NAME)
>#   sudo make uninstall  # remove installed binary
>#   make clean           # clean artifacts
>```
> Alternatively run `bash compile.sh` \
> Or manually:
> Convert logo.txt to inc before compilation
>```c
>xxd -i -n dvd_logo logo.txt > logo.inc
>```
> Compile
>```c
>export LANG=en_US.UTF-8
>gcc -O2 -Wall -Wextra -std=c11 dvd_ascii.c -lncursesw -lm -o dvd
>```

---

# 5. Custom

> [!NOTE]
> ## Custom logos
>- Provide your own ASCII/UTF‑8 art via `-L path/to/logo.txt` at runtime.
> ### Default logo.txt
> > ```csv
> > ⠀⠀⣸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⠀⢀⣾⣿⣿⣿⣿⣿⣿⣿⣿⣶⣦⡀
>>⠀⢠⣿⣿⡿⠀⠀⠈⢹⣿⣿⡿⣿⣿⣇⠀⣠⣿⣿⠟⣽⣿⣿⠇⠀⠀⢹⣿⣿⣿
>>⠀⢸⣿⣿⡇⠀⢀⣠⣾⣿⡿⠃⢹⣿⣿⣶⣿⡿⠋⢰⣿⣿⡿⠀⠀⣠⣼⣿⣿⠏
>>⠀⣿⣿⣿⣿⣿⣿⠿⠟⠋⠁⠀⠀⢿⣿⣿⠏⠀⠀⢸⣿⣿⣿⣿⣿⡿⠟⠋⠁⠀
>>⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⣀⣀⣸⣟⣁⣀⣀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
>>⣠⣴⣶⣾⣿⣿⣻⡟⣻⣿⢻⣿⡟⣛⢻⣿⡟⣛⣿⡿⣛⣛⢻⣿⣿⣶⣦⣄⡀⠀
>>⠉⠛⠻⠿⠿⠿⠷⣼⣿⣿⣼⣿⣧⣭⣼⣿⣧⣭⣿⣿⣬⡭⠾⠿⠿⠿⠛⠉⠀
>>```
> #### Or bake it in at compile time using the `xxd` step above.
>- Make sure your terminal font supports the characters you use.

---

# 6. More

> [!WARNING]
>>## Logos / Banners
>> <details><summary><b><h3>Images / Logos</b></summary>
>> Banners <br>
>> <img src="https://raw.githubusercontent.com/serainox420/serainox420/refs/heads/personal/vector/banner-black2.svg" alt="long" width="280">
>>  </a><br><br>
>> <img src="https://raw.githubusercontent.com/serainox420/serainox420/refs/heads/personal/vector/banner-white2.svg" alt="long" width="280">
>>  </a><br><br>
>> Logos <br>
>> <img src="https://raw.githubusercontent.com/serainox420/serainox420/refs/heads/personal/vector/logo-white.svg" alt="long" width="80">
>>  </a><br><br>
>> <img src="https://raw.githubusercontent.com/serainox420/serainox420/refs/heads/personal/vector/logo-black.svg" alt="long" width="80">
>> </details></h3>

---

# 7. Caution Details

> [!CAUTION]
> DETAILS
>## Requirements
>
>- A POSIX‑y environment (Linux, BSD, macOS).
>- `ncursesw`, `gcc`/`clang`, and `make` (if using the Makefile).
>- UTF‑8 locale (e.g., `LANG=en_US.UTF-8`).
>
> ---
>
>## 📝 Notes
>
>- Terminal size affects bounce boundaries (resizing is handled on the fly).
>- For best visuals, use a font with good box‑drawing / block character coverage.
>- Also, Important to note is, this project was mostly just ***Vibe Coded*** with much help from an A.I assistant,
>- while I took it as a learning opportunity with a project that does not neceaseaarly have to be fully understood right away and memory safe!
