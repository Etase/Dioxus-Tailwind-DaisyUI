# Desktop Development Template with Dioxus, TailwindCSS, and DaisyUI

This is a simple template for desktop application development, combining **Dioxus**, **TailwindCSS**, and **DaisyUI** to help you quickly build modern, responsive, and customizable user interfaces.

---

## **Features**
- 🚀 **Dioxus 0.6.2** for fast, efficient, and safe Rust-based UI development.
- 🎨 **TailwindCSS 4.0.0** for utility-first CSS design.
- 🌸 **DaisyUI 5.0.0-beta.2** for pre-styled UI components, reducing boilerplate CSS.

---

## **Prerequisites**

Before getting started, ensure you have the following tools installed:

1. [Install Dioxus](https://dioxuslabs.com/learn/0.6/getting_started/)
   - Follow the guide to set up `dx` CLI and configure your Rust environment.

2. [Install npm](https://www.npmjs.com/)
   - Node.js and npm are required for managing and building TailwindCSS.

---

## **Toolchain**

This template is built with the following versions:
- **Dioxus**: `0.6.2`
- **TailwindCSS**: `4.0.0`
- **DaisyUI**: `5.0.0-beta.2`

We recommend keeping your toolchain versions consistent to avoid compatibility issues. See the provided `package.json` and `Cargo.toml` for additional details.

---

## **Getting Started**

### **1. Install Dependencies**

Run the following commands to set up the project dependencies:

```bash
# Install Rust dependencies
cargo build

# Install TailwindCSS and DaisyUI
npm install
```
### **2. Serve Your App**
To start developing, follow these steps:

Build CSS: Run TailwindCSS in watch mode to compile your CSS:

```bash
npx tailwindcss -i ./input.css -o ./assets/tailwind.css --watch
Serve Your App: Run the Dioxus development server in another terminal:
```
```bash
dx serve
```

## **Directory Structure**
```graphql
.
├── src/                   # Source code for the Dioxus application  
├── assets/                # Static assets such as compiled CSS, images, and other resources  
├── node_modules/          # Dependencies installed via npm  
├── input.css              # TailwindCSS input file for styling  
├── package.json           # npm configuration file, including dependencies and scripts  
├── Cargo.toml             # Rust project configuration and dependencies  
├── Dioxus.toml            # Dioxus-specific configuration and dependencies  
└── README.md              # Project documentation and instructions  
```
## **Contributing**
Contributions are welcome! If you encounter issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

## **License**
This project is licensed under the MIT License.

