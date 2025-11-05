# Davidson Library Ersatz CDN

This is the ersatz CDN (content delivery network) for the Davidson College Library, modeled on our colleagues' in [College Comms](https://github.com/DavidsonCollege/eCDN). The repo hosts files (primarily images) for utilization in websites, LMS, or other integrations with library systems. 

### Directory information

Directory | Purpose
--- | ---
libguides | persistent assets for use in Davidson College library's libguides
icons | icons to be deployed in or on behalf of library systems 
assets | assets


### Usage

The URL template for the images is:

`https://davidson-library.github.io/eCDN/{directory}/{file}`

`{directory}` = a directory listed above
`{file}` = file found in the directory

Example: https://davidson-library.github.io/eCDN/icons/leganto_moodle_icon.png

### Notes

1. No files should be stored in the root directory. If you need to add a file, consider whether it fits into an existing dir. If it does not, create a new dir.
2. Directories should use hyphens if they need 2+ words. For naming standardization, images should include underscores in place of any spaces to ensure machine readability. 
3. Do not nest directories. Only a top-level directory with images.
4. When a new dir is added to the repo, please add it to this readme and include a v. brief description.

### Creating a Subdir
There is no "add a directory/file" button in the Github web interface, but you can still add a directory for your assets. 

1. *Start Creating a New File* Click on the "Add file" dropdown button near the top right (next to the green "Code" button), and select "Create new file".
2. *Specify the Folder Path _and_ File Name* In the file name input box, you will type the new *folder* name, followed by a forward slash (/), and then the name of a file to put inside it.

ex. `assets/readme.md`

![gif showing how to create a subdir in github](https://davidson-library.github.io/eCDN/assets/creating_subdir_github.gif)

