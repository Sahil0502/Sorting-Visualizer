# Sorting Visualizer 🧮

## Overview

**Sorting Visualizer** is an educational web application designed to help users visually understand how different sorting algorithms work. The project uses HTML, CSS, and JavaScript to display sorting algorithms step-by-step, giving users a graphical representation of how data is sorted by popular algorithms.

This tool is perfect for students, developers, and anyone interested in learning or revisiting sorting concepts in an interactive way.

## 🚀 Features

- 🎨 **Visual Representation**: Graphical animations that clearly show the steps of sorting algorithms.
  - **Colored Representation of Steps**:
    1. 🔵 **Blue**: Default color (unsorted elements).
    2. 🟡 **Yellow**: Elements being compared.
    3. 🔴 **Red**: Elements identified as in the incorrect position and to be moved.
    4. 🟢 **Green**: Elements in their correct position.
- 🎛 **Adjustable Settings**: Modify the speed of the sorting process and change the size of the array being sorted.
- 🎲 **Random Array Generation**: Generate arrays of different sizes and values with a single click.
- 📱 **Responsive Design**: The application adapts to different screen sizes, so it’s viewable on both desktop and mobile devices.

## 📚 Implemented Sorting Algorithms

1. **Bubble Sort** 🟢  
   - Time Complexity: O(n²)  
   - Space Complexity: O(1)  
   - Stable: Yes  

2. **Selection Sort** 🟡  
   - Time Complexity: O(n²)  
   - Space Complexity: O(1)  
   - Stable: No  

3. **Insertion Sort** 🔵  
   - Time Complexity: O(n²)  
   - Space Complexity: O(1)  
   - Stable: Yes  

4. **Merge Sort** 🟠  
   - Time Complexity: O(n log n)  
   - Space Complexity: O(n)  
   - Stable: Yes  

5. **Quick Sort** 🔴  
   - Time Complexity: O(n log n) (average case)  
   - Space Complexity: O(log n)  
   - Stable: No  

6. **Heap Sort** 🟣  
   - Time Complexity: O(n log n)  
   - Space Complexity: O(1)  
   - Stable: No  

![image](https://github.com/user-attachments/assets/e5b0a714-258f-497a-b0f2-ff0f1e83a269)

## 💻 Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

- Any modern web browser (Chrome, Firefox, or Edge).

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Sahil0502/Sorting-Visualizer.git

2. Navigate to the project directory:
   ```bash
   cd Sorting-Visualizer

3. Open index.html in your web browser to view the application:

   On Windows, double-click index.html to open in your default browser. On Mac or Linux, you can run the following command in your terminal:

   ```bash
   open index.html

## 🛠 Tools Used
- HTML5: Provides the structure for the webpage.
- CSS3: Styles the application and creates smooth animations.
- JavaScript: Handles the logic behind the sorting algorithms and animates them.
- Sorting Concepts: Implemented sorting algorithms based on Data Structures and Algorithms       principles.

## 🖼 File Structure

```plaintext
Sorting-Visualizer/
│
├── css/
│   └── styles.css          # Styles for visualizer
├── js/
│   ├── bubbleSort.js       # Bubble sort algorithm implementation
│   ├── quickSort.js        # Quick sort algorithm implementation
│   ├── mergeSort.js        # Merge sort algorithm implementation
│   └── [Other Algorithms]  # Other sorting algorithms
├── index.html              # Main HTML file
├── README.md               # Project README
└── .gitignore              # Git ignore file
```

## 📊 How It Works
The Sorting Visualizer provides an animated representation of how sorting algorithms rearrange an array of bars (each representing a number). The bars change color and position to visually demonstrate the key operations of each algorithm, such as comparisons and swaps.

- Colors: Highlight comparisons and swaps between array elements.
- Animations: Slow down the sorting process to help users follow each step.
- Customizations: Users can adjust the speed of the algorithm and the size of the array for a better learning experience.

## 🤝 Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

How to Contribute
1. Fork the project.
2. Create your feature branch (git checkout -b feature/AmazingFeature).
3. Commit your changes (git commit -m 'Add some AmazingFeature').
4. Push to the branch (git push origin feature/AmazingFeature).
5. Open a pull request.

## 🔧 Future Enhancements
- Add more sorting algorithms like Radix Sort and Bucket Sort.
- Include detailed time and space complexity analysis for each algorithm.
- Implement dark mode for better accessibility.
- Add step-by-step navigation so users can manually go through each sorting step.

## 📝 License
This project is licensed under the MIT License. See the LICENSE file for details.

## 📬 Contact
For questions or feedback, reach out at: sahilsinghm32@gmail.com
