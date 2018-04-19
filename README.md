## Rust Game

Work in progress. Some gameplay ideas:

* Turn-based, isometric battles in randomly generated environments
* D&D/OGL type character creation
* Randomly generated maps, cities, quests, etc.
* Will take some pieces of the roguelike formula

## Development

Check out [cargo](https://doc.rust-lang.org/cargo/) for more information and [rustfmt](https://github.com/rust-lang-nursery/rustfmt) for automatic code formatting.

* `cargo check` to check you code to ensure it compiles but not create an executable
* `cargo build` to build the application in debug mode
* `cargo run` to build and run the application
* `cargo build --release` to build the application in release mode
* `cargo fmt` once rustfmt is installed to automatically format code
* `cargo doc --open` to open docs of all installed crates locally

### Automatic Code Checking on File Changes

On mac, install `watchexec` with homebrew (`brew install watchexec`). Then in the project directory run:

`watchexec -r -w src  "cargo check"`
