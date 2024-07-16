# Rust Todo App

A simple command-line Todo application in Rust.

## Features

- Add, view, complete, and delete tasks
- Tasks saved to `tasks.json` for persistence

## Setup

1. **Install Rust:** [Install Rust](https://www.rust-lang.org/tools/install)
2. **Clone the Repo:**

    ```bash
    git clone https://github.com/Murugan-Bounteous/rust-todo-app.git
    cd rust-todo-app
    ```

3. **Build:**

    ```bash
    cargo build --release
    ```

## Usage

1. **Run:**

    ```bash
    cargo run
    ```

2. **Follow Prompts:**

    - `1` to Add a task
    - `2` to View tasks
    - `3` to Complete a task
    - `4` to Delete a task
    - `5` to Save and exit

## Data

- Tasks are saved in `tasks.json`
- Automatically loaded on start

## License

MIT License
