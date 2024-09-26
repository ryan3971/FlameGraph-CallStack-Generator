# FlameGraph-CallStack-Generator
A tool that builds off of AppDynamics DEXTER; call stack data is used to generate interactable SVG images in the form of Flame graphs. Can be enhanced using Power BI.

**Awaiting approval to share code**

# Project Summary
This project is a comprehensive tool for processing and visualizing call stack data, primarily aimed at generating flame graphs and icicle graphs from call stack information. The tool is built using Python and includes a graphical user interface (GUI) for ease of use. The project consists of several key components:

**Pre-Processing Call Stack Data**: The preProcessCallstack.py script processes raw call stack data, folding it into a more compact representation suitable for visualization.

**Flame Graph and Icicle Graph Generation**: The flame_graph_generator.py script takes the processed call stack data and generates SVG files for flame graphs and icicle graphs. These visualizations help in understanding the performance characteristics of the application by showing the time spent in various method calls.

**Graphical User Interface (GUI)**: The dexterExecutableGUI.py script provides a user-friendly interface for configuring and running the data processing and visualization tasks. The GUI allows users to specify input files, runtime parameters, and output directories.
