# OLEGEASE
> general information about my personal projects andor applications

## Repositories

- **`template`**: _template repository with minimal structure of future projects, base template for other templates_
- **`hello-mxx-world`**: _exemplar of `C++23` Standard Modules CMake application_
- **`hello-cxx-world`**: _exemplar of `C++17` Standard Headers CMake application_
- **`hello-web-world`**: _exemplar of `JavaScript NodeJS (mjs)`, Postgres and Web `(JS, HTML and CSS)` application_
- **`hello-asm-world`**: _exemplar of Assembly `NASM x86-64` application_
- **`ease-git`**: _simple C++ application for git commands wrapper, at start only cloning repos based on current directory path_

## Organizations

- **`forkease`**: _fork repositories to my personal andor my organization andor any other organization in `{Org Alias}-{Original Repo Name}`
- **`soneight`**: _`C++17` oriented `3D OpenGL` graphics related projects_
- **`motwonil`**: _`C++23+` only standard modules `3D Vulkan` graphics related projects (pending)_
- **`nethreed`**: _`Javascript NodeJS` web `2D WebGL` graphics related projects (pending)_
- **`asevenly`**: _`Assembly NASM x64 and C90 C` language standard `2D Software Rendering` graphics related projects (pending)_

### Son 8

- libraries: _using CMake required version in range `3.8..3.27`, lower minimum for C++17 standard available, upper maximum because of next version kind of supports C++20 modules_
- applications: _using CMake required version in range `3.20..3.27`, lower minimum for configure and build presets, upper maximum same as libraries_

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

- `hub`: _`github` clone_
- `berg`: _`codeberg` clone_

## Licensing

- `libraries`: _`[Apache License 2.0](https://spdx.org/licenses/Apache-2.0.html)`_
- `applications`: _`[GNU Affero General Public License v3.0 or later](https://spdx.org/licenses/AGPL-3.0-or-later.html)`_

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
  - `camelCaseUndercored_`: _private data members_

- Formatting:
  - Always insert spaces after curly `{`, round `(`, angle `<` opening brackets and before curly `}`, round `)`, angle `>` closing brackets but not before or after array opening `[` or closing `]` brackets
