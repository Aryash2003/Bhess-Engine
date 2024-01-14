# Bhess Engine : Bitboard Chess Engine

This is a simple chess engine implemented in Rust, utilizing bitboards for efficient move generation and board representation.

## Features

- **Bitboard Representation:** Efficient board representation using bitboards for pieces.
- **Move Generation:** Generate legal moves for a given position.
- **Quiescence search:** Implement the Quiescence search algorithm for efficient search with iterative deepning **[TODO]**
- **UCI Support:** Follows the Universal Chess Interface (UCI) standard for communication with GUIs. **[TODO]**

## Getting Started

### Prerequisites

- [Rust](https://www.rust-lang.org/) installed on your machine.

### Building and Running

1. Clone the repository:

   ```bash
   git clone https://github.com/Unic-X/Bhess-Engine.git
   cd Bhess-Engine
2. Build and run the chess engine:
    ```bash
    cargo build --release   
    cargo run
    ```
### Usage
Run the executable generated by the build.
Use a UCI-compatible chess GUI (e.g., Arena) to communicate with the engine.

## Contributing
Contributions are welcome! Feel free to open issues or pull requests for improvements, bug fixes, or new features.
