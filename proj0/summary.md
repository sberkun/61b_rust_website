---
parent: "Project 0: 2048"
title: Summary and Deliverables
nav_order: 2
---


## Assignment Overview

You will implementing `tilt` and `game_over` in `game.rs`.

## Running the Project

To test your code, run `cargo test`.


To run the project, you should open two terminals:
 - In one terminal, run `wasm-pack build --target web` to compile your code.
 - In the other terminal, run `python3 -m http.server` to start the server. You can leave this server running while you work.
 - Go to [http://0.0.0.0:8000/](http://0.0.0.0:8000/) (or whichever address the server says to go to) in your browser to view the project.

Whenever you make changes to the code, rerun `wasm-pack build --target web`, and **hard-refresh** the browser page.



## Submitting Your Code

Before submitting your code, make sure to:
 - Run `cargo clippy` and fix any warnings that appear.
 - Run `cargo fmt` to format your code according to the Rust style guidelines.
 - Commit and push your code to your repository.

Then, submit your code to the [Gradescope assignment](https://cheese.com/).
