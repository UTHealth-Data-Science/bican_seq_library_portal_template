1. In each CSV file, assign YOUR OWN local name to the field labeled as '*_local_name'. DO NOT utilize the identical one present in the template.
2. The file names need to be kept the same.
3. The format of "project_identifier" should be "NIH AWARD NUMBER - PI's first_name last_name", for example, "UM1MH130981 - Ed Lein" 
4. The "other_species" field is required, with a value of 0 representing standard human and 1 indicating different species or other human.
5. If the "other_species" field is set to 0, "roi_local_name" is required. You can use either the ROI NHash ID or the local name as the value. If the "other_species" is set to 1, "donor_local_name" is required.
6. Please do not include a row in tissue sample_structure.csv for tissue samples without structures.
6. The format for date fields is: mm/dd/yyyy.
7. Please refer the data dictionary "Sequencing_Library_batch_upload_data_dictionary.csv" for information regarding all the fields in the templates including their types, value sets for categorical variables, and whether they are required or not.
8. barcoded_cell_sample_tag.csv and barcoded_cell_sample_tag_component.csv are optional.
