#  Java Caro Game (Gomoku)

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Swing](https://img.shields.io/badge/Swing-GUI-blue?style=for-the-badge)

###  Overview
This is a classic **Caro (Gomoku)** strategy board game developed using **Java Swing**. The application features a graphical user interface (GUI) that allows two players to compete on a 20x30 grid. The project demonstrates solid understanding of **Object-Oriented Programming (OOP)**, **Event Handling**, and **Algorithm Logic** in Java.

###  Key Features
* ** Large Board:** A 20x30 grid layout offering a comprehensive gameplay experience.
* ** Win Detection Algorithm:** Intelligent algorithm to detect 5 consecutive symbols (Horizontal, Vertical, Diagonal) to declare the winner immediately.
* **n Undo Functionality:** Implemented using a Stack data structure logic, allowing players to retract moves if mistakes are made.
* ** Game Controls:** Options to start a **New Game** or **Exit** at any time.
* ** Interactive UI:** Visual feedback for turns (X/O) and winning notifications.

###  Technical Details
* **Language:** Java (JDK 8+).
* **Library:** Java Swing & AWT (Abstract Window Toolkit).
* **Logic:**
    * `checkWin()`: Scans 4 directions from the last placed point to count consecutive marks.
    * `Undo System`: Uses two arrays `xUndo[]` and `yUndo[]` acting as a stack to store move history.

###  How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Nguyenchicuong34/](https://github.com/Nguyenchicuong34/GAME_CARO_BASIC].git
    ```
2.  **Open in IDE:**
    Open the project in IntelliJ IDEA, Eclipse, or NetBeans.
3.  **Setup Resources:**
    Ensure the `icons` folder (containing `x.png`, `o.png`, `h.png`) is in the resource path.
4.  **Run:**
    Run the `Caro.java` file.
---
###  Author
Developed by **Nguyen Chi Cuong**
* **School:** HCMC University of Industry and Trade (HUIT)
* **Major:** Information Security
