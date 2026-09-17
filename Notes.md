When setting up on a new machine, run `cargo build`. If using NixOS, run `nix-shell -p cargo rustc --run "cargo build"`
Then run `./target/debug/generator` to generate the pages.
