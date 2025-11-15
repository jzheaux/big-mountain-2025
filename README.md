# big-mountain-2025
Once Upon a PR Preso

## Running the Slides

This repository contains a presentation in `slides.md` that can be viewed using [patat](https://github.com/jaspervdj/patat) (Presentations And The ANSI Terminal).

### Installing patat

#### macOS
```bash
brew install patat
```

#### Linux
- **Ubuntu/Debian:**
  ```bash
  sudo apt-get install patat
  ```
- **Arch Linux:**
  ```bash
  sudo pacman -S patat
  ```
- **From source (requires Haskell Stack):**
  ```bash
  git clone https://github.com/jaspervdj/patat.git
  cd patat
  stack install
  ```

#### Windows
- Download the pre-built binary from the [releases page](https://github.com/jaspervdj/patat/releases)
- Or use [Chocolatey](https://chocolatey.org/):
  ```powershell
  choco install patat
  ```

For more installation options, see the [official patat installation guide](https://github.com/jaspervdj/patat#installation).

### Running the Presentation

Once patat is installed, run the presentation with:

```bash
patat slides.md
```

### Navigation

- **Next slide:** Space, Enter, or Arrow Right
- **Previous slide:** Backspace or Arrow Left
- **Quit:** q or Esc
- **Help:** ? (shows all keybindings)
