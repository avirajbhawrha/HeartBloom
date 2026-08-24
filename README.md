# 💖 HeartBloom

A colorful rainbow heart animation built with Python's Turtle Graphics — combining math, color, and motion into a beginner-friendly generative art project.

---

## ✨ Overview

HeartBloom draws a glowing, animated heart shape using parametric equations, then decorates it with rainbow-colored lines and sparkling star patterns. It's a fun way to explore how simple math and a bit of Python can create eye-catching visuals.

---

## 🌟 Features

- ❤️ Mathematically generated heart shape using parametric equations
- 🌈 Randomized rainbow colors on every line drawn
- ✨ Sparkling star-like decorations along the heart's outline
- ⚡ Optimized rendering with `screen.tracer(0)` for smooth, fast drawing
- 🐍 Simple, readable code — great for Python and Turtle Graphics beginners

---

## 🧰 Built With

- **Python 3**
- **Turtle Graphics** — for drawing and animation
- **Math module** — for the heart's parametric equations
- **Random module** — for generating rainbow colors

---

## 📁 Project Structure

```
HeartBloom/
│
├── heart_animation.py
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/avirajbhawrha/HeartBloom.git
```

### 2. Move into the project folder
```bash
cd HeartBloom
```

### 3. Run the animation
```bash
python heart_animation.py
```

---

## ⚙️ How It Works

1. Opens a Turtle graphics window with a black background.
2. Calculates points along the heart's outline using the parametric heart equation.
3. Draws colorful lines from the center of the screen out to each point on the heart.
4. Adds small star-shaped flourishes at select points along the outline.
5. Renders the final rainbow heart on screen.

---

## 📐 The Heart Equation

The heart shape comes from the classic parametric equations:

```python
x = 16 * sin(t) ** 3
y = 13 * cos(t) - 5 * cos(2*t) - 2 * cos(3*t) - cos(4*t)
```

As `t` sweeps through a full rotation, these equations trace out the familiar heart curve.

---

## 🖼️ Output

Running the script produces a vividly colored heart outline — rainbow-hued lines radiating from the center, accented with small sparkling stars, all set against a black background.

---

## 📋 Requirements

- Python 3.x
- No external libraries needed (Turtle, Math, and Random are all part of the standard library)

Don't have Python? Grab it here: https://www.python.org/downloads/

---

## 🔮 Roadmap

- [ ] Animate the drawing process in real time
- [ ] Export the final artwork as an image file
- [ ] Let users pick their own custom color palette
- [ ] Add background music for a full audiovisual effect
- [ ] Add a simple GUI for customization options

---

## 🤝 Contributing

Contributions, ideas, and feature requests are welcome! Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is open source and available for personal and educational use.
