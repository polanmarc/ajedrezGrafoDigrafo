# ♟️ Directed Chess Graph

Interactive web application that represents the movements of different chess pieces using a **directed graph**. Each square on the chessboard acts as a node, and each legal movement of the selected piece is represented as a directed edge.

🔗 **Live demo:**
You can try the project by visiting:
https://ajedrez-grafo-digrafo.vercel.app/

---

## 📌 Project Description

This project combines concepts from **graph theory**, **chess**, and **interactive data visualization** to show how chess piece movements can be modeled on an 8x8 board.

The main goal is to visually represent a **digraph**, where:

* Each chessboard square is a **node**.
* Each possible movement of a piece is a **directed edge**.
* The edge direction indicates the movement direction.
* The user can select different pieces and observe how the graph structure changes.

---

## 🚀 Main Features

* Full chessboard visualization with 64 nodes.
* Representation of movements using directed graphs.
* Selection of different chess pieces:

  * Knight
  * King
  * Rook
  * Bishop
  * White pawn
* Dynamic calculation of the number of directed edges.
* Interactive mode to display only the movements from a selected square.
* Full view mode to display all graph edges.
* Responsive interface with a sidebar configuration panel.
* Zooming and panning over the graph.
* Visual design inspired by a traditional chessboard.

---

## 🧠 Concepts Applied

This project helps visualize and work with concepts such as:

* Directed graphs.
* Nodes and edges.
* Out-degree of a node.
* Mathematical modeling of movements.
* Graphical representation of discrete structures.
* Paths and relationships between board positions.

---

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript**
* **Tailwind CSS**
* **Vis.js / vis-network**
* **Vercel** for deployment

---

## 📷 Overview

The application displays an 8x8 grid representing a chessboard. When a piece is selected, all possible connections are automatically generated according to its movement rules.

In the recommended mode, the user can click on a specific square to visualize only the outgoing moves from that node, avoiding the visual clutter caused by displaying the entire graph at once.

---

## ⚙️ How to Run the Project Locally

1. Clone this repository:

```bash id="igdrla"
git clone https://github.com/your-username/your-repository.git
```

2. Open the project folder:

```bash id="zrqe25"
cd your-repository
```

3. Open the `index.html` file directly in your browser.

No dependency installation is required, since the project uses CDN-hosted resources.

---

## 📁 Project Structure

```bash id="shlmwa"
/
├── index.html
└── README.md
```

---

## 🎯 Project Goal

The purpose of this project is to demonstrate how web development can be used to visually represent mathematical and computational concepts.

It also serves as a practical example of how familiar rules, such as chess piece movements, can be transformed into visual data structures using directed graphs.

---

## 🔍 Usage Example

1. Select a chess piece from the sidebar.
2. Click **Generate Graph** or change the selected piece directly.
3. Click on a square of the chessboard.
4. Observe the directed edges that indicate the possible movements from that position.
5. Switch to full visualization mode to display all graph connections.

---

## 📈 Future Improvements

* Add more pieces or special movement rules.
* Include legal movements considering blocking pieces.
* Display additional graph metrics.
* Allow exporting the graph as an image.
* Add movement animations.
* Implement shortest paths between squares.
* Add search algorithms over the board.

---

## 👨‍💻 Author

Project developed as part of my personal portfolio, focused on visualizing mathematical structures using web technologies.

---

## 🌐 Demo

You can try the application here:

https://ajedrez-grafo-digrafo.vercel.app/
