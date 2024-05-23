# rust-paste-bin

It is a simple, high-performance Pastebin clone written in Rust. This utility allows users to share text snippets easily by creating unique links for each paste. Built using Rust and Actix-web, it ensures speed and safety, making it an ideal solution for sharing content over the web.

## Features

- Quick and easy text sharing
- Generates unique links for each paste
- Minimalist web interface
- Secure storage using SQLite

## Installation

To install rust-paste-bin, you need to have [Rust](https://www.rust-lang.org/) installed. You can then build the project using Cargo:

```sh
git clone https://github.com/Quinos2003/rust-paste-bin.git
cd rust-paste-bin
cargo build --release
```

## Usage

After building the project, you can use the `rust-paste-bin` binary to share text snippets.

### Run the server

```sh
./target/release/rust-paste-bin
```

### Access the Paste Bin

Open your browser and go to `http://localhost:8080` to access the paste bin interface.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request on GitHub.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
