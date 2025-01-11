<h1 align="center">Bluetooth Controller </h1>

<br>
<div align="center">
<img src="src/Resources/Bluetooth.gif" width="300">
</div>
<br>

<p align="center">
        <img src="https://img.shields.io/github/created-at/cusaldmsr/Bluetooth-Controller"/>
        <img src="https://img.shields.io/github/commit-activity/m/cusaldmsr/Bluetooth-Controller"/>
        <img src="https://img.shields.io/github/forks/cusaldmsr/Bluetooth-Controller"/>
        <img src="https://img.shields.io/github/stars/cusaldmsr/Bluetooth-Controller"/>
        <img src="https://img.shields.io/github/watchers/cusaldmsr/Bluetooth-Controller"/>
</p>

<p align="center">
  
This repository contains a simple Bluetooth controller application that transmits four signals (`1`, `2`, `3`, and `4`) via Bluetooth. 

</p>

<p align="center">
  
  The application also supports keyboard controls to send these signals using the `W`, `S`, `A`, and `D` keys.
</p>

## Features

- **Signal Transmission**: Sends four distinct signals (`1`, `2`, `3`, `4`) over Bluetooth.
- **Keyboard Controls**:
  - `W` key: Signal `1`
  - `S` key: Signal `2`
  - `A` key: Signal `3`
  - `D` key: Signal `4`
- **Java-Based Implementation**: Developed using Java with JDK 17.

## Prerequisites

- Java Development Kit (JDK) 17 installed.
- A Bluetooth-enabled device for testing.
- A Bluetooth receiver capable of recognizing the transmitted signals.

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/cusaldmsr/Bluetooth-Controller.git
cd Bluetooth-Controller
```

### Compile the Code

Ensure you have JDK 17 installed and properly configured in your environment.

```bash
javac -d out src/GUI/Controller.java
```

### Run the Application

Execute the compiled Java application:

```bash
java -cp out GUI.Controller.Main
```

### Keyboard Controls
Use the following keyboard keys to send signals:
- `W` -> Sends signal `1`
- `S` -> Sends signal `2`
- `A` -> Sends signal `3`
- `D` -> Sends signal `4`

## File Structure
```
Bluetooth Controller/
├── src/
│   └── GUI/
│   │   ├── Controller.java
│   │   ├── BluetoothController.java
│   │   └── Utils.java
│   └── Resources/
│       ├── Bluetooth.gif
│       └── bluetooth.svg
├── Lib/
│   ├── Bluetooth.jar
│   └── flatlaf-3.5.1.jar
├── README.md
└── LICENSE
```

## Technologies Used
- Java (JDK 17)
- Bluetooth communication protocols

## Contribution
Contributions are welcome! Feel free to fork this repository and submit a pull request.

### Steps to Contribute
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch-name
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Your commit message"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-branch-name
   ```
5. Open a pull request on GitHub.


## Author
[Kusal Damsara](https://github.com/cusaldmsr)

Feel free to open an issue if you have any questions or suggestions!
