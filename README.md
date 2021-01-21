# Database

[2021/01/10]
Completed the bad_apple function, which will replace any spreadsheet that is not SQL-compliant, using the archive bin files made by Retriever. Database can currently assemble and print its own custom-made data tables based on user search criteria, however it has no flexibility with regards to variations of search criteria between catalogues. For example, a command to build a table from multiple catalogues containing "total population by sex and age" will fail to incorporate the catalogue variable "total population by age and sex". 

[2021/01/21] 
Created the "Quality-Control" secondary program to implement catalogue-wide formatting corrections to relevant CSV files. SQL is strict regarding input, and Stats Canada can be a bit loose in their spreadsheet formatting. Specifically, the number of spaces in front of a sub-column must be strictly controlled as this indentation is used to linearize Stats Canada's 2D sub-column spreadsheets. 
