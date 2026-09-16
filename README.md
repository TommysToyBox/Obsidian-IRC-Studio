# Obsidian IRC Studio

<p align="center">
  <strong>A modern development environment for mIRC scripting and IRC addon development.</strong>
</p>

<p align="center">
  Write. Analyze. Customize. Test.
</p>

<p align="center">

  <img src="https://i.ibb.co/zzqST3f/001.png" alt="Obsidian IRC Studio">

</p>

<p align="center">

<strong>Obsidian IRC Studio</strong> · <a href="#features">Features</a> · <a href="#screenshots">Screenshots</a> · <a href="#getting-started">Getting Started</a>

</p>

---

## 🌑 About

**Obsidian IRC Studio** is a standalone development environment designed specifically for creating, editing, analyzing, customizing, and testing **mIRC scripts and IRC addons**.

Instead of relying on a standard text editor and constantly switching between different applications, Obsidian brings the development workflow together into a single environment.

### The idea is simple:

**Write → Analyze → Customize → Test → Refine**

Obsidian IRC Studio is being developed as more than just a script editor. The goal is to create a complete development environment for the **mIRC scripting ecosystem**, providing developers with tools for writing scripts, finding problems, customizing addons, and testing their work.

---

## ✨ Features

### 📝 mIRC Script Editor

Obsidian provides a dedicated development environment for working with mIRC scripts.

Features include:

* mIRC-oriented syntax highlighting
* Multiple document tabs
* Script editing
* Integrated output
* Project information
* Error and diagnostic reporting
* Dedicated development workspace

The editor is designed specifically around the way mIRC scripts are written and organized.

---

### 🔎 Script Error Checker

Find problems before they make it onto an IRC network.

The built-in Script Error Checker analyzes your script and reports detected problems with useful information such as:

* Error messages
* Warning messages
* Line numbers
* Column numbers
* Diagnostic information

Instead of manually searching through hundreds or thousands of lines of script, developers can quickly identify where problems are occurring.

---

### 🧩 Pre-Built Addons

Obsidian IRC Studio includes a collection of pre-built addons that can be loaded directly into the development environment.

Current addons include:

* **3D Text**
* **Alarm**
* **Clone Scanner**
* **Flash-Nick**
* **IRCop Scan**
* **Log Viewer**
* **Mass Operations**
* **Socket Spy**
* **Stats**
* **Version Reply**

These addons provide ready-made examples as well as starting points for further development and customization.

---

### 🛠️ Addon Customization

One of the major features of Obsidian IRC Studio is the ability to customize addons through a graphical interface.

Instead of manually searching through an entire `.mrc` file to find strings, commands, labels, and other configurable values, Obsidian can identify customizable elements and present them through a structured interface.

The customization system is designed to make addon modification accessible without requiring users to understand every line of the original script.

---

### ⚙️ Advanced Customization

For developers who need more control, the Advanced Customization system exposes additional detected values within an addon.

This provides a deeper level of control over the generated script while still keeping the customization process organized.

---

### 💬 Integrated IRC Test Console

Obsidian IRC Studio includes an integrated IRC Test Console for testing scripts and addons against a live IRC connection.

The test environment provides:

* IRC server configuration
* Port configuration
* Nickname configuration
* Channel configuration
* Server output
* Channel activity
* Nick lists
* Connection status
* Message sending
* IRC event visibility

The goal is to let developers test their work without constantly switching between the development environment and an external IRC client.

---

## 🖥️ Screenshots

### 📝 Main Script Editor

The main development environment provides a dedicated mIRC script editor with syntax highlighting, document tabs, integrated output, and project information.

<p align="center">
  <img src="https://i.ibb.co/zzqST3f/001.png" alt="Obsidian IRC Studio - Main Script Editor" width="100%">
</p>

---

### 🧰 Development Tools

The Tools menu provides access to the built-in development features, including script checking, addon customization, and other utilities.

<p align="center">
  <img src="https://i.ibb.co/Fb0gQN3G/002.png" alt="Obsidian IRC Studio - Development Tools" width="75%">
</p>

---

### 🧩 Pre-Built Addons

Access a collection of ready-to-use addons directly from the IDE.

<p align="center">
  <img src="https://i.ibb.co/rGQpwmmN/003.png" alt="Obsidian IRC Studio - Pre-Built Addons" width="75%">
</p>

---

### 🔎 Script Error Checker

Run the built-in error checker to analyze the current script and identify problems with line and column information.

<p align="center">
  <img src="https://i.ibb.co/twPSfL4v/004.png" alt="Obsidian IRC Studio - Script Error Checker" width="100%">
</p>

---

## 🛠️ Addon Customization

Obsidian's addon customization system provides a guided workflow for modifying existing addons.

### Getting Started

The customization wizard provides an overview of the addon and identifies configurable elements.

<p align="center">
  <img src="https://i.ibb.co/Dg7ZfQxg/005.png" alt="Obsidian IRC Studio - Addon Customization Getting Started" width="100%">
</p>

---

### Addon Information

Review information about the addon and the elements detected by the customization system.

<p align="center">
  <img src="https://i.ibb.co/sfWX4sH/006.png" alt="Obsidian IRC Studio - Addon Information" width="100%">
</p>

---

### Messages

Customize messages and other text used by the addon.

<p align="center">
  <img src="https://i.ibb.co/RpH5FS5p/007.png" alt="Obsidian IRC Studio - Message Customization" width="100%">
</p>

---

### Commands

Customize commands used by the addon without manually searching through the script.

<p align="center">
  <img src="https://i.ibb.co/mrJyzKsP/008.png" alt="Obsidian IRC Studio - Command Customization" width="100%">
