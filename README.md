# `OLEGEASE`
> general information about my personal projects andor applications

## Repositories

- **`template`**: _template repository with minimal structure of future projects, base template for other templates_
- **`hello-mxx-world`**: _exemplar of `C++23` Standard Modules `CMake` dual projects:_
  - `ghub`: _`Library` Module_
  - `berg`: _`Program` that uses `ghub` Module Library_
- **`hello-cxx-world`**: _exemplar of `C++17` Standard Headers `CMake` dual projects:_
  - `ghub`: _`Library` Static_
  - `berg`: _`Program` that uses `ghub` Static Library_
- **`hello-asm-world`**: _exemplar of `C90` Standard Pedantic `Makefile` with `NASM x86-64` assembly dual projects:_
  - `ghub`: _`Library` Shared_
  - `berg`: _`Program` that uses `ghub` Shared Library_
- **`hello-web-world`**: _exemplar of `JavaScript NodeJS (mjs)`, Postgres and Web `(JS, HTML and CSS)` dual projects_
  - `ghub`: _`Package` Remote_
  - `berg`: _`Program` that uses `ghub` Remote Package_
- **`ease-git`**: _simple C++ application for git commands wrapper, at start only cloning repos based on current directory path_

## Organizations
> most of all projects are computer graphics related ones which targets mainly `x86-64` architecture on `linux` (as a main development environment)

- **`forkease`**: _fork repositories to my personal andor my organization andor any other organization in `{Org Alias or Full Name}-{Original Repo Name}`_
- **`soneight`**: _namespace `son8` `C++17` oriented `3D OpenGL` graphics related projects, mainly retro `RPG` style games_
- **`motwonil`**: _namespace `mo20` `C++23+` only with `import std` and standard modules `3D Vulkan` graphics related projects (pending), mainly renderer engines_
- **`nethreed`**: _global web `NE3` package scope `@ne3` `Javascript NodeJS` web `2D WebGL` graphics related projects (pending)_
- **`asevenly`**: _prefix `a7` `Assembly NASM x64 and C90 C` language standard `2D Software Rendering` graphics related projects (pending), mainly graphical user interfaces_

### Son 8

- libraries: _using CMake required version in range `3.8..3.27`, lower minimum for C++17 standard available, upper maximum because of next version kind of supports C++20 modules_
- applications: _using CMake required version in range `3.20..3.27`, lower minimum for configure and build presets, upper maximum same as libraries_

#### IMPORTANT
> before adding `git` tag to a project use `git --amend` until it generates hash that starts with `8` number

## Remotes

a base:
> original repository

- `origin`: _for libraries `github`, for applications `codeberg`_
- `mirror`: _for libraries `codeberg`, for applications `github`_

a fork:
> forked repository

- `root`: _original project_
- `fork`: _fork from original_

a docs:
> documentation only repository

- `ghub`: _`github` clone_
- `berg`: _`codeberg` clone_

## Licensing

- `libraries`: _[`Apache License 2.0`](https://spdx.org/licenses/Apache-2.0.html)_
- `applications`: _[`GNU Affero General Public License v3.0 or later`](https://spdx.org/licenses/AGPL-3.0-or-later.html)_
- `documentations`: _[`Creative Commons Attribution Non Commercial 4.0 International`](https://spdx.org/licenses/CC-BY-NC-4.0.html)_
- `other`: _[`Boost Software License 1.0`](https://spdx.org/licenses/BSL-1.0.html)_

## Versions
> naming in git commit messages

- `alpha (v0.0.z)`: _alpha patch z_
- `beta (v0.y.z)`: _beta y patch z_
- `major (vX.y.z)`: _major X minor y patch z_

## Code Style Naming and Formatting

### C++

- Naming:
  - `UPPER_SNAKE_CASE`: _macros_
  - `Pascal_Snake_Case`: _constants, enum class members_
  - `camel_Snake_Case`: _private functions_
  - `lower_snake_case`: _functions and class methods_
  - `PascalCase`: _class types, global variables_
  - `PascalCaseUnderscored_`: _private types_
  - `camelCase`: _function arguments, local variables_
  - `camelCaseUnderscored_`: _private data members_

- Formatting:
  - Always insert spaces after `Curly {`, `Round (`, `Angle <` opening brackets and before `Curly }`, `Round )`, `Angle >` closing brackets but not before or after `Array [` opening or `Array ]` closing brackets
  - When brackets are after each other only last one should contain space character

## Naming Things
> used for naming related up to four things, word chains (mostly pairs) with same character length

- brackets: `Angle < >` - `Array []` - `Curly { }` - `Round ( )`
- list element position related: `Prev` - `Curr` - `Next`
- stack operations (also flag operation like `set-get-clear`): `Put` - `Top` - `Pop`

### General Word Pairs Table
> usually pair forms from: smaller to larger, populating to destroying or obtaining, good to bad

|     3-4     |      5-5      |       6-6       |         7-8         |
|:-----------:|:-------------:|:---------------:|:-------------------:|
|  `Set-Get`  | `Clean-Dirty` | `Create-Delete` | `Positive-Negative` |
| `Show-Hide` | `North-South` | `Writer-Reader` |  `Slender-Massive`  |
| `Bind-Free` | `Lower-Upper` | `Insert-Remove` |  `Scatter-Restore`  |
|  `New-Old`  | `Build-Erase` | `Expand-Reduce` | `Increase-Decrease` |
| `Save-Load` | `Small-Large` | `Listen-Ignore` |  `Success-Failure`  |
| `West-East` | `Throw-Catch` |                 |                     |
| `Push-Pull` | `First-Final` |                 |                     |
| `Give-Keep` | `Right-Wrong` |                 |                     |
| `Tiny-Huge` |               |                 |                     |
|  `Col-Row`  |               |                 |                     |
| `Slow-Fast` |               |                 |                     |
|  `Add-Sub`  |               |                 |                     |
| `Love-Hate` |               |                 |                     |
| `Pile-Heap` |               |                 |                     |
| `Kept-Left` |               |                 |                     |
|             |               |                 |                     |

###### END OF `OLEGEASE`
