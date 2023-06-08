# Data Science Deep dive #6

Welcome to the Python workshop part of the data science deep dive #6. 

## Getting Started

To get started with the workshop, please follow these steps:

1. Clone the repository to your local machine.

2. Navigate to the `./deepdive6` folder

3. Install the required packages by running the following command:

`pip install -r requirements.txt`

This will install the necessary packages, including Pandas and Matplotlib, from the requirements.txt file.

4. Launch Jupyter Notebook or JupyterLab and open the workshop notebook (.ipynb file).

5. Follow the instructions in the notebook to learn about data profiling, data analysis, and visualization using Pandas and Matplotlib.

## Requirements

The workshop requires the following packages to be installed:

- Pandas: A powerful data manipulation and analysis library.
- Matplotlib: A plotting library for creating visualizations.

To install the required packages, use the command mentioned above or refer to the requirements.txt file for a detailed list of dependencies.

## Important Note

**Avoid Adding Data to Version Control**

It is generally considered bad practice to add data directly into a git repository. Here are a few reasons why:

1. **Large File Sizes**: Data files can be significantly larger than code files, causing repository size bloat and slower cloning, pushing, and pulling operations.

2. **Version Control Management**: Version control systems are designed for tracking changes to code, not large data files. Storing data in a repository can make it more challenging to manage and track changes effectively.

3. **Confidentiality and Security**: Data files may contain sensitive or confidential information. Storing such data in a public or shared repository can lead to unintended exposure or breaches of security.

4. **Data Integrity**: Adding data files to version control may introduce inconsistencies, especially when multiple contributors are working with the data. Tracking changes to data through version control systems is not as efficient or reliable as using dedicated data management systems.

To handle data in a more effective and organized manner, it is recommended to store data files separately and ensure proper data management practices, such as using databases, data lakes, or file systems designed for data storage and versioning.