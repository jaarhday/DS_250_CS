# DS_250_CS
**Python for Data Science Cheat Sheet**

**1. Basics of Data-Driven Programming:**
   - Efficiently use functions, data structures, and programming constructs.
   - Process and find meaning in data using Python.

**2. Loading Data:**
   - Programmatically load data from various sources:
     - Files: `pd.read_csv('filename.csv')`, `pd.read_excel('filename.xlsx')`
     - Databases: `pd.read_sql('SELECT * FROM table', connection)`
     - Remote Services: `requests.get(url).json()`

**3. Data Manipulation with pandas:**
   - Install pandas: `pip install pandas`
   - Basic DataFrame operations:
     - Selecting Columns: `df['column_name']`
     - Filtering Data: `df[df['column'] > value]`
     - Grouping and Aggregating: `df.groupby('column').agg({'other_column': 'mean'})`

**4. Data Visualization with Altair:**
   - Install Altair: `pip install altair`
   - Create a simple chart:
     ```python
     import altair as alt
     chart = alt.Chart(data).mark_point().encode(x='x_column', y='y_column')
     chart.show()
     ```

**5. Data Science Handbook:**
   - Reference book: "Python Data Science Handbook" by Jake VanderPlas.
   - Covers comprehensive data science topics with practical examples.

**6. Machine Learning:**
   - Install scikit-learn: `pip install scikit-learn`
   - Basic usage:
     ```python
     from sklearn.model_selection import train_test_split
     from sklearn.linear_model import LinearRegression

     X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2)
     model = LinearRegression()
     model.fit(X_train, y_train)
     predictions = model.predict(X_test)
     ```

**7. Collaboration and Sharing:**
   - Industry-leading tools:
     - Use Jupyter Notebooks for interactive coding and documentation.
     - Version control with Git: `git init`, `git add .`, `git commit -m "message"`

**8. SQL with data.world:**
   - Explore SQL with the data.world platform.
   - Access data using SQL queries: `SELECT * FROM dataset.table WHERE condition;`

**Additional Resources:**
   - [pandas User Guide](https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html)
   - [Altair User Guide](https://altair-viz.github.io/)
   - [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
   - [SQL by data.world](https://docs.data.world/documentation/sql/overview/)
