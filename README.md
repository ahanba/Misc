# Misc  

## Table of Contents  
- [htmlTable2XLS](#htmltable2xls)  
- [csv2tmx](#csv2tmx)  

## htmlTable2XLS  

### Description  
This script converts HTML tables to an XLSX file, supporting merged rows and columns.  

### How to Use  
1. Install required packages.
   ```python
   pip install beautifulsoup4 pandas openpyxl
   ```
2. Save the HTML file to your PC (press **Ctrl+S** in your web browser).  
3. Place the Python file in the same folder.
4. Open the Python file in a text editor.  
5. Update the following value to match your target table header:  
   ```python
   HEADER_INDICATOR = 'HEADER OF YOUR TARGET TABLES'
   ```  
6. Run the script.

   
## csv2tmx  

### Description  
This script converts CSV files to TMX format.  
It processes CSV files in the current directory and its subdirectories.  

### How to Use  
1. Open the Python file in a text editor.  
2. Update the following values to match your CSV headers:  
   ```python
   # Specify key, source, and target language headers
   key_id = "YOUR CSV'S KEY HEADER"
   source_lang = "YOUR CSV'S SOURCE HEADER"
   target_lang = "YOUR CSV'S TARGET HEADER"
   ```  
3. Run the script.  

> **TIP**  
> For details on TMX files and their format, see the [Phrase](https://support.phrase.com/hc/ja/articles/6111346531484--TMX-Strings) and [Transifex](https://help.transifex.com/en/articles/6838724-tmx-files-and-format) documentation.  
