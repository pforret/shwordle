![Shellcheck CI](https://github.com/pforret/shwordle/workflows/Shellcheck%20CI/badge.svg)
![GH Language](https://img.shields.io/github/languages/top/pforret/shwordle)
![GH stars](https://img.shields.io/github/stars/pforret/shwordle)
![GH tag](https://img.shields.io/github/v/tag/pforret/shwordle)
![GH License](https://img.shields.io/github/license/pforret/shwordle)
[![basher install](https://img.shields.io/badge/basher-install-white?logo=gnu-bash&style=flat)](https://basher.gitparade.com/package/)

# shwordle

CLI version of Wordle with choice of # letters and choice of langauge

## 🔥 Usage

```
Program: shwordle 0.1.8 by peter@forret.com
Updated: Feb  5 14:43:26 2022
Description: CLI Wordle
Usage: shwordle [-h] [-q] [-v] [-f] [-l <log_dir>] [-t <tmp_dir>] [-e <letters>] [-g <guesses>] [-u <language>] <action>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -q|--quiet       : [flag] no output [default: off]
    -v|--verbose     : [flag] output more [default: off]
    -f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
    -l|--log_dir <?> : [option] folder for log files   [default: /Users/pforret/log/shwordle]
    -t|--tmp_dir <?> : [option] folder for temp files  [default: /tmp/shwordle]
    -e|--letters <?> : [option] word length  [default: 5]
    -g|--guesses <?> : [option] allowed guesses  [default: 6]
    -u|--language <?>: [option] word language  [default: en-us]
    <action>         : [parameter] action to perform: play/options
```

## ⚡️ Examples

```bash
> shwordle play
# start Shwordle with default options

>shwordle -e 4 play
# start Showrdle with 4 letter word

>shwordle -u nl play
# start Shwordle with Dutch words


```

## 🚀 Installation

with [basher](https://github.com/basherpm/basher)

	$ basher install pforret/shwordle

or with `git`

	$ git clone https://github.com/pforret/shwordle.git
	$ cd shwordle

## 📝 Acknowledgements

* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2022 Peter Forret
