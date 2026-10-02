# Assignment-Data-cleaning
Data cleaning
	1) Handling Missing Values:	
  
		• Check for missing values in the 'Price' column. How would you handle products with missing price information?	

  [median imputation , median=130]  
		
    • If there are products with missing categories, propose a strategy to impute or deal with these missing values effectively.	

    [Replaced with "not given"]

    	2) Correcting Inconsistent Data:	

      
		• Identify any inconsistent text formats present in the "Product Name" column.

    [Inconsistent capitalization present, used PROPER function]
    
		• Identify any typos present in the "Category" column.	

    [spelling mistake, Electroni]
    
		• Use the find and replace function to standardize the text formats in the "Product Name" column and fix any typos or misspellings in the "Category" column.		

    [ctrl+H Used]


				3) Removing Duplicates:

        
		• Identify any duplicate rows within the dataset based on the entirety of each row, and remove them if any.							
									
[Removed duplicates from data tool]


			4) Splitting and Merging Data:	

      
	• Split the "Product ID" column into two separate columns for " Manufacturing Date" and "Country Code". Remove unnecessary characters, if any.	

  [used split column]

  
	• Merge the "Brand Name" and "Product Name" columns into one column named "Product Brand".	

  [used merge function]


  	5) Number Formatting:	

    
		• Format the data type of the "Price" column to currency format. 

    [number format to currency ]
    
		• Format the "Manufacturing Date" column to display dates in the "DD-MM-YYYY " format. 

    [changed to date format from the column ]


    	6) Conditional Formatting:	

      
		• Apply data bar or color scales conditional formatting in the "Price" column.

    [conditional formatting/data bars/gradient fill]

    
		• Create a custom rule for conditional formatting in the "Category" column to highlight cells where the category is "Electronics."			

    [conditional formatting/Highlite cells rule/Equal to Electronics]
										


								



				

