<p align="center">
  <strong>Rust TUI for searching all known skins in SA faster!</strong>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/bd3f817d-a4a4-4f47-b210-93e4fcdc5f49" alt="demo">
</p>

## Installation

Option 1: [Install - pola.exe](https://github.com/Sethispr/pola/releases/tag/v0.1.1-beta)

Option 2: Install the latest stable versions of [Rust](https://www.rust-lang.org/tools/install) and [Git](https://git-scm.com/downloads/win) first.

1. Clone the repository:
   ```bash
   git clone https://github.com/sethispr/pola
   cd pola
   ```

2. Run the application
   ```bash
   cargo run --release
   ```

Option 3: You can also install the `pola` package directly using Cargo:

1. Install the package
   ```bash
   cargo install pola --locked
   ```

2. Run the application
   ```bash
   pola
   ```

<img src="https://img.shields.io/crates/d/pola" alt="Crates.io Download Badge">

https://crates.io/crates/pola

> [!TIP]
> If installing isn't your thing, feel free to look at the [Online Demo](https://sethispr.github.io/pola) or [Skin List](https://github.com/Sethispr/pola/blob/main/skins.md)

## Cheat Sheet

<table>
<tr>
<td>

<details>
<summary>Tags List</summary>

<p align="center">
  <img src="https://github.com/user-attachments/assets/2e8b5a87-2ce7-4f41-b6f0-03c8d08c161f" alt="demo" width="596">
</p>

| Tag                   | Description                         | Tag                   | Description                         |
|-----------------------|-------------------------------------|-----------------------|-------------------------------------|
| <kbd>Event</kbd>      | Event skins                         | <kbd>Bundle</kbd>     | Bundle skins                        |
| <kbd>Code</kbd>       | Code-redeemed skins                 | <kbd>Launch</kbd>     | Skins obtained from game launch     |
| <kbd>Case</kbd>       | Case skins                          | <kbd>Red</kbd>        | Red skin rarity                     |
| <kbd>Pink</kbd>       | Pink skin rarity                    | <kbd>Teal</kbd>       | Teal skin rarity                    |
| <kbd>2022</kbd>       | 2022 skins                          | <kbd>2023</kbd>       | 2023 skins                          |
| <kbd>2024</kbd>       | 2024 skins                          | <kbd>2025</kbd>       | 2025 skins                          |
| <kbd>Valentine</kbd>  | Valentine case skins                | <kbd>Birthday</kbd>   | Birthday case skins                 |
| <kbd>Easter</kbd>     | Easter case skins                   | <kbd>Summer</kbd>     | Summer case skins                   |
| <kbd>Halloween</kbd>  | Halloween case skins                | <kbd>Christmas</kbd>  | Christmas case skins                |
| <kbd>Exquisite</kbd>  | Exquisite case skins                | <kbd>Animal</kbd>     | Skins from the Animal case          |
| <kbd>Camouflage</kbd> | Skins from the Camouflage case      | <kbd>Future</kbd>     | Skins from the Future case          |
| <kbd>Material</kbd>   | Skins from the Material case        | <kbd>Nature</kbd>     | Skins from the Nature case          |
| <kbd>Pattern</kbd>    | Skins from the Pattern case         | <kbd>Refined</kbd>    | Skins from the Refined case         |
</details>

<details>
<summary>Keybinds</summary>

| Bind                | Description                    | Bind                       | Description                     |
|---------------------|--------------------------------|----------------------------|---------------------------------|
| <kbd>ctrl+h</kbd>   | Show help                      | <kbd>▲</kbd> <kbd>▼</kbd>  | Navigate results                |
| <kbd>►</kbd>        | Accept suggestion              | <kbd>tab</kbd>             | Cycle suggestions               |
| <kbd>home/end</kbd> | Go to first last result        | <kbd>ctrl+d</kbd>          | Toggle detailed view            |
| <kbd>ctrl+l</kbd>   | Clear search input             | <kbd>esc</kbd>             | Close TUI/Help                  |
| <kbd>ctrl+y</kbd>   | Redo                           | <kbd>ctrl+z</kbd>          | Undo                            |

</details>

</td>
</tr>
</table>
