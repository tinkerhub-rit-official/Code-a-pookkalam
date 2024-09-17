# 🌸 Is it Your First Time Participating in Code-a-Pookkalam? 🌸

If this is your first time participating in **Code-a-Pookkalam**, welcome! Don’t worry if you’re new to coding or unsure about how to create your own Pookkalam using code — we’re here to help. This guide will walk you through the basics and get you started.

## 🎨 Use Any Language or Platform

In **Code-a-Pookkalam**, you are free to use any programming language or platform that you are comfortable with to design your Pookkalam. However, if you are a **beginner**, we recommend starting with one of these two beginner-friendly options:

### 1. **p5.js (JavaScript)**

p5.js is a JavaScript library that makes it easy to create graphics and interactive visuals in your browser. It’s an excellent choice for beginners because:
- You can see the output immediately in your browser.
- The syntax is simple and beginner-friendly.
- It’s highly versatile and can be used for creative coding.

You can get started with p5.js online without installing anything by visiting the [p5.js Web Editor](https://editor.p5js.org/).

Example: A simple flower using p5.js:

```javascript
function setup() {
  createCanvas(400, 400);
  background(255);
  translate(width / 2, height / 2);
  for (let i = 0; i < 10; i++) {
    ellipse(0, 0, 150, 50);
    rotate(PI / 5);
  }
}
```

### 2. **Python Turtle**

Python’s Turtle library is another beginner-friendly option that allows you to create graphics by controlling a virtual "turtle." It’s intuitive and great for creating patterns like Pookkalams.

You can use Python Turtle if:
- You are more familiar with Python.
- You want a simple and easy-to-learn library for drawing.

Example: A simple flower using Python's Turtle:

```python
import turtle

t = turtle.Turtle()
t.speed(0)

for i in range(36):
    t.circle(100)
    t.right(10)

turtle.done()
```

### 3. **Joy**

Joy is a tiny creative coding library in Python, made by FOSS United India
See how to use Joy: https://github.com/fossunited/joy/blob/main/README.md

### Other Languages

You are free to use any language that supports graphical output, such as:
- **JavaScript (HTML5 Canvas)**
- **Java (AWT/Swing)**
- **C++ (Graphics libraries)**
- **Processing**
- Or any other platform...

## 🔗 Submitting Your Code via GitHub

Once you’ve created your Pookkalam design using the language of your choice, the next step is to submit it. For this competition, **submissions are done through GitHub**. Don’t worry if you’re new to GitHub — here’s a quick guide to help you get started.

### Step 1: Create a GitHub Account

If you don’t already have a GitHub account, head over to [GitHub.com](https://github.com) and sign up for a free account.

See how: https://youtu.be/QUtk-Uuq9nE?si=ECSPHNIEDmu9IFME

### Step 2: Create a New Repository

1. After logging in, click on the **+** icon in the top right corner and select **New repository**.
2. Name your repository `Code-a-Pookkalam-2024`.
3. Choose the repository as **Public** so that we can access your submission.
4. Add a brief description like "My Code-a-Pookkalam submission."
5. Optionally, initialize the repository with a `README.md` file.

### Step 3: Upload Your Code

1. If you are familiar with Git, you can use `git` commands to push your code to GitHub.
2. Alternatively, you can manually upload your code by:
   - Clicking on **Add file** in your repository.
   - Selecting **Upload files** and then dragging your code and any images into the file uploader.
3. Don’t forget to include a screenshot of your final output in your repository.

See how: https://youtu.be/P75e8DgOxn8?si=FK7ptPAWEaWELMvu

### Step 4: Submit Your Repository Link

Once your code is uploaded to GitHub, submit the link to your repository using the form provided on the competition page.

Example format for the link:
```
https://github.com/YourUsername/Code-a-Pookkalam-2024
```

## 💡 Need Help?

If you’re stuck or need help getting started with coding, feel free to reach out to the TinkerHub RIT community for assistance. We’re here to support you!

---

We hope you have a great time participating in **Code-a-Pookkalam**. Whether you’re a seasoned coder or a beginner, this competition is all about having fun and celebrating creativity. Happy coding!
