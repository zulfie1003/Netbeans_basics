
# 📌 Project 1

A Java application built using **Apache Ant**, managed in **NetBeans**.
It includes an Ant build script (`build.xml`) and a manifest (`manifest.mf`) for JAR execution.

---

## 📜 Description

Project 1 demonstrates a Java application that can be built, tested, and run using Ant.
The build script is set up with customizable hooks for compilation, JAR creation, and post-build tasks.
The manifest file specifies the entry point of the application.

---

## ⚙️ Requirements

* **Java JDK** 8 or later
* **Apache Ant** 1.10 or later
* **NetBeans IDE** (optional, but recommended for easier project management)

---

## 🛠️ Build & Run

**Build the project**:

```sh
ant clean build
```

**Run the project (via Ant)**:

```sh
ant run
```

**Run the JAR directly**:

```sh
java -jar dist/Project_1.jar
```

> The `manifest.mf` contains the `Main-Class` entry so you can execute the JAR without specifying the class name manually.

---

## 📂 Project Structure

```
Project_1/
│── build.xml        # Ant build script (controls build, run, clean, etc.)
│── manifest.mf      # Manifest file (defines Main-Class and metadata)
│── src/             # Java source code
│── nbproject/       # NetBeans project files
│── dist/            # Output JAR file after build
```

---

## ✨ Customization

* **build.xml** → Add pre/post compile actions, JAR modifications, or external tool calls.
* **manifest.mf** → Change `Main-Class` if your entry point class changes.
* **nbproject/** → NetBeans-specific configuration for IDE builds.

---

## 📄 License

This project is for educational/demo purposes.
You may modify and use it freely.

---


