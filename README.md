PROCESS SETUP PAGE NAME
=======================

Overwrites function setupPageName() in class Pages (core), which is typically called in case of autogeneration of pages. Provides more options for 'Name Format Children' in parent template settings. [More](https://processwire.com/talk/topic/8576-name-format-children/?p=108748)

This Module could replace Pages::setupPageName without any adjustment by taking over the 4 functions (createFromFormat, setupPageName, getSameNameArray and makeUnique) in the module.

## Author
kixe (Christoph Thelen)
