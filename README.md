# Supporting the preservation of legacy source code.

Instantiating this template creates a [SWHAPPE](https://github.com/Unipisa/SWHAPPE) workbench to support the acquisition of legacy source code and feed it to Software Heritage.

The workbench comes with the predefined folders that are used in the supported process, [SWHAP](). Namely:

1. Folder [raw materials](./raw_materials) is for the original materials, as they have been found or submitted.

1. Folder [browsable source](./browsable_source) is for a browsable version of the source code. Source files, with the right extension, have to be accessible through the GitHub web interface, e.g., archives should be decompressed, code should be transcribed if provided by images, etc.

1. Folder [source](./source) is for the curated revision of the source code, as a base for the reconstruction of the development history as a git repository, i.e., a folder for each major version of the code.

1. Folder [metadata](/.metadata) holds various files with meta information (catalogue, actors, journal, tags) to be updated throughout the process. 

Please refer to the [SWHAPPE](https://github.com/Unipisa/SWHAPPE) guidelines for greater details. 
