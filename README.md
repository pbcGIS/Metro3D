# Metro3D: Simple City Model Schema
## Why? Expensive observations and effort are going to waste.
<p>We know that in the Boston area there are several municipal governments, campus administrations and architecture firms that maintain broad-scale 3D models for their territorial interests and surrounding area.  These models are used primarily for visualizing proposed changes.  Many of these models overlap with each-other resulting in redundency of details and of effort.  Furthermore the opportunity to systematically remember the past form of the city is fragmented and impractical to collect.  
By publising these resources on GitHub and working with users we seek to answer the question: By sharing tools and data, can we eintice independent city modelers to share selected models -- to build a metropolitan-scale cith model that reflects current conditions and approved proposals while remembering past conditions? 

We do not see region-wide collaborations in the development of metropolitan scale city models because figuring out how to organize the work is very time-consuming.  Individual participants don't have the motivation or skills think through the needs collaborators from different disciplines. This project is designed to diminish these obstacles by working with contributors from the spectrum of dispiplines to create a ready-made framework that is desiggned to preserve information through allof the potential hand-offs that are required. 
  
## What?  A simple scheme for organizing a 3D city model.  

Provides a framework for collaboration and sharing among diverse disciplines and their tools.

  * Municipal and campus IT organizations (geographic information systems
  * Design and Development community (Computer Aided Design / BIM)
  * Archives & Libraries, Historians, VR, Open-Source Community Apps  (Open-Source tool-chains) 

## Product: A Simple, Cross-Platform Archive Repository for a Module-Based City Model:</h2>
A simple scheme of tiling, coordinate referencing, and cataloging that produces a portable interoperable city model repository that includes:</p>
  * Detailed terrain models: SketchUp, Wavefront Object
   * Detailed Building Model Collection: SketchUp, ESRI Geodatabase, Wavefront Object
   * Model Catalog with detailed provenance and temporal information (CSV, GeoJSON) 
   * Groundplan images (JPG): Modern basemap, Recent True Ortho Photo, Detailed historical maps 
   * Vector groundplan and terrain linework in DXF format.

The Archive Repository Schema is ready now and will soon replace the [prior version](http://www.bostonplans.org/3d-data-maps/3d-smart-model/3d-data-download0 of the Boston Planning and Development Authority's 3D Data Download Site. The repository is:
   * Simple specification for arranging data embedded with a complete catalog 
   * Easy to access for interactively assembly of any portion of the city-model in commercial 3D modeling tools
   * Easy to apply automated tools for assembling and performing wholesale visualiations and workflows using commercial or open-source tool-chains including geographic information systems.
   * Fulfills the requirements of an Archival Information Package according to the [Open Archive Information System Recommendations](https://en.wikipedia.org/wiki/Open_Archival_Information_System) for assuring integrity of information assets through exchange and migration.  

## Use It!
We know that the csheme is appreciated by the users of 3D model assets.  We hope that with this new release, it will also make life easier for publishers of city models.   
Inspect and download a fully-working demo of this simple ready-to use data package from the [./Boston3d/bos3d_repository_demo](Boston3d/bos3d_repository_demo) branch of this GitHub repository.

## Procedures and Tools for Creating and Managing Simple, Sharable City Models  
Later this year we will be publising the ArcGIS Pro Toolboxes and Tasks and Safe Software FME workbenches that are used to transform municipal GIS data into city models and then tile and publish using this this repository scheme.  When these are ready, we wil  publishe them in the Boston/ArcGIS folder. 

## Taking It forward
<p>There are many ways that this project can be taken forward.  pbcGIS is planning  to extend our project with the City of Cambridge Hostorical Commission [https://chcomeka.azurewebsites.net/omeka-s/s/cdash/page/home](Cambridge Architectural Survey and History) a geographically-informed digital archive of building information.  This application has extended the [popular archiving tool, Omeka to connect old photographs and other documents with historic maps. We wil be adding a 3D previewer to show how easy it is for "traditional" archival tools to preserve 3D models.  We also hope to demonstrate the use of the schema to publish historical map tiles that will be useful for people interested in documenting this history of boston places in 3D.  Check [http://www.pbcgis.com/metro3d](www.pbcgis.com/metro3d) for more information about these projects and for contact information. 

Along the way, we hope to develop open-source tool-chains like ThreeJS to process and transform models from the Metro3D Simple Schema to broad-scale web visualizations.  Interested in helping?   

## Acknowledgements
This work has been supported by the **Boston Planning and Development Agency Office of Digital Cartography and GIS** and the **City of Cambridge GIS Department**. 
