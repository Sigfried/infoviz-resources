infoviz-resources
=================

Some handy resources as of early 2012. Will try to update.


## Software and programming resources

### Static graphics (primarily)

  * [R](http://www.r-project.org/).
  * [R graphics gallery](http://addictedtor.free.fr/graphiques/), [another](http://www.sr.bham.ac.uk/~ajrs/R/r-gallery.html)
  * [Examples](http://www.stat.auckland.ac.nz/~paul/RGraphics/chapter1.html) from excellent Paul Murrell book
  * [SAS JMP](http://www.sr.bham.ac.uk/~ajrs/R/r-gallery.html).
  * [Matplotlib](http://matplotlib.sourceforge.net/gallery.html) graphics library for Python. Naji and David Fetterer have experience.

### Interactive graphics (primarily)

  * [D3](http://mbostock.github.com/d3) D3 is an impressive Javascript library for making beautiful, animated graphs for the web. Significant learning curve.  
  

    * [Start here](http://alignedleft.com/tutorials/d3/binding-data/) This is the clearest explanation of the basic D3.js pattern I’ve seen yet.
    * [D3 Examples](http://mbostock.github.com/d3/ex), [D3 grab bag](http://blockses.appspot.com/mbostock), [introductory examples](http://www.verisi.com/resources/d3-tutorial-basic-charts.htm), [more examples](https://github.com/mbostock/d3/wiki), [tutorial](http://christopheviau.com/d3_tutorial)
    * [Hairy data/event details](http://groups.google.com/group/d3-js/browse_thread/thread/9697b3111f3d04e7)
    * To do: Make separate D3.js page with annotated references.
  * [Rickshaw](http://shutterstock.github.com/rickshaw) Nice time series chart library built on top of D3. Definite worth using!
  * [Paper.js](http://paperjs.org/) might be easier to use than D3 and have better performance on browsers (uses Canvas rather than SVG), but it doesn’t have all the charting features, like help creating axes.
  * [SVG in HTML](http://phrogz.net/svg/3-point-circle.xhtml). Nice example of how to do stylesheets and js with SVG embedded in HTML, without D3.
  * CSS:[Zen Garden](http://www.csszengarden.com/), [positioning](http://www.barelyfitz.com/screencast/html-training/css/positioning/)

Also look at the software listed in the [Business Intelligen
ce](http://ec2-67-202-41-166.compute-1.amazonaws.com/index.php/Visualization_W
orking_Group#Contexts_for_Information_Visualization) section

##  Data Management Frameworks for Web-based Visualizations

  * [Cube](http://square.github.com/cube/) is an open-source system for visualizing time series data, built on MongoDB, Node and D3.
  * [Tesseract](http://square.github.com/tesseract/) Fast Multidimensional Filtering for Coordinated Views

##  Specific Types of Data or Visualization

###  Hierarchical data

  * [Radial hierarchies in D3.js](http://blockses.appspot.com/1306365)
  * [Curvy interactive tree in D3.js](http://blockses.appspot.com/1061834)
  * [Zoomable icicle in D3.js](http://blockses.appspot.com/1005873)
  * [Treemaps](http://www.cs.umd.edu/hcil/treemap/)  
  

    * [3D treemap](http://finviz.com/map3d.ashx) market data. Ajaxy mouseovers.

###  Network data

  * [Hive Plot](http://www.hiveplot.com/) Very promising network diagram layout strategy. [Slides](http://www.hiveplot.com/talks/linnet-introduction.pdf)
  * [Cytoscape](http://www.cytoscape.org/)
  * [GraphViz](http://www.graphviz.org/)
  * [yEd](http://www.yworks.com/en/products_yed_gallery.html)
  * [NetworkX](http://networkx.lanl.gov/)

###  Temporal data

  * UMD/HCIL (Ben Shneiderman): [LifeFlow](http://www.cs.umd.edu/hcil/lifeflow/), [other](http://www.cs.umd.edu/hcil/temporalviz/)
  * [Disaster cost over time and country](http://disaster.mmx-dns.com/). Move slider at bottom to see animation over time.
  * Process flow: [Sankey in D3.js](http://nickrabinowitz.com/projects/d3/alluvial/alluvial-dynamic.html), [Resources for Sankey Diagrams](http://www.sankey-diagrams.com/sankey-diagram-software)
  * [Cube](http://square.github.com/cube/) is an open-source system for visualizing time series data, built on MongoDB, Node and D3.

###  Multi-dimensional data

  * Highly multi-dimensional data **What’s good? Parallel coordinates?**

###  Geographic Data

  * Open source cartography: [blog posting](https://plus.google.com/u/0/118383351194421484817/posts/foj5A1fURGt) by Sebastian Delmont

##  Collections and Resources

  * [Visual Complexity](http://www.visualcomplexity.com/vc/)
  * [Visualizing.org](http://www.visualizing.org/)
  * [Jeffrey Michael Heer](http://hci.stanford.edu/jheer/) Stanford HCI webpage
  * [Flowing Data](http://www.flowingdata.com/)
  * [Information is Beautiful](http://www.informationisbeautiful.net/)
  * [WikiViz/Tools](http://www.wikiviz.org/wiki/Tools) Very nice collection of visualization resources as of a few years ago.
  * [Resources for web graphics](http://coding.smashingmagazine.com/2011/04/07/useful-javascript-and-jquery-tools-libraries-plugins/)

##  Contexts for Information Visualization

  * Statistical graphics _Can we get copies of Naji’s slides for this section?_
  * Exploratory analysis
  * Graphics for the web
  * Business intelligence — the use of information to make business decisions. Dorothy and Sigfried would be very interested in hearing opinions SSS staff have about any of the products listed below. Trial versions are available on the websites.  
  

    * Relevant to Clinical Trials Networks Operations Centers, SSS internal operations, …?
    * Business intelligence software:  
  

      * [Tableau Software](http://www.tableausoftware.com/) Cutting edge business analytics software, reputation for being user-friendly. Dorothy and Sigfried have licenses ordered.
      * [Spotfire](http://spotfire.tibco.com/Tibco) Probably most robust and flexible than Tableau, not known for being as easy to use.
      * [Miner3D](http://www.miner3d.com/)
      * [SAS Business Intelligence](http://www.sas.com/technologies/bi) Used internally for financial planning (is that right?).
      * [IBM Cognos](http://www.ibm.com/software/analytics/cognos) SSS has a license.

##  To-do

  * Make repository of academic papers on infoviz, visual analytics topics
  * Add section on visualization luminaries (
  * [Tufte](http://www.linkedin.com/redirect?url=http%3A%2F%2Fwww%2Eedwardtufte%2Ecom%2Ftufte%2F&amp;urlhash=1HE2&amp;_t=tracking_disc)
  * [Michael Friendly](http://www.math.yorku.ca/SCS/StatResource.html#DataVis),
  * [Stephen Few](http://www.jmp.com/uk/about/events/explorers/speakers.shtml) ([white papers](http://www.jmp.com/uk/applications/bizviz/))
  * David McCandless [TED talk](http://www.ted.com/talks/david_mccandless_the_beauty_of_data_visualization.html)
  * Hans Rosling [TED talk](http://www.ted.com/talks/hans_rosling_shows_the_best_stats_you_ve_ever_seen.html)



[Home](https://www.assembla.com/) / [Developer API](http://api-
doc.assembla.com/) / [Support Portal](http://helpdesk.assembla.com/) / [Copy
this project](https://www.assembla.com/spaces/data_viz/prepare_copy)

Visualization is powered by Assembla Workspaces. [Learn
More](https://www.assembla.com/)

![](./Old SSS Visualization Wiki   Visualization Project
Assembla_files/dragDrop_ind1.gif)

[](javascript:;)[](javascript:;)

