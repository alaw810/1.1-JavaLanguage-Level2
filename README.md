# 📱 Java Language – Inheritance and Interfaces: Smartphone Simulation

This Java exercise demonstrates how a class can inherit from a superclass and implement multiple interfaces. It models a basic `Smartphone` with capabilities to call, take photos, and ring an alarm.

---

## 📄 Description – Exercise Statement

Create a class `Phone` with:

- Attributes: `brand`, `model`
- Method: `call(String number)` → prints a message like:
  > "Calling 123456789..."

Create two interfaces:

- `Camera` → with method `takePhoto()` → prints:
  > "Taking a photo..."

- `Clock` → with method `alarm()` → prints:
  > "The alarm is ringing..."

Create a class `Smartphone` that:

- Inherits from `Phone`
- Implements both `Camera` and `Clock` interfaces

From the `main()` method, create a `Smartphone` object and invoke all the methods.

---

## 💻 Technologies Used

- **Java 24 (OpenJDK 24.0.1)**
- IntelliJ IDEA
- Git & GitHub

---

## 📋 Requirements

- Java SDK **24.0.1** or higher
- A Java IDE (e.g., IntelliJ IDEA, Eclipse)
- Git (optional)

---

## 🛠️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/alaw810/1.1-JavaLanguage-Level2.git

2. Open the project in IntelliJ IDEA.

3. Make sure the SDK is set to Java 24:

   * `File → Project Structure → SDKs`

---

## ▶️ How to Run

1. Open the `Main.java`.
2. Run the `main()` method.
3. You should see the following output:

```
Calling phone number 900533175
Taking a photo.
The alarm is ringing.
```

---

## 🧠 Learning Outcomes

* Learn how to implement multiple interfaces in Java
* Understand how inheritance works in combination with interfaces
* Practice separating concerns (calling, photography, alarm) into reusable interfaces

---

## 🤝 Contributions

This is a personal educational exercise.
Pull requests with improvements or suggestions are welcome.
