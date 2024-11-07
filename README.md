# Flue Lang

Flue Lang is a functional programming language designed to provide a smooth, pragmatic, and simple development experience. Inspired by Ruby, Python, Go, TypeScript, Elixir, and F#, Flue Lang combines an accessible syntax with strong typing and security, making it ideal for agile development and maintainable projects.

## Key Features

- **Functional and Fluent Syntax**: Focused on readability and simplicity.
- **Static and Strong Typing**: With type inference, similar to Go.
- **Immutability and Data Safety**: Inspired by functional programming concepts.
- **Multi-Purpose**: Suitable for a variety of use cases, with a focus on web development.
- **Cross-Platform**: Designed to work seamlessly across different platforms.
- **Transpiled to Go**: Flue Lang code is converted into Go, leveraging the Go ecosystem for final compilation and execution.

For complete syntax details and language features, please refer to the [Flue Lang Documentation](https://flue.gitbook.io/flue-lang).

## Installing the Flue Lang Compiler

### Prerequisites

- **Go**: Make sure you have Go installed on your system. [Go Installation Guide](https://golang.org/doc/install).

### Installation Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/FlueLang/Flue
   cd Flue
   ```

2. Install dependencies:

    ```bash
    go mod tidy

    ```

3. Build the Flue Compiler:
    ```bash
    go build -o flue
    ```

This will create an executable named `flue` in the current directory.

## Using the Flue Lang Compiler

### Compiling a Program

Once installed, you can compile Flue Lang files with the following command:

```bash
./flue <path_to_file>.flue
```

For example:

```bash
./flue examples/main.flue
```

The compiler will transpile the Flue Lang code into Go code, which can then be compiled and run.

## Running the Generated Code

The compiler generates an equivalent Go file. You can compile and run this Go file as follows:

```bash
go run <generated_go_file>.go
```

### Full Example

Suppose you have a file `main.flue`:

```flue
fun main() {
    writeln("Hello, Flue!")
}
```

1. Transpile the file to Go:

    ```bash
    ./flue main.flue
    ```

2. Compile and run the generated Go file:

    ```bash
    go run main.go
    ```

    Expected output:
    ```
    Hello, Flue!
    ```

## Documentation

For complete details on Flue Lang's syntax, features, and usage, please refer to the official [Flue Lang Documentation](https://flue.gitbook.io/flue-lang).

## Contributing

Flue Lang is an open-source project in active development, and contributions are welcome! If you'd like to contribute, please feel free to open an issue or a pull request with improvements or bug fixes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Fun Fact

Flue Lang is a Brazilian project created with the assistance of ChatGPT. The language's development reflects a unique blend of cultural inspiration and modern AI-driven support.

Thank you for exploring Flue Lang! We’re excited to have you on board.
