ckan-multilingual-translator
============================

Bootstrap based CKAN multilingual translator SPA tool

Intro
-----------------------
If you are using the CKAN [multilingual extension](http://docs.ckan.org/en/latest/maintaining/multilingual.html) you 
will probably require this tool as it will provide a nicer and quick interface to maintain localizations for the many strings that typically require translations.


Features
--------
The tool is a Single Page Application (SPA) as show in the quite self explicative screen:


The key features are:
* quick access and translate labels and strings of Datasets, Resources, Groups/Organizations, Tags and Dataset Extra fields
* filtering capability by translation status or by keyword
* easily usable by persons with translation skills only.
* completelly decoupled from CKAN
* authorization based on CKAN API Keys (via ckan4j-webapi)
* easy customizable
* super easy deployment


Dependencies
------------
The tools require a properly configured and working [ckan4j-webapi](http://github.com/sciamlab/ckan4j-webapi) that provide the appropriate translation WebAPI services for a given CKAN instance

Contribute
----------
The tool is pretty stable as it has been extensivelly tested and used for www.opendatahub.it and other CKAN based catalogs. If you spot any issue please report on [ideas and bugs](https://github.com/sciamlab/ckan-multilingual-translator/issues)



License
-------

    Copyright 2013-2014 Sciamlab s.r.l.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
