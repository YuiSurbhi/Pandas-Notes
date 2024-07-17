# Pandas-Notes
## 👉 About Pandas :

🐼 **Pandas:** Simplifying data analysis in Python! Pandas is a versatile library that provides intuitive data structures and powerful tools for data manipulation and analysis. It's essential for anyone working with structured data, offering seamless operations from data cleaning to exploration and visualization. Dive into data effortlessly with Pandas! 📊💡<br>

▫️ In Python 'pandas' refers to the pandas library used for working with data sets.<br>

▫️ It is a popular open source used for data manipulation and analysis tools.<br>

▫️ Pandas were made so that we can work with data effectively. 📊<br>

▫️ It provides data structures and functions designed to work with structured data in tabular
   form so that it can work easily and effectively.<br>

▫️ Pandas introduces two primary data structures:-<br>

  1. **Series:** A series is a 1-D labeled array that can hold any data type.<br>
               Series is a single column in a table, which is why considered 1-D.<br>

  2. **Dataframe:** A dataframe is a multi-dimensional labeled data structure that consists of columns,
                   each of which can hold different data types. 📉<br>
                  The representation of data is in tabular form, similar to a spreadsheet or SQL table.<br>

▫️ Pandas have a wide range functionalities of data manipulation and analysis including data cleaning, 
   data filtering, and more.<br>

▫️ Pandas is a base of Data Science.<br>

## 🔹 History :

▫️ Pandas was created by Wes Mckinney in 2008.<br>

▫️ The development of pandas was motivated by the need for flexible and efficient tools to handle and
   analysis structured data in Python.<br>

## Installation ⚙️

▪️ If <ins>Python</ins> and <ins>PIP</ins> are already installed on your system, then installing Pandas is easy<br>
▪️ Install it using this command:<br>

     pip install pandas

## 🔹 How can we use Pandas :

▪️ Once Pandas is installed, import it into your applications by adding the <code>import</code> keyword.<br>
▪️ Pandas is imported under <code>pd</code> alias.<br>
▪️ This alias is created with the help of <code>as</code> keyword while importing.<br>

      import pandas as pd

▪️ After this, Pandas can be referred as <code>pd</code> instead of <code>pandas</code>.<br>
▪️ Now, Pandas is imported and ready to use.<br>

### Example 

      import pandas as pd
      
      dict = {
      "Name":["John","Luca","Reba"],
      "Marks":[20,50,60],
      "Sports":["Cricket","Hockey","Basketball"]
      }

      school = pd.DataFrame(dict)
      school 

**Output**

      | Name  | Marks |     Sports |  
    --|-------|-------|------------|
    0 | John  | 20    |    Cricket |   
    1 | Luca  | 50    |     Hockey |    
    2 | Reba  | 60    | Basketball | 