</p>

---

### Appearance

Configure appearance-related values through the graphical customization environment.

<p align="center">
  <img src="https://i.ibb.co/MD6CkkN5/009.png" alt="Obsidian IRC Studio - Appearance Customization" width="100%">
</p>

---

### Advanced Customization

Advanced users can access additional detected values and configuration options.

<p align="center">
  <img src="https://i.ibb.co/WvSQcFfK/010.png" alt="Obsidian IRC Studio - Advanced Customization" width="100%">
</p>

---

## 💬 IRC Test Console

The integrated IRC Test Console provides a dedicated environment for testing scripts and addons against an IRC server.

Configure the connection, join channels, monitor IRC activity, and interact with the server without leaving Obsidian IRC Studio.

<p align="center">
  <img src="https://i.ibb.co/1fmQ6gLF/011.png" alt="Obsidian IRC Studio - IRC Test Console" width="100%">
</p>

---

## 🎯 Project Goals

Obsidian IRC Studio is being built around several core goals.

### Make mIRC scripting easier

Provide a dedicated development environment instead of relying solely on a generic text editor.

### Make errors easier to find

Give developers useful diagnostic information and make script problems easier to locate.

### Make addons easier to customize

Provide graphical tools for modifying addons without requiring developers to manually search through large scripts.

### Make testing easier

Provide an integrated IRC testing environment so developers can test their work without constantly switching applications.

### Build a complete development environment

The long-term goal is to bring the major parts of the mIRC addon development workflow together into one application.

---

## 🏗️ Development Philosophy

Obsidian IRC Studio follows a simple development workflow:

```text
              ┌─────────────┐
              │    WRITE    │
              │    SCRIPT   │
              └──────┬──────┘
                     │
                     ▼
              ┌─────────────┐
              │   ANALYZE   │
              │    SCRIPT   │
              └──────┬──────┘
                     │
                     ▼
              ┌─────────────┐
              │  CUSTOMIZE  │
              │    ADDON    │
              └──────┬──────┘
                     │
                     ▼
              ┌─────────────┐
              │    TEST     │
              │     IRC     │
              └──────┬──────┘
                     │
                     ▼
              ┌─────────────┐
              │   REFINE    │
              │    CODE     │
              └─────────────┘
```

The purpose is to reduce the amount of time developers spend jumping between unrelated tools.

---

## 🧰 Technology

Obsidian IRC Studio is a native Windows desktop application built around the **.NET / Windows Forms** ecosystem.

The project focuses on:

* Native Windows desktop functionality
* A familiar IDE-style interface
* mIRC scripting support
* IRC connectivity
* Script analysis
* Addon customization
* Integrated development tools

---

## 💻 Getting Started

### Requirements

To build Obsidian IRC Studio from source, you will need:

* Windows
* Visual Studio
* A compatible .NET SDK
* Internet connectivity for IRC testing

### Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Obsidian-IRC-Studio.git
```

Then open the solution in Visual Studio and build the project.

> Replace `YOUR-USERNAME` with your GitHub username.

---

## 📂 Project Structure

The project is organized around the major components of the development environment.

```text
Obsidian IRC Studio
│
├── Editor
│   └── mIRC script editing
│
├── Addons
│   └── Pre-built addon library
│
├── Customizer
│   └── Addon customization tools
│
├── IRC
│   └── IRC testing environment
│
├── Screenshots
│   └── Project screenshots
│
└── README.md
```

The exact project structure may evolve as development continues.

---

## 🚧 Project Status

**Active Development**

Obsidian IRC Studio is currently under active development.

The application, scripting engine, customization tools, and IRC testing environment are continuing to evolve.

Features and interfaces may change as development progresses.

---

## 🔮 Planned Development

Future development may include improvements to:

* mIRC syntax support
* Syntax highlighting
* Code completion
* Script analysis
* Error detection
* Script debugging
* Addon management
* Addon templates
* Project management
* IRC event testing
* WYSIWYG development tools
* Customization tools
* Script generation
* Additional pre-built addons

---

## 🤝 Contributing

Contributions, ideas, bug reports, and feature suggestions are welcome.

If you find a problem or have an idea that could improve Obsidian IRC Studio:

1. Open an issue.
2. Describe the problem or proposed feature.
3. Include screenshots or example scripts when useful.
4. Provide as much information as possible to reproduce the issue.

Pull requests are also welcome as the project develops.

---

## 🐛 Bug Reports

When reporting a bug, please include:

* Windows version
* Visual Studio version if building from source
* Obsidian IRC Studio version or commit
* Steps to reproduce the issue
* Expected behavior
* Actual behavior
* Screenshots when applicable
* Relevant script or error information

The more information provided, the easier it is to reproduce and fix the problem.

---

## 🌐 Website

Learn more about Obsidian IRC Studio and other projects:

**Tommy's Toybox**

https://tommystoybox.netlify.app/

---

## 👤 Author

**Tommy McLoughlin**

Obsidian IRC Studio is developed as part of the projects created under **Tommy's Toybox**.

---

## 📜 License

License information will be added as the project develops.

---

## 🌑 Obsidian IRC Studio

<p align="center">

<strong>Write scripts.</strong><br> <strong>Find problems.</strong><br> <strong>Customize addons.</strong><br> <strong>Test on IRC.</strong>

</p>

<p align="center">

<code>OBSIDIAN // IRC SCRIPTING DEVELOPMENT ENVIRONMENT</code>

</p>

<p align="center">

Built for developers who still believe IRC isn't dead.

</p>
