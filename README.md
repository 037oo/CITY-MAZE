# CITY-MAZE
# 🧭 Maze Drawing Project

This is a simple web-based project that draws a maze using the HTML `<canvas>` element and JavaScript. It reads a set of coordinates and draws lines between them to form the structure of the maze.

## 📌 Project Description

The project displays a maze by rendering lines based on predefined coordinates. Each line segment is defined by four values: the starting point `(x1, y1)` and the ending point `(x2, y2)`.

It was created as a high school assignment.

## 🛠️ Technologies Used

- **HTML** – for the basic structure of the web page.
- **JavaScript** – to render the maze on the canvas.
- **Canvas API** – for drawing lines.

## 🧩 How It Works

- The `cord` array contains all the wall segments of the maze as coordinate pairs.
- When the page loads, the JavaScript code iterates over each set of coordinates and draws the corresponding lines on the canvas.
- The maze appears automatically without the need for user interaction.

### Example Line Definition:

```js
[2, 2, 226, 2] // Draws a line from (2, 2) to (226, 2)

🚀 How to Run the Project

    Download or clone this repository.

    Open the file index.html in any modern web browser (such as Chrome or Firefox).

    The maze should render immediately on the page.


📄 License

This project is open-source. Feel free to use, modify, and learn from it. 
