# Logic_gates
practice
💡 Digital Logic Bulb Simulator (AND/OR Gate)
This project simulates basic AND and OR logic gates using a bulb animation created with HTML, CSS, and JavaScript.
It helps visualize how digital logic gates work in a simple and interactive way!

📋 Features
Two inputs: Input A and Input B (each can be toggled ON or OFF).

Gate selection: AND or OR mode (via radio buttons or dropdown).

A bulb that:

Lights up based on the logic gate behavior.

Stays off when the conditions are not satisfied.

🛠️ Built With
HTML5 — for structure

CSS3 — for bulb design and styling

JavaScript (Vanilla) — for logic control and interactivity

⚡ How It Works
Toggle Input A and Input B by clicking their respective buttons.

Choose a gate type (AND or OR) using the provided selector.

Based on the selected gate:

AND Gate: Bulb turns ON only if both inputs are ON.

OR Gate: Bulb turns ON if either input is ON.

JavaScript updates the bulb's color dynamically by changing a CSS variable (--light-color).

🧠 Logic Table

Input A	Input B	AND Gate (A ⋅ B)	OR Gate (A + B)
0	0	0	0
0	1	0	1
1	0	0	1
1	1	1	1
📸 Screenshot Preview
![image](https://github.com/user-attachments/assets/41784317-c979-4bfe-8e6b-5e5b3f73cb11)


📂 Project Structure
bash
Copy
Edit
project-folder/
│
├── index.html     # Page structure
├── style.css      # Bulb design and responsiveness
└── script.js      # Gate logic and interactivity
🎯 Future Improvements
Add support for NAND, NOR, and XOR gates.

Animate bulb glowing smoothly.

Show real-time truth tables for selected gates.

📝 Author
Made with 💖 by Aanchal
