# _Changelog_
All notable changes to this project are documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## **[v0.3]**

### **Added**
- [documenti_Directory]() to contain, in the end, the Turtle files of every document studied during the staying in Bordeaux. When added, the Directory is empty, because more phases have to be completetd before starting the creation of the main file in `.ttl` format. Inside this Directory, nevertheless, two other directories has been added short after:
- [generi_Directory](), to store the Turtle file of the genres of documents found in the three series of the Itié-Latresne archive, made in order to create digital items for the main Turtle file of the documents;
- [inventario_Directory](), which contains the Turtle file with the description of the ancient inventory of the archive, made in XIX century. This is now a digital object with its URI.

## **[v.0.2]**

### **Added**
- [matrimoni Directory](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/RDF/matrimoni), with its [README.md](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/RDF/matrimoni/README.md) and the file in `.ttl` of the [marriages](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/RDF/matrimoni/matrimoni.ttl)
- [persone Directory](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/RDF/persone), and its [README.md](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/RDF/persone/README.md) and the draft of the `.ttl` file that will describe de [personal informations](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/RDF/persone/persone.ttl) of the people mentioned in the archive
- [images_Directory](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/images), the [README.md](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/images/README.md) and the directories for the files in `.jpg` of the [portraits](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/images/ritratti) and those in `.png` of the [coats of arms](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/images/stemmi): both will be used to complete the LODs for the people mentioned in the documents;
- [matrimoni Script](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/scripts/matrimoni.py), made to accelerate the creation of RDF triples after having some of them correctly written by myself.
- In [CSV Directory](https://github.com/glptr-gh/Ms4300_Digital_Library/tree/main/data/CSV), added [MS4300_database.v.0.1](https://github.com/glptr-gh/Ms4300_Digital_Library/tree/main/data/CSV/MS4300_database.v0.1.csv) and [noms.v0.1](https://github.com/glptr-gh/Ms4300_Digital_Library/tree/main/data/CSV/noms.v0.1.csv), incomplete versions of the databases that will be the main source for the website, uploaded to show the processes and the changing made before the achievement of the final tables. It's also for this reason, that the second file has been almost immediately replaced by [noms.v.0.2](https://github.com/glptr-gh/Ms4300_Digital_Library/tree/main/data/CSV/noms.v0.2.csv), because of the major changings made on this table (and not to the first one, which is still titled "v.0.1"). **DISCLAIMER: these two files are not complete yet, and they need much work on them to be really useful**.

### **Fixed**
Minor errors in [MS4300_database.v.0.1](https://github.com/glptr-gh/Ms4300_Digital_Library/tree/main/data/CSV/MS4300_database.v0.1.csv) and [noms.v0.1](https://github.com/glptr-gh/Ms4300_Digital_Library/tree/main/data/CSV/noms.v0.2.csv), such as empty cells, wrong positioning of quotation marks.

### **Changed**
- Deleted and reuploaded the [portraits Directory](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/images/ritratti) and the [coats of arms Directory](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/images/stemmi) in order to update more easily the names of the images, wrongly uploaded with an incorrect style of naming
- Updated this ChangeLog


## **[v.0.1]**

### **Added**
- Initial repository structure: [README.md](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/README.md), [LICENSE](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/LICENSE), CHANGELOG
- [Data directory](./data/), with a README describing its intended contents (tables, images, manifests, TEI transcriptions)
- [Scripts directory](./scripts/), with a README describing the image-processing pipeline, the structure of the HTML script, etc.
- [Docs directory](./docs/), with a README describing its intended contents (methodology, licenses, documentation for library staff)
