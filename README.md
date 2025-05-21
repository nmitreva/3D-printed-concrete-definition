# 3D-Printed Concrete Wall Visualizer

## 📌 Description

This Python-based interactive visualization tool was developed as part of a master's thesis focused on **optimising 3D-printed concrete structures for carbon capture and storage (CCS)**. The goal is to explore how geometric parameters such as **wall thickness** and **number of internal triangles** influence both the material distribution and environmental performance of the structure.

Using the **Dash** framework and **Plotly**, the application provides a dynamic 3D visualization of a wall structure. It helps designers and researchers understand how geometric configurations affect surface area, material usage, and ultimately the potential for carbon capture.

## ⚙️ Installation

Before running the application, ensure you have Python 3.8 or later installed. Then, install the required libraries:

```bash
pip install dash
pip install numpy
pip install plotly
```



## Usage Instructions
To run the application, follow these steps:

a. Clone the repository or download the .py file containing the application code.
b. Open a terminal and navigate to the folder containing the script.
c. Launch the application with: python app.py .
d. After running the script, a local web page will open in your default browser (usually at http://127.0.0.1:8050/).
e. Use the interactive sliders to modify:
   - The number of triangles in the structure
   - The thickness of the concrete layers
The geometry will update in real-time based on your inputs, and the updated width of the wall is displayed dynamically.


## Exemplary Usage
Imagine you want to explore the impact of using 8 triangles and a thickness of 0.05 m:
   - Open the web interface
   - Set Number of Triangles = 8
   - Set Thickness = 0.05

The application will:
i.   Display a 3D model of the wall with the specified parameters
ii.  Calculate the resulting wall width needed to carry a compressive load of 5 MN/m
iii. Offer a realistic representation of how the printed geometry would look in practice

This tool is particularly useful in the early design phase to visually evaluate material layout strategies, with the ultimate goal of reducing carbon emissions while maintaining structural efficiency.

Functional Unit
The reference unit used for all visualizations and calculations is 1 m² of 3D-printed wall. This standardized measure allows for direct comparison between different configurations and supports further environmental analyses like Life Cycle Assessment (LCA).
