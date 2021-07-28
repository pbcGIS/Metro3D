# Metro3D: Simple City Model Schema
## Why? Expensive observations and effort are going to waste.
<p>We know that in the Boston area there are several municipal governments, campus administrations and architecture firms that maintain broad-scale 3D models for their territorial interests and surrounding area.  These models are used primarily for visualizing proposed changes.  Many of these models overlap with each-other resulting in redundency of details and of effort.  Furthermore the opportunity to systematically remember the past form of the city is fragmented and impractical to collect.  
By publising these resources on GitHub and working with users we seek to answer the question: By sharing tools and data, can we eintice independent city modelers to share selected models -- tobuild a metropolitan-scale cith model that reflects current conditions and approved proposals while remembering past conditions? 

A culture of this sort would sustain itself because participation will be cost-effective for participants.  Additional value would be created if the resulting information was able to be captured by a variety of new applications -- including historical preservation and archiving, virtual reality, STEAM education and others.  
  
## What?  A scheme for organizing a 3D city model.  Facilitates collaboration among diverse disciplines and their tools.

  * Municipal and campus IT organizations (geographic information systems
  * Design and Development community (Computer Aided Design / BIM)
  * Archives & Libraries, Historians, VR, Open-Source Community Apps  (Open-Source tool-chains) 

We do not see region-wide collaborations in the development of metropolitan scale city models because figuring out how to organize the work is very time-consuming.  Individual participants don't have the motivation or skills think through the needs collaborators from different disciplines. This project is designed to diminish these obstacles by working with contributors from the spectrum of dispiplines to create a ready-made framework that is desiggned to preserve information through allof the potential hand-offs that are required. 

## Product: A Simple, Cross-Platform Archive Repository for a Module-Based City Model:</h2>
A scheme of tiling, coordinate referencing, and cataloging that produces a portable interpoerable city model repository that includes:</p>
  * Detailed terrain models: SketchUp, Wavefront Object
   * Detailed Building Model Collection: SketchUp, ESRI Geodatabase, Wavefront Object
   * Model Catalog with detailed provenance and temporal information (CSV, GeoJSON) 
   * Groundplan images (JPG): Modern basemap, Recent True Ortho Photo, Detailed historical maps 
   * Vector groundplan and terrain linework in DXF format.

The Archive Repository Schema is ready now and will soon replace the [prior version](http://www.bostonplans.org/3d-data-maps/3d-smart-model/3d-data-download target="_new") of the Boston Planning and Development Authority's 3D Data Download Site. The repository is:
   * a simple specification for arranging data with easy-to-maintain html documents and javascript 
   * Easy to access for interactively assembly of any portion of the city-model in commercial 3D modeling tools
   * Easy apply automated tools for assembling and performing wholesale visualiations and workflows using commercial or open-source tool-chains including geographic information systems.
   * Fulfills the requirements of an [https://en.wikipedia.org/wiki/Open_Archival_Information_System](Open Archive Information System) for assuring integrity of information assets through exchange and migration.;  

Inspect and download a fully-working demo of this simple ready-to use data package from the [Boston3d/bos3d_repository_demo/](tree/main/Boston3d/bos3d_repository_demo) branch of this GitHub repository.

## Process: Procedures and Tools for Creating and Managing Simple, Sharable City Models  
Later this year we wil be publising the ArcGIS Pro and FME toolboxes and tasks that are used to turn municipal GIS data into this repository scheme.
<p>Next, to extend our project with the City of Cambridge Hostorical Commission to develop a geographically-informed digital archive of building information (photographs and documents) -- to demonstrate how 3D models from the Metro3D Simple City Model Scheme can be integrated into tools and standards used by main-stream archives, libraries and museums.  Follow this work at <a href="http://www.pbcgis.com/metro3d">www.pbcgis.com/metro3d</a>.

## Acknowledgements
     we have developed with the sponsorship of the Boston Redevelopment Authority 
