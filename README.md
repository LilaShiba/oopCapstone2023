# Tech Demo 🚀🌟

In this demo, you'll showcase your understanding of 3/4 pillars of OOP: Encapsulation, Inheritance, Abstraction, and Polymorphism for extra credit. You'll create a fun and interactive program and share with the class via a tech demo that demonstrates your many skills! 🎉🎓

📋🐈‍⬛ Oh, here's the [rubric](https://kyle1james.github.io/oopCapstone2023/rubric) 📋🐈‍⬛

## Getting Started 🏁

1. **Create a new Java project** in repl.it. Find the project named tech-demo-final, you can copy/paste your current project code here or use this time to start with a new idea! 🤖
2. **Choose a theme** for your tech demo. It can be anything you like, such as a zoo, a school, a video game, or even a simulated world! You may also build off of the in-class coding examples, e.g., Star Wars game and the deck of cards 🦁🏫🎮🧙
3. **Design classes** that represent the different components of your theme, using the OOP concepts you've learned. 🏗

# Demonstrating OOP Concepts 🔍

To make sure your tech demo showcases the 3ish pillars of OOP, follow these guidelines:

## Encapsulation 🔒

Create classes with private fields and use public methods (getters and setters) to access those fields. This demonstrates data hiding and ensures that the internal state of the object is protected. For example:

<details>
  <summary><strong>example</strong></summary>
  
  <pre><code>
  // Encapsulation Example
  // Shape.java
  class Shape {
    // Encapsulation 
    private float area;

    // Encapsulation
    private float perimeter;
  }

  // Main.java
  public class Main {
    public static void main(String[] args) {
      // Create a Circle object with a radius of 5.0
      Circle circle = new Circle(5.0);
    }
  }
  </code></pre>
  Extension: try to make this code work while keeping area and perimeter encapsulated
</details>





## Inheritance 👨‍👧
Create a hierarchy of classes, where child classes inherit properties and behaviors from parent classes. This will show how you can reuse code and create more specialized classes using inheritance. For example:

<details>
  <summary>example</summary>
  
  <pre><code>
  // Inheritance Example
  // Shape.java
  class Shape {
    // method to calculate the area of the shape
    public double getArea();
    
    // method to calculate the perimeter of the shape
    public double getPerimeter();
  }
  
  // Circle.java
class Circle extends Shape {
  private double radius;

  public Circle(double radius) {
    this.radius = radius;
  }
 }
  
  // Main.java
  public class Main {
    public static void main(String[] args) {
      // Create a Circle object with a radius of 5.0
      Circle circle = new Circle(5.0);
    }
  }
  </code></pre>
  Extension: try to create the get methods!

</details>


## Abstraction 🎭
Implement abstract classes or interfaces (think custom methods in a class like deck.deal()) to define common behaviors for a group of related classes. This will demonstrate how abstraction can be used to create flexible and extensible code. For example:

<details>
  <summary><strong>example</strong></summary>
  
  <pre><code>
  // Shape.java
  class Shape {
    // method to calculate the area of the shape
    public double getArea();

    // method to calculate the perimeter of the shape
    public double getPerimeter();
  }
  
  // Circle.java
  class Circle extends Shape {
    private double radius;

    public Circle(double radius) {
      this.radius = radius;
    }
  }

  // Main.java
  public class Main {
    public static void main(String[] args) {
      // Create a Circle object with a radius of 5.0
      Circle circle = new Circle(5.0);
    }
  }
  </code></pre>
  Extension: try abstraction outside of main.java
</details>




# Structuring Your Tech Demo 🏗

1. **Create a `README.md` file** in your project to explain the theme and the OOP concepts you've used. 📝
2. **Write descriptive comments** in your code to help explain the purpose of each class, method, and field. 💬
3. **Include sample input and output** in your `README.md` file to show how your program works. 📊
4. **Add fun emojis** 😄 to your `README.md` file and comments to make them more engaging and enjoyable to read! 🎨

Remember to have fun, be creative, and show off your OOP skills! Good luck, and happy coding! 🚀🌟

# Why Dark Mode 🌃🌿

Dark mode saves power, especially on devices with OLED or AMOLED displays. These displays work by lighting up individual pixels rather than using a backlight. When the background is dark or black, fewer pixels need to be lit up, which means less power is consumed. 📱💡

## Benefits for the Environment 🌍

By saving power, dark mode can help reduce the overall energy consumption of your devices. This can lead to:

- Reduced electricity usage 🏡⚡
- Lower carbon footprint 🦶🌳
- Longer battery life, which means fewer battery replacements and less electronic waste 🌐🔋

So, go ahead and switch to dark mode to save power and contribute to a greener planet! 🌃🌿🌎

Remember, every little bit helps when it comes to protecting our environment! 🤗💚

# Open Source

## 📝 Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, please open an issue or submit a pull request.

## 📄 License

This project is licensed under the [MIT License](LICENSE)

## 📧 Contact

If you have any questions or need further assistance, feel free to contact by howl-chain 🐶



