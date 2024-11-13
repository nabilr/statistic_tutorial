The **Interquartile Range (IQR)** method is used in statistics to measure the spread or variability of a dataset and to identify **outliers**. It is especially useful because **it focuses on the middle 50% of the data**, making it less sensitive to extreme values compared to the range (which includes the entire data set).

### Why the IQR Method is Used:

1. **Identifying Outliers**:
   The IQR is commonly used to detect outliers. Any data point that lies outside the range:
   - Lower Bound = \( Q1 - 1.5 \times \text{IQR} \)
   - Upper Bound = \( Q3 + 1.5 \times \text{IQR} \)
   where \( Q1 \) is the first quartile (25th percentile) and \( Q3 \) is the third quartile (75th percentile), is considered an outlier.

2. **Resistant to Outliers**:
   Since IQR is based on quartiles, which are less influenced by extreme values, it is a robust measure of variability. This makes it ideal for analyzing datasets with potential outliers without having them skew the results too much.

3. **Measuring Data Spread**:
   The IQR provides a good sense of the spread of the middle half of the data. It is especially useful when you want to summarize the spread of data without considering outliers.

4. **Simple and Intuitive**:
   The IQR method is easy to calculate and interpret, which makes it a popular choice in exploratory data analysis and statistical summary.

