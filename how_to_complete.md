# Metadata Tutorial
This tutorial outlines how to fill our the metadata for various data nodes within the acdc dictionary.


When submitting data files, a metadata template should be filled in. the metadata template will include the all the necessary entities within the data model. Entities will be ordered as tabs in the excel spreadsheet, which is also based on the order that the entities depend on each other in the data model. 

Please fill out the metadata for each entity / tab, in order from left to right. The first column for each entity is the primary key. Table keys are named as `<entity_name>_uid`. The second column is the foreign key. The first row is the variable name, the second row is the variable description which also includes the data type and the controlled vocabulary. You may want to reformat this for readibility in excel.

When filling out the metadata submission sheet you will need to create links between all of the entities by creating a unique identifier for the primary key within the entity. You have freedom to choose a unique primary key that is informative but most importantly unique. For performance reasons, there is a strict 50 character limit on keys. but please feel free to follow these guidelines:

- start of the key should be the name of the entity
- include the study id
- include a unique identifier

When filling out metadata for files, you must ensure that files are split by sample / particiapnt, so that only one file per participant is present. You should NOT have one file for all samples.

