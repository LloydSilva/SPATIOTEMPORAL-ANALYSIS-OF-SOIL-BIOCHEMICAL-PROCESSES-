# SPATIOTEMPORAL-ANALYSIS-OF-SOIL-BIOCHEMICAL-PROCESSES-
1. Processed and visualized a spatiotemporal dataset using ParaView, analyzing soil biochemical processes (ammonification &amp; nitrification) and ecological factors (plant species &amp; functional types).
2. Advanced Visualization Techniques: Implemented color-coded planes, isolines, isosurfaces, and trend vectors to explore spatial and temporal patterns, including multi-variable representation and animated trends.
3. Key Findings and Insights: Identified seasonal variations in biochemical processes, detected an inverse relationship between ammonification and nitrification, and analyzed species distribution patterns, enhancing ecological understanding through data-driven visualizations.

Data description 
The data were collected by researchers from the Department of Plant Biology and concern 575 soil samples, from an area of 25x25 m2, where each sample contains values relating to the following variables: 
• PFT (Plant Functional Type / Tipo Funcional da Planta) 
• Plant Species (1 a 13) 
• Ammonification 
• Nitrification 
Samples were collected throughout the four seasons of the same year, which resulted in four samples, corresponding to the spring, summer, autumn and winter periods, respectively, 1st, 2nd, 3rd and 4th samples. 
The original grid provided for the collection of 625 samples, using a regular 25x25 grid. However, due to the existence of a rock, which covered an area of the land, only 575 samples were collected (see the figure for an approximation of the data collection area). Since the same number of samples were not collected along all grid lines, the original grid has an irregular topology. This type of grid involves describing all the grid cells, which makes formatting more time-consuming and requires more memory space. 

To simplify the grid description and data processing time, this unstructured grid was transformed into a structured grid. The solution was to add more points to the grid (corresponding to the missing points), thus obtaining a grid with a regular topology. However, so that these points did not “corrupt” the original structure, both in terms of the spatial reference and in terms of the data collected, fictitious points were created with the coordinates superimposed on those of the points that limit the grid corresponding to the data collection. Thus, these points are copies of the real points, making the grid have 625 points, but only 575 are distinct points and refer to the real samples. 

Data file contains: 

• 2 columns relating to the XX and YY coordinates of the grid points, that is, the points that identify the location of each of the samples. 

• 1 column with the values collected for the Plant Functional Type. 

• 1 column with the value of the Plant Species at each point on the grid. 

• 4 columns with Ammonification samples. 

• 4 columns with Nitrification samples. 
