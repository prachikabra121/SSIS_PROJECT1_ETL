"# SSIS_PROJECT1_ETL" 


i)Data flow task - load data from flat file to sql server table
ii)File system task - used to rename the loaded file by filename followed by date 
iii)File system task -used to move renamed file in archive folder
iv)execute process task - used to zip the file from archive folder
v)File system task - used to delete the file once the file is zipped
vi)utilized variables to make the complete process dynamic

