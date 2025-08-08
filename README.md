# Auth API - Rust with Actix Web

This project is a simple **authentication API** built using **Rust** and the **Actix Web** framework. The API allows users to **sign up** and **log in** using their **username** and **password**. Passwords are securely hashed using the **bcrypt** hashing algorithm before being stored.

## Features

- **Signup**: Users can register with a **username** and **password**. The password is hashed and stored securely.
- **Login**: Users can log in by providing their **username** and **password**. The password is verified against the stored hashed password.

## Technologies Used

- **Rust**: A systems programming language focused on performance and safety.
- **Actix Web**: A powerful, actor-based framework for building concurrent applications in Rust.
- **bcrypt**: A hashing algorithm to securely store passwords.
- **Serde**: A framework for serializing and deserializing Rust data structures.
- **Mutex**: A synchronization primitive to safely share data between threads.

## Setup

### Prerequisites

Before running this project, ensure that you have **Rust** and **Cargo** installed. You can install Rust by following the instructions on [Rust's official website](https://www.rust-lang.org/).
