# Graph For Better Genetics
**Contributers and Contact Information: Tim W. https://devpost.com/tim1988**

**Problem Statement addressed: Graph For Better X**

**Description**: 

DNA sequencing generates incredible amounts of data describing nucleotide sequences and genetic variants and their coded products, often spread across multiple databases. Other databases contain details of medical conditions and treatments, which may be affected by genetic variation. By using graph analytics, the associations between genetic variants, traits, disorders and treatments can be fully exploited and understood, by providing a mechanism to link all the data together in an accessible way.

**More information:**
https://devpost.com/software/graph-for-better-genetics

## Dependencies

No additional dependencies are needed to run this project in TigerGraph. 

## Installation
The **src** folder contains the following items:
1. **export_922368599.tar.gz** - the exported tarball of the complete schema and data mapping, created by "Export Current Solution" in GraphStudio
2. **csv_data** - folder containing the individual data .csv files that are needed to reproduce the examples demonstrated in the video
3. **all_data.ods** - the example data as an OpenDocument Spreadsheet with multiple tabs (for reference)
4. **schema-and-mapping.png** - image showing the schema and data mapping in GraphStudio (for reference)

To install the schema and database:
1. Clone repository
2. Import the tarball in GraphStudio by clicking "Import An Existing Solution" to install the schema and data mapping
3. Add and upload the data .CSV files (the data mapping page will show duplicate file icons that can be deleted after loading the data)
