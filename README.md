<div align="center">

# Rusting-Rust on Solana 🦀

<br/>

<div>
  <img src="https://img.shields.io/badge/Solana-9945FF?style=for-the-badge&logo=solana&logoColor=white" alt="Solana">
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Anchor-000000?style=for-the-badge&logo=anchor&logoColor=white" alt="Anchor">
</div>

<br/>

**A Solana program developed with Rust and Anchor, designed for seamless building and testing in the Solana Playground environment.**

<p>
  <a href="#-about-the-project">About</a> •
  <a href="#-key-features">Features</a> •
  <a href="#-getting-started">Getting Started</a> •
  <a href="#-usage">Usage</a> •
  <a href="#-contributing">Contributing</a>
</p>

</div>

## 🌟 About The Project

"Rusting-Rust" is a foundational Solana program that demonstrates key concepts of building on-chain applications. The program is written in Rust using the Anchor framework, which simplifies Solana development by providing a more structured and secure way to write smart contracts. This project is specifically configured to be used with Solana Playground, an in-browser IDE that allows for rapid development, testing, and deployment without requiring a local setup.

### 🛠️ Built With

This project leverages a modern, blockchain-focused technology stack.

* **Blockchain:** [Solana](https://solana.com/)
* **Smart Contract Language:** [Rust](https://www.rust-lang.org/)
* **Framework:** [Anchor](https://www.anchor-lang.com/)
* **Client-Side Scripting:** [TypeScript](https://www.typescriptlang.org/)
* **Development Environment:** [Solana Playground](https://beta.solanaplayground.io/)

## ✨ Key Features

* **Anchor Framework:** Utilizes Anchor for safer, more modular, and easier-to-write Solana programs.
* **Solana Playground Ready:** Pre-configured to be imported, built, and tested directly in the Solana Playground web IDE.
* **Client Interaction:** Includes a TypeScript client script for easy interaction with the on-chain program.
* **Clear & Modern Code:** The Rust program is well-structured and serves as a great starting point for more complex Solana projects.

## 🚀 Getting Started

The primary way to use this project is through the Solana Playground.

### Prerequisites

* A modern web browser (like Chrome, Firefox, or Brave).
* The [Phantom](https://phantom.app/) wallet browser extension (or another Solana-compatible wallet).

### Installation & Setup

1.  **Open Solana Playground:**
    Navigate to [https://beta.solanaplayground.io/](https://beta.solanaplayground.io/).

2.  **Import the Repository:**
    * In the Solana Playground explorer, click on the import icon (a folder with an arrow).
    * Paste the URL of your GitHub repository: `https://github.com/neutron420/rusting-rust`.
    * Click **Import**.

3.  **Build the Program:**
    * Once imported, open the terminal in Solana Playground (`View > Terminal`).
    * Run the build command:
        ```sh
        build
        ```

4.  **Deploy the Program:**
    * After a successful build, deploy the program to a local or devnet cluster:
        ```sh
        deploy
        ```

## Usage

After deploying the program, you can interact with it using the provided TypeScript client.

1.  **Navigate to the Client Script:**
    In the Solana Playground explorer, open `client/client.ts`.

2.  **Run the Client:**
    * Click the **"Run"** button in the top-right of the editor, or use the terminal:
        ```sh
        run
        ```
    * The script will execute, calling the functions defined in your on-chain program. Check the terminal for output and transaction details.

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📜 License

Distributed under the MIT License.

Project Link: [https://github.com/neutron420/rusting-rust](https://github.com/neutron420/rusting-rust)
