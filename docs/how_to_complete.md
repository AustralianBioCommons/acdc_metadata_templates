# ACDC Metadata Submission Tutorial

This tutorial provides step-by-step instructions for completing the metadata for various data nodes within the ACDC dictionary.


## Overview

When submitting data files, you must fill out a metadata template. This template includes all necessary entities within the data model, organised as tabs in an Excel spreadsheet. The order of these tabs follows the dependency hierarchy of the data model.


## Key Points

1. **Entity Order**: Complete the metadata for each tab (entity) in order, from left to right.
2. **Primary Keys**: Each entity’s primary key is located in the first column and follows the format `<entity_name>_uid`.
3. **Foreign Keys**: The second column contains foreign keys linking related entities.
4. **Row Information**:
   - **First Row**: Variable names.
   - **Second Row**: Variable descriptions, including data types and controlled vocabulary (reformat these in Excel for better readability, if needed).

## Completing the Metadata Template


### Step 1: Populate Metadata for Each Entity

- Complete the metadata for each tab, starting with the leftmost tab and proceeding sequentially to the right.
- **Primary Keys**: Create a unique identifier for each primary key in the first column. This key must:
  - Be unique and informative.
  - Adhere to a strict 50-character limit for performance reasons.


#### Guidelines for Primary Keys

- Begin the key with the entity name.
- Include the study ID.
- Add a unique identifier.

**Example**:

For a sample entity in study “ABC123,” a primary key might look like:

`sample_ABC123_001`


### Step 2: Link Entities via Foreign Keys

- Use the foreign key (second column) to link each entity to its dependencies.


## Metadata for Files

When submitting metadata for files:
1. **One File Per Participant**: Ensure that files are split by sample/participant. Do not reference a single file containing data for multiple participants.
2. **File Linking**: Include the relevant primary key for each participant’s file to establish a connection in the metadata.


## Additional Tips

- Ensure all data entries are accurate and comply with the controlled vocabulary and data types outlined in the second row of each entity tab.
- Validate the format and readability of the Excel sheet for better usability.

By following these guidelines, you can ensure that your metadata submission aligns with the ACDC dictionary and supports efficient data integration.