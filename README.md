# Pruner (Fork)

An `fzf`-powered, interactive fonts & themes manager for Termux wrapped in one Bash script. Fuzzy-filter through a gorgeous menu, and let the script handle all the scary commands syntax for you.

*Fork maintained by **Haitham Aouati** (Original tool created by [Y3rw1N](https://github.com/Y3rw1N/pruner/tree/main)).*

## Screenshot

![screenshot](screenshot.png)

## Installation & Dependencies

Install the required dependencies (`curl`, `jq`, and `fzf`): `pkg add curl jq fzf -y`

Then clone the repository and enter its directory:

```
git clone https://github.com/haithamaouati/pruner.git
cd pruner
./pruner --help
```

## Usage
​**Interactive Mode**

​Run `./pruner` without any arguments to launch the `fzf`-powered interactive menu:
```
./pruner
```

From the interactive menu, you can seamlessly fuzzy-search, download, apply, and manage your Termux themes and Nerd Fonts.

## ​CLI Commands
​You can also run commands directly via flags:

- **Apply a font or theme** (downloads automatically if not cached):
```
./pruner set -f <font-name>
./pruner set -t <theme-name>
```

- **Download a font or theme:**
```
./pruner install -f <font-name>
./pruner install -t <theme-name>
```

- **Remove a stored font or theme:**
```
./pruner remove -f <font-name>
./pruner remove -t <theme-name>
```

- **Remove all cached downloads:**
```
./pruner remove -a
```

- **Display help information:**
```
  ./pruner --help
```
  
