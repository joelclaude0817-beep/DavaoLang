# DavaoLang 🇵🇭

[English](#english) | [Filipino](#filipino)

---

## English

**DavaoLang** is a simple, beginner-friendly programming language with Filipino-inspired syntax. Perfect for learning programming concepts while embracing Filipino culture!

### Features

- 🌟 Filipino-inspired keywords (`sulti`, `kung`, `habang`)
- 📱 Runs on Termux (Android)
- 🖥️ Works on any system with Python 3
- 🎓 Beginner-friendly syntax
- ✅ Boolean values in Filipino (`Oo` / `Hindi`)
- 🔢 Variables, loops, conditionals, and user input

### Installation

#### On Termux (Android)

```bash
# Update packages
pkg update && pkg upgrade

# Install Python and Git
pkg install python git

# Clone the repository
git clone https://github.com/joelclaude0817-beep/DavaoLang.git
cd DavaoLang

# Run a program
python3 davaolang.py examples/hello.dl
```

#### On Linux/Mac/Windows

```bash
# Install Python 3 (if not already installed)
# Then clone the repository
git clone https://github.com/joelclaude0817-beep/DavaoLang.git
cd DavaoLang

# Run a program
python3 davaolang.py examples/hello.dl
```

### Quick Start

Create a file called `hello.dl`:

```
sulti "Kumusta Mundo!"
```

Run it:

```bash
python3 davaolang.py hello.dl
```

### Language Syntax

#### Keywords

| Keyword | English | Description |
|---------|---------|-------------|
| `sulti` | say/speak | Print output |
| `ay` | is | Variable assignment |
| `kung` | if | Conditional statement |
| `habang` | while | Loop statement |
| `tapos` | finished | End block |
| `dugang` | add | Increment variable |
| `kuha` | get | Get user input |
| `Oo` | Yes | True |
| `Hindi` | No | False |

#### Examples

**Variables:**
```
pangalan ay "Juan"
edad ay 25
sulti pangalan
```

**Conditionals:**
```
edad ay 18
kung edad >= 18
    sulti "You can vote!"
tapos
```

**Loops:**
```
counter ay 1
habang counter <= 5
    sulti counter
    dugang counter 1
tapos
```

**Booleans:**
```
is_ready ay Oo
kung is_ready
    sulti "Let's go!"
tapos
```

**User Input:**
```
sulti "Enter your name:"
kuha name
sulti name
```

### More Examples

Check the `examples/` folder for more sample programs:
- `hello.dl` - Hello World
- `variables.dl` - Working with variables
- `loop.dl` - Loops demonstration
- `boolean.dl` - Boolean values
- `input.dl` - User input

### Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

### License

MIT License - Feel free to use and modify!

### Author

Created with ❤️ for the Filipino programming community

---

## Filipino

**DavaoLang** ay isang simple at beginner-friendly na programming language na may Filipino-inspired na syntax. Perpekto para sa pag-aaral ng programming habang ipinagmamalaki ang kulturang Pilipino!

### Mga Feature

- 🌟 Filipino-inspired na keywords (`sulti`, `kung`, `habang`)
- 📱 Tumatakbo sa Termux (Android)
- 🖥️ Gumagana sa kahit anong system na may Python 3
- 🎓 Madaling maunawaan para sa beginners
- ✅ Boolean values sa Filipino (`Oo` / `Hindi`)
- 🔢 Variables, loops, conditionals, at user input

### Pag-install

#### Sa Termux (Android)

```bash
# I-update ang packages
pkg update && pkg upgrade

# I-install ang Python at Git
pkg install python git

# I-clone ang repository
git clone https://github.com/joelclaude0817-beep/DavaoLang.git
cd DavaoLang

# Patakbuhin ang program
python3 davaolang.py examples/hello.dl
```

#### Sa Linux/Mac/Windows

```bash
# I-install ang Python 3 (kung wala pa)
# Pagkatapos i-clone ang repository
git clone https://github.com/joelclaude0817-beep/DavaoLang.git
cd DavaoLang

# Patakbuhin ang program
python3 davaolang.py examples/hello.dl
```

### Quick Start

Gumawa ng file na `hello.dl`:

```
sulti "Kumusta Mundo!"
```

Patakbuhin:

```bash
python3 davaolang.py hello.dl
```

### Syntax ng Wika

#### Mga Keyword

| Keyword | Tagalog | Paglalarawan |
|---------|---------|--------------|
| `sulti` | magsalita | Mag-print ng output |
| `ay` | ay | Variable assignment |
| `kung` | kung | Conditional statement |
| `habang` | habang | Loop statement |
| `tapos` | tapos | Tapusin ang block |
| `dugang` | dagdag | Dagdagan ang variable |
| `kuha` | kuha | Kunin ang input |
| `Oo` | Oo | Totoo (True) |
| `Hindi` | Hindi | Mali (False) |

#### Mga Halimbawa

**Variables:**
```
pangalan ay "Juan"
edad ay 25
sulti pangalan
```

**Conditionals:**
```
edad ay 18
kung edad >= 18
    sulti "Pwede ka nang bumoto!"
tapos
```

**Loops:**
```
counter ay 1
habang counter <= 5
    sulti counter
    dugang counter 1
tapos
```

**Booleans:**
```
is_ready ay Oo
kung is_ready
    sulti "Tara na!"
tapos
```

**User Input:**
```
sulti "Ilagay ang iyong pangalan:"
kuha name
sulti name
```

### Mas Maraming Halimbawa

Tingnan ang `examples/` folder para sa mas maraming sample programs:
- `hello.dl` - Hello World
- `variables.dl` - Paggamit ng variables
- `loop.dl` - Demonstrasyon ng loops
- `boolean.dl` - Boolean values
- `input.dl` - User input

### Pag-contribute

Malugod naming tinatanggap ang contributions! Pwede kang:
- Mag-report ng bugs
- Magsuggest ng bagong features
- Magsumite ng pull requests
- Pagbutihin ang documentation

### Lisensya

MIT License - Malayang gamitin at baguhin!

### May-akda

Ginawa nang may ❤️ para sa Filipino programming community
