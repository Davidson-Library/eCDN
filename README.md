# Davidson Library Ersatz CDN

This is the ersatz CDN (content delivery network) for the Davidson College Library, modeled on our colleagues' in [College Comms](https://github.com/DavidsonCollege/eCDN). The repo hosts files (primarily images) for utilization in websites, LMS, or other integrations with library systems. 

### Directory information

Directory | Purpose
--- | ---
libguides | persistent assets for use in Davidson College library's libguides


### Usage

The URL template for the images is:

`https://davidson-library.github.io/eCDN/{directory}/{file}`

`{directory}` = a directory listed above
`{file}` = file found in the directory

Example: https://davidson-library.github.io/eCDN/

### Notes

1. No files should be stored in the root directory. If you need to add a file, consider whether it fits into an existing dir. If it does not, create a new dir.
2. Directories should use hyphens if they need 2+ words. For naming standardization, images should include underscores in place of any spaces to ensure machine readability. 
3. Do not nest directories. Only a top-level directory with images.
4. When a new dir is added to the repo, please add it to this readme and include a v. brief description. 

