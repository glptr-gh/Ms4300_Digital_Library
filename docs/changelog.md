# _Changelog_
All notable changes to this project are documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## **[v.0.2]**

### **Added**
- [matrimoni Directory](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/RDF/matrimoni), with its [README.md](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/RDF/matrimoni/README.md) and the file in `.ttl` of the [marriages](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/RDF/matrimoni/matrimoni.ttl)
- [persone Directory](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/RDF/persone), and its [README.md](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/RDF/persone/README.md) and the draft of the `.ttl` file that will describe de [personal informations](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/RDF/persone/persone.ttl) of the people mentioned in the archive
- [images_Directory](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/images), the [README.md](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/images/README.md) and the directories for the files in `.jpg` of the [portraits](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/images/dipinti) and those in `.png` of the [coats of arms](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/images/stemmi): both will be used to complete the LODs for the people mentioned in the documents;
- [matrimoni Script](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/scripts/matrimoni.py), made to accelerate the creation of RDF triples after having some of them correctly written by myself.

### **Fixed**

### **Changed**
- Deleted and reuploaded the [portraits Directory](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/images/dipinti) and the [coats of arms Directory](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/data/images/stemmi) in order to update more easily the names of the images, wrongly uploaded with an incorrect style of naming
- Updated this ChangeLog


## **[v.0.1]**

### **Added**
- Initial repository structure: [README.md](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/README.md), [LICENSE](https://github.com/glptr-gh/Ms4300_Digital_Library/blob/main/LICENSE), CHANGELOG
- [Data directory](./data/), with a README describing its intended contents (tables, images, manifests, TEI transcriptions)
- [Scripts directory](./scripts/), with a README describing the image-processing pipeline, the structure of the HTML script, etc.
- [Docs directory](./docs/), with a README describing its intended contents (methodology, licenses, documentation for library staff)
