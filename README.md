## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Lokeshrathi/Lokesh_Rathi_Portfolio1/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Lokeshrathi/Lokesh_Rathi_Portfolio1/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

# IBM-HR-Attrition-Analysis-and-Prediction
- In this Notebook, we try to analyse and predict on *Attriction* on the IBM employee Dataset. 
- Dataset has 1470 rows and 35 columns.

## Data analysis:
 -  We divide the data into Numerical and Categorical type, to analyse them.
 - Using the categorical data, we plot a graph showing the counts for all the entries
 
 ![](/Images/IBM1.png)
 
 -Using the Numerical data, we check for the outliers
 
 ![](/Images/IBM2.png)
 
 ![](/Images/IBM3.png)
 
 - We also check for the columns with high multi-collinearity.
 
 ![](/Images/corr.png)
 
## Data Cleaning:

 - Here we remove:
  1. Redundant values
  2. Values with high collinearity.
  3. Removing columns having more than 96% similar values.
  4. Columns that have least correlation with the *target columns*.
  
  ![](/Images/c1.png)
  
- Data was reshaped to 1340 rows and 35 columns.

## Data Scaling:

  - *RobustScaler* is a transformation technique that removes the median and scales the data according to the quantile range (defaults to IQR: Interquartile Range). The IQR is the range between the 1st quartile (25th quantile) and the 3rd quartile (75th quantile). It is also robust to outliers, which makes it ideal for data where there are too many outliers that will drastically reduce the number of training data.
  
## Data Modeling:
  
  - We use **XGBoostClassifier** to model our data with hyper-parameter tuning.
  - Model gets us an **accuracy score of 87.30% and log_loss of 4.38.**

