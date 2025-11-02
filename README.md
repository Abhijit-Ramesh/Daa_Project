# 💰 Coin Change Visualizer - Greedy Approach

An interactive web-based visualization tool for understanding the **Greedy Algorithm** approach to the classic Coin Change problem in Design and Analysis of Algorithms (DAA).

## 🎯 Overview

This project provides an animated, step-by-step visualization of how the greedy algorithm solves the coin change problem. It demonstrates the algorithm's decision-making process by always selecting the largest coin denomination that fits the remaining amount.

## ✨ Features

- **Real-time Visualization**: Watch coins appear with smooth animations as the algorithm selects them
- **Step-by-Step Breakdown**: See each decision the algorithm makes with detailed logging
- **Decision Table**: Track coin selection, amount used, and remaining value at each step
- **Live Statistics**: Monitor coins used, remaining amount, and iterations in real-time
- **Progress Tracking**: Visual progress bar showing how close you are to the target amount
- **Color-coded Coins**: Different denominations have distinct colors for easy identification
- **Customizable Inputs**: 
  - Set any target amount
  - Configure any coin denominations (comma-separated)
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## 🚀 How to Use

1. **Open the Application**: Simply open `daa_proj.html` in any modern web browser
2. **Set Target Amount**: Enter the amount you want to make change for
3. **Configure Coin Denominations**: Enter available coin values (comma-separated)
4. **Click Visualize**: Watch the algorithm in action!
5. **Reset**: Clear the visualization and try different values

### Default Example
- **Amount**: 41
- **Coins**: 25, 10, 1
- **Result**: Uses 1×25 + 1×10 + 6×1 = 8 coins total

## 📊 Algorithm Details

### Greedy Approach
The greedy algorithm solves the coin change problem by:
1. Sorting coins in descending order
2. For each coin, using as many as possible without exceeding the remaining amount
3. Moving to the next smaller coin denomination
4. Repeating until the amount is fully covered or no solution exists

**Time Complexity**: O(n) - where n is the number of coin denominations  
**Space Complexity**: O(1) - constant space used

### Important Note
The greedy approach doesn't always produce the optimal solution for all coin systems. For example:
- **Amount**: 6, **Coins**: [4, 3, 1]
- **Greedy Result**: 4 + 1 + 1 = 3 coins
- **Optimal Result**: 3 + 3 = 2 coins

## 🎨 Visual Features

- **Coin Animations**: Coins appear with a spinning animation
- **Color Scheme**: 
  - 25¢ (Quarter): Gold gradient
  - 10¢ (Dime): Silver gradient
  - 5¢ (Nickel): Bronze gradient
  - 1¢ (Penny): Copper gradient
  - Custom denominations: Purple gradient
- **Interactive Stats Cards**: Hover effects on statistics
- **Auto-scrolling**: Decision table and steps automatically scroll to show latest entries

## 🛠️ Technical Stack

- **HTML5**: Structure and layout
- **CSS3**: Styling, animations, and responsive design
- **JavaScript (Vanilla)**: Algorithm implementation and DOM manipulation
- **No Dependencies**: Runs entirely in the browser without external libraries

## 📁 Project Structure

```
daa/
├── daa_proj.html    # Main application file (HTML, CSS, JS combined)
└── README.md        # This file
```

## 💡 Use Cases

- **Educational**: Learn and visualize how the greedy algorithm works
- **Teaching Aid**: Demonstrate algorithm concepts in DAA courses
- **Comparison Tool**: Test different coin systems and amounts
- **Interview Prep**: Understand the coin change problem visually

## 🎓 Educational Value

This visualizer helps students understand:
- How greedy algorithms make locally optimal choices
- The difference between greedy and dynamic programming approaches
- When greedy algorithms work optimally vs. when they don't
- Algorithm complexity analysis
- Step-by-step execution flow

## 🔧 Customization

You can easily customize:
- Animation speed (modify `animationDelay` variable in JavaScript)
- Color schemes for different coin denominations
- Input validation rules
- Default values for amount and coins

## 🌐 Browser Compatibility

Works on all modern browsers:
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## 📝 Example Test Cases

Try these interesting cases:

1. **Standard US Coins**: Amount=99, Coins=[25,10,5,1]
2. **Greedy Failure**: Amount=6, Coins=[4,3,1]
3. **Large Amount**: Amount=127, Coins=[25,10,5,1]
4. **Custom System**: Amount=18, Coins=[7,5,1]

## 🤝 Contributing

Feel free to fork this project and enhance it with:
- Additional algorithm approaches (Dynamic Programming, BFS)
- More visualization options
- Export functionality for results
- Algorithm comparison side-by-side

## 📄 License

This project is open-source and available for educational purposes.

## 👤 Done by: Abhijit Ramesh, 2024UCD2122

Created as part of Design and Analysis of Algorithms coursework.

---

**Happy Visualizing! 🎉**
