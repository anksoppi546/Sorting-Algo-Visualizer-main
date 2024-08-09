**Features:**
 (i)The array elements are represented as bars of varying heights, which change dynamically as the algorithms sort them.
 (ii) Users can adjust the size of the array and regenerate new arrays.
 (iii) The project includes a speed slider that allows users to control the speed of the visualizations.
 (iv) When an algorithm is selected, the interface locks other buttons to prevent interference during the visualization. It prints Time Complexity of selected algorithm also.
![Sorting](https://github.com/user-attachments/assets/cf56a989-b35a-47c8-b6bb-ca901f84e7ec)
**Technical Implementation:**
 1. HTML Structure: Divides the interface into different sections, including a header, a main content area for the visualization, and a footer with algorithm selection buttons.
 2. CSS Styling: The color scheme is designed to provide a visual contrast that enhances the user experience. Responsive design principles are applied to ensure the visualizer works well on various screen sizes.
 3. JavaScript Functionality: Functions to generate the array, update its size dynamically, and handle the visual updates as the sorting algorithms progress. Visual updates during sorting are synchronized using 
 "setTimeout" to create illusion of motion. To enhance the interactivity, "disable_buttons" function is implemented that locks the interface during the sorting process to prevent user input that could interfere 
 with the visualization.
