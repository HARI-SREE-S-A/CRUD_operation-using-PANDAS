# CRUD_operation-using-PANDAS

Reading Excel Files: You can use the read_excel function of pandas to read an Excel file into a DataFrame. The function has several parameters that allow you to customize the reading process, such as the sheet name, column names, and data types.
python
Copy code
import pandas as pd

## Read the Excel file into a DataFrame
df = pd.read_excel('example.xlsx')
Creating Excel Files: You can create a new Excel file using pandas by creating a new DataFrame and then using the to_excel function to write the DataFrame to an Excel file.
python
Copy code
import pandas as pd

## Create a new DataFrame
df = pd.DataFrame({
    'Column1': [1, 2, 3],
    'Column2': ['A', 'B', 'C']
})

## Write the DataFrame to a new Excel file
df.to_excel('new_file.xlsx', index=False)
