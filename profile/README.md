## Welcome to Machines Reading Maps

Machines Reading Maps (MRM) is a collaboration between the University of Southern California Digital Library, Computer Science & Engineering Department at the University of Minnesota, and the Alan Turing Institute (UK). The project is funded by the National Endowment for the Humanities (NEH) in the US and the Arts and Humanities Research Council (AHRC) in the UK under the first round of NEH/AHRC New Directions for Digital Scholarship. We also are supported by David Rumsey.

MRM seeks to normalize map text as a new kind of data that can be used across the humanities and the heritage sector. 

Here you will find the code, tutorials, guidelines for MRM tools and experiments. These include:

### Code

- **mapKurator-system** - A modularized method combining text spotting and entity linking using historical map scans as input. mapKurator output provides researchers with a structured dataset documenting the geospatial and image coordinates for the bounding polygon around any text on maps; the transcription of the text; and a prediction of links to external knowledge bases for named entities. 
- **mrm-recogito-ui** - Custom version of the Regotio annotation platform. This interface includes new features specific to map annotation, and integrates basic mapKurator functionality.
- **semantic-type-recommendation-api** - Retrieves semantically similar "types" of places (e.g. "hotel" or "school") for experimenting with semantic type labeling of features on historical maps.
- **Rumsey-MRM** - Pipeline using mapKurator to process 57k georeferenced maps in the David Rumsey Historical Map Collection.
- **luna-annotorious-client** - Annotation interface embedded in David Rumsey Historical Map Collection Luna Insight Browser. This interface allows users to edit mapKurator-generated map annotations and share new information about places labelled on maps.

### Tutorials

- [Using the integrated Recogito-mapKurator annotation tool.](https://github.com/machines-reading-maps/Tutorials-Newsletters/wiki)
- [Map Text Annotation Guidelines](https://github.com/machines-reading-maps/Tutorials-Newsletters/wiki/Map-Text-Annotation-Guidelines)

Questions or comments? You can reach us @ReadingMaps on Twitter, or you'll find our contact info [over here](https://machines-reading-maps.github.io/).
