PROCESS SETUP PAGE NAME
=======================

Overwrites function setupPageName() in class Pages (core), which is typically called in case of autogeneration of pages. Provides more options for 'Name Format Children' in parent template settings. [More](https://processwire.com/talk/topic/8576-name-format-children/?p=108748)

This Module could replace Pages::setupPageName with tiny adjustments. Take over the 4 functions (createFromFormat, SetupPageName, getSameNameArray and makeUnique) in the module. Rename ___SetupPageName() to ___setupPageName() and adjust some Inputfield notes. Done.

## Author
kixe (Christoph Thelen)
