# Contributing

Agencies that are added to lists should offer web development or design services.


## Table of Contents

- [Overview](#overview)
- [Adding a new agency](#adding-a-new-agency)
- [Adding a new "area" file](#adding-a-new-area-file)
- [Adding a new country folder](#adding-a-new-country-folder)
- [Folder Structure](#folder-structure)
- [Templates](#templates)


## Overview

- "Area" (state, province, territory, etc...)/city files hold lists of agencies.
- "Area"/city files are placed inside of their respective country folder.
- Country folders are placed inside of their respective continent folders.


## Adding a new agency

1. Be sure to add the agency to the correct "area"/city file.
    - If the necessary country folder or "area"/city file doesn't already exist, feel free to create it! _([see below](#adding-a-new-area-file))_
1. If the city isn't already on the list, be sure to add a new section and add it to the table of contents.
1. Exclude `www` and the trailing slash from the link.
1. Keep lists organized alphabetically by city, and then alphabetically by agency name _(numbers/symbols first)_.
1. If an agency has offices in multiple cities, be sure to add it to all of the "area"/city files.


## Adding a new "area" file

1. Follow the required structure when adding new files. _([see below](#folder-structure))_
1. Use the area's name as the filename. _(lowercase and hyphenated, no spaces please!)_
1. Use the "Area" template for the README file. _([see below](#templates))_
    - Some files will be a little different if the location doesn't have an "area". In this case, just use the city name as the filename and use the "City" template.


## Adding a new country folder

1. Follow the required structure when adding new folders. _([see below](#folder-structure))_
1. Use the countries name as the folder name. _(lowercase and hyphenated, no spaces please!)_


## Folder structure

```
|--- agencies
   |
   |--- <continent>
      |
      |--- <country>
         |
         |--- <area|city>.md
```


## Templates

#### Area

```
# <Area name>

### Table of Contents

- [<City name>](#<city-slug>)

---

##### <City name>

- [Agency Name](http://agency-website.com)
```

#### City

```
# <City name>

- [Agency Name](http://agency-website.com)
```
