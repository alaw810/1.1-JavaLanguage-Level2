## 📄 Description – Exercise Statement

- Create a class `Phone` with attributes:
    - `brand`
    - `model`
    - A method `call(String number)` that prints:
      > "Calling [number]..."

- Create an interface `Camera` with the method `takePhoto()`, which prints:
  > "Taking a photo"

- Create another interface `Clock` with the method `alarm()`, which prints:
  > "The alarm is ringing"

- Create a class `Smartphone` that:
    - Extends the class `Phone`
    - Implements both interfaces `Camera` and `Clock`

- From the `main()` method, create a `Smartphone` object and call:
    - `call()`
    - `takePhoto()`
    - `alarm()`

This exercise demonstrates **multi-interface implementation**, **method overriding**, and **polymorphism**.

---

## 💻 Technologies Used

- Java 24
- IntelliJ IDEA (or any other Java IDE)
- Git & GitHub (optional, for version control)

---

## 📋 Requirements

- Java SDK 24 or higher
- An IDE like IntelliJ IDEA or Eclipse
- Git installed (optional)

---

## 🛠️ Installation

1. Clone the repository (if available):

   ```bash
   git clone https://github.com/alaw810/1.1-JavaLanguage-Level2.git

2. Open the project in IntelliJ IDEA:

File → Open → Select the project folder

3. Set the correct Java SDK:

File → Project Structure → SDKs → Java 24+

---

## ▶️ Execution

1. Open the Main.java file

2. Run the main() method

3. You should see output similar to:

> Calling 123456789...
 
> Taking a photo

> The alarm is ringing

--- 

## 🌐 Deployment
This is a Java console-based educational exercise and doesn't require production deployment.
If desired, you can compile and run it manually:

    ```bash
    javac *.java
    java Main

Or export it as a `.jar` file using IntelliJ IDEA.

---

## 🤝 Contributions
This is a learning exercise intended for individual academic practice.
However, pull requests with enhancements or improvements are welcome!

1. Fork the repo

2. Create a new branch (`git checkout -b feature/your-feature`)

3. Commit and push your changes

4. Open a Pull Request