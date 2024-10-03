Sorting Visualizer

Overview
Sorting Visualizer is a web-based application that provides an intuitive and interactive way to visualize popular sorting algorithms. The tool is designed for students, developers, and anyone interested in learning sorting techniques and their efficiencies by observing the process step-by-step through graphical animations.

Features
Visualize how different sorting algorithms work.
Control the speed of the visualization to observe details.
Generate random arrays of different sizes.
Real-time feedback through graphical representations.
User-friendly interface with clear, simple controls.

Sorting Algorithms Implemented:
Bubble Sort
Time Complexity: O(n²)
Space Complexity: O(1)
Stable: Yes

Selection Sort
Time Complexity: O(n²)
Space Complexity: O(1)
Stable: No

Insertion Sort
Time Complexity: O(n²)
Space Complexity: O(1)
Stable: Yes

Merge Sort
Time Complexity: O(n log n)
Space Complexity: O(n)
Stable: Yes

Quick Sort
Time Complexity: O(n log n) (average)
Space Complexity: O(log n)
Stable: No

Heap Sort
Time Complexity: O(n log n)
Space Complexity: O(1)
Stable: No

Getting Started
To run this project locally, follow the steps below.

Prerequisites
A web browser (preferably Chrome, Firefox, or Edge).
Basic knowledge of HTML, CSS, and JavaScript.

Installation
1. Clone the repository:
git clone https://github.com/Sahil0502/Sorting-Visualizer.git

2. Open the index.html file in a browser:
Open index.html

File Structure
Sorting-Visualizer/
│
├── css/
│   └── styles.css       # Styles for visualizer
├── js/
│   ├── bubbleSort.js     # Bubble sort algorithm
│   ├── quickSort.js      # Quick sort algorithm
│   ├── mergeSort.js      # Merge sort algorithm
│   └── [Other algorithms]
├── index.html            # Main HTML file
├── README.md             # Project README
└── .gitignore

Technologies Used
HTML: Structure of the webpage.
CSS: Styling the elements and animations.
JavaScript: Implementing sorting algorithms and dynamic visualizations.
Sorting Algorithms: Core logic based on sorting concepts from Data Structures and Algorithms.

How It Works
The Sorting Visualizer displays sorting algorithms by graphically representing an array of numbers as bars. As the algorithm progresses, bars are moved, swapped, or changed in color to show comparisons and operations in real time. Using JavaScript, sorting algorithms like Bubble Sort, Quick Sort, and Merge Sort are implemented, and their steps are animated using setTimeout and CSS transitions.

Contribution Guidelines
Contributions are welcome! If you have ideas for new features, optimizations, or additional algorithms, feel free to open a pull request or issue.

Steps to Contribute:
Fork the repository.
Create a new feature branch (git checkout -b feature-name).
Commit your changes (git commit -m 'Add feature').
Push to the branch (git push origin feature-name).
Open a pull request.
