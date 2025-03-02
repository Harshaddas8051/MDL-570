  // generates a dependency graph with the specified nodes and visualizes it.
  //Interactive Dependency Graph :
A simple web application that visualizes dependency relationships between items using an  graph. The graph is interactive, allowing users to click on nodes to explore their dependencies.

  // Features
Interactive Graph: Click on any node to view its dependencies.

Customizable Data: Easily modify the dependency data to suit your needs.

  // How It Works
Data Structure: The dependency data is stored in a JavaScript object where each key represents a node, and its corresponding value is an array of its dependencies.

Graph Rendering: The renderGraph function recursively builds the graph by creating nodes and links based on the provided data.

User Interaction: Clicking on a node triggers the renderGraph function again, focusing on the selected node as the new root.

  // Usage
Open the HTML File: Simply open the index.html file in a web browser to view the graph.

Modify the Data: Edit the graphData object in the JavaScript section to add or modify dependencies.
