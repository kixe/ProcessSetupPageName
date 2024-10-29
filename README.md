PROCESS SETUP PAGE NAME
=======================


## No Longer Maintained
This repository is no longer maintained as it has been fully implemented in ProcessWire core.

```
@see core classes
Pages::setupPageName()
PagesEditor::setupPageName()
PagesNames::pageNameFromFormat()
```

#### [https://processwire.com/api/ref/pages-names/page-name-from-format](https://processwire.com/api/ref/pages-names/page-name-from-format/)

---

Overwrites function setupPageName() in class Pages (core), which is typically called in case of autogeneration of pages. Provides more options for 'Name Format Children' in parent template settings. [More](https://processwire.com/talk/topic/8576-name-format-children/?p=108748)

## Changelog
+ Since version 2.0.2 you have an option to update the name of existing pages if the values of the selected fields from which the name is generated have been changed. Use the option with caution because it has the potential to inadvertently break links if Page Path History module is not installed.

## Author
kixe (Christoph Thelen)
