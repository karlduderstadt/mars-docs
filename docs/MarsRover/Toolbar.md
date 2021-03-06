---
layout: marsrover
title: Toolbar
permalink: /docs/MarsRover/Toolbar/index.html
---
<img align='center' src='{{site.baseurl}}/docs/img/Icons/img0.png' width='100' />

#### File

| :------------- | :------------- |
| Save       | Save the created Molecule Archive.      |
| Save a Copy       | Save a copy of the created Molecule Archive.       |
| Save a Virtual Store Copy       | Save the Molecule Archive in virtual storage.       |
| Close      | Close **Mars Rover**.|

A Molecule Archive can be saved in two ways:
1. Normal storage: saved in the .yama file format. Additionally a .yama.cfg file is saved containing information like settings and selections. A .cfg file can be renamed and reused for another archive to apply the settings defined for another Archive.
2. Virtual storage: saves a .yama.store folder containing .json files for the indexes, properties, all molecule UIDs and experiment IDs separately. Choose this saving mode when dealing with large data sets.


#### Tools

| :------------- | :------------- |
| Delete Molecules      | Delete molecules with a specific tag or all molecules without tag.     |
| Delete Molecule Tag       | Delete a specified or all tag(s).       |
| Delete Molecule Parameters       |  Delete a specified or all calculated parameter(s).      |
| Delete Segment Tables       | Deletes segment tables that are generated for the kinetic change point analysis.       |
| Merge Molecules       | Merges the data tables of multiple molecules. Use f.e. if a tracking result appears to be split into multiple smaller tracked segments.       |
| Show Video      | Shows the video at a specific position corresponding to a tracked molecule. See also the [tutorial](https://duderstadt-lab.github.io/mars-docs/tutorials/workingwithmars/bdv/) on finding tracked molecules in the video.      |
| Export Video      | Exports the video at a specific position corresponding to a tracked molecule. See also the [tutorial](https://duderstadt-lab.github.io/mars-docs/tutorials/workingwithmars/bdv/) on finding tracked molecules in the video, step 5.        |
| Rebuild indexes      | Rebuild the index.json file when operating in virtual storage.        |
