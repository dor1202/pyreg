## lazyregex - Python Regex CLI Tool!

Lazyregex provides a terminal UI to test and develop regexes.

The aim of this project is to make it easier to test and develop regexes without having to leave the terminal or browse the web.

---

## Note...

Lazyregex is an idea of a frustrated developer who got the task of developing regexes and not by a big corporation with deep pockets.

It is a project that is being developed by a single person in their free time.

If you feel Lazyregex makes your regex journey a bit easier, saves you time and makes you more productive, please consider [sponsoring!](https://github.com/sponsors/dor1202)
Your donations will go a long way in keeping the project alive and beers in my fridge! 🍺

**Thank you!**

---

[![Release](https://img.shields.io/github/release-pre/dor1202/lazyregex.svg)](https://github.com/dor1202/lazyregex/releases)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/dor1202/lazyregex/blob/main/LICENSE)
<!-- [![Downloads](https://img.shields.io/github/downloads/dor1202/lazyregex/total.svg)](https://github.com/dor1202/lazyregex/releases) -->

---

## Screenshots

1. Match
   <img src="https://github.com/dor1202/lazyregex/blob/main/assets/match_example.png?raw=true"/>
2. Substitution
   <img src="https://github.com/dor1202/lazyregex/blob/main/assets/sub_example.png?raw=true"/>
3. Regex Options
   <img src="https://github.com/dor1202/lazyregex/blob/main/assets/options_example.png?raw=true"/>

## Installation

### Homebrew

Normally `lazyregex` formula can be found in the Homebrew core but we suggest you to tap our formula to get frequently updated one. It works with Linux, too.

**Tap**:
```sh
brew tap dor1202/lazyregex
brew install lazyregex
```

**Core (Not implemented yet)**:
```sh
brew install lazyregex
```

### Scoop (Windows)(Not implemented yet)

You can install `lazyregex` using [scoop](https://scoop.sh/):

```sh
scoop install lazyregex
```
### Chocolatey (Windows)(Not implemented yet)

You can install `lazyregex` using [Chocolatey](https://chocolatey.org/):

```sh
choco install lazyregex
```

---

## Starting Lazyregex

  ```shell
  lazyregex
  ```

---

## Building From Source

 Lazyregex is currently using Python v3.8.X or above.
 In order to build Lazyregex from source you must:

 1. Clone the repo
 2. Build and run the executable

      ```shell
      poetry run lazyregex
      ```

---

## Lazyregex Compatibility Matrix

|         Lazyregex        | python |
| ------------------ | ---------- |
|     LTS     |   "3.8", "3.9", "3.10", "3.11", "3.12"   |

---

## Contributors

Without the contributions from these fine folks, this project would be a total dud!

<a href="https://github.com/dor1202/lazyregex/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=dor1202/lazyregex" />
</a>

---

## Known Issues

This is still work in progress! If something is broken or there's a feature
that you want, please file an issue and if so inclined submit a PR!

---

## Contributions Guideline

* File an issue first prior to submitting a PR!
* Ensure all exported items are properly commented

---

## References

Big thanks to the following projects for their inspiration:

* [Textual](https://github.com/Textualize/textual)
* [k9s](https://github.com/derailed/k9s)
* [rexi](https://github.com/royreznik/rexi)

Without them, this project would not be possible.