🔢 Bitwise Matching Pattern
A simple interactive web tool that, given a positive integer n, finds the next larger integer that has the same number of set bits (1s) in its binary representation.

✨ Features
🔢 Input a positive integer.

⚙️ Calculates the next integer larger than the input with the same count of binary 1 bits.

💻 Displays the result both as a decimal number and its binary form.

🎨 Clean, responsive UI with white background and black text.

♿ Accessible design with proper ARIA labels and keyboard-friendly input.

✅ Validates input and handles edge cases gracefully.

⚙️ How It Works
The algorithm identifies the rightmost non-trailing zero in the binary form of the input and manipulates the bits to produce the next integer with the same number of ones. If no such number exists (e.g., for all 1s at the left or the maximum 32-bit number), it returns -1.

🚀 Usage
📂 Open the index.html file in any modern web browser.

📝 Enter a positive integer in the input field.

▶️ Click the Find Next Number button.

👀 View the output below the button showing the next integer and its binary form.

🧪 Test Cases
Input	Expected Output
6	Next larger integer: 9 (binary: 1001)
13	Next larger integer: 14 (binary: 1110)
1	Next larger integer: 2 (binary: 10)
15	Next larger integer: 23 (binary: 10111)
7	Next larger integer: 11 (binary: 1011)
0	⚠️ Warning: Invalid input (positive integer only)
2147483647	❌ No larger integer with same bits

💻 How to Run Locally
🔽 Clone or download this repository.

🌐 Open the index.html file with your favorite web browser.

🛠️ No additional setup or dependencies required.

🛠️ Technologies Used
📝 HTML5

🎨 CSS3

💡 JavaScript (vanilla)

♿ Accessibility
🌐 Semantic HTML and ARIA labels used for better screen reader support.

⌨️ Keyboard accessible input and button.
