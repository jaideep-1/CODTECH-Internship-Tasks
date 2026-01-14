
Task 1: Big Data Analysis with Dask

Objective:

To analyze a large-scale customer review dataset using parallel processing for scalability.

Tools Used:

Python, Dask, Pandas, Matplotlib

Process:

Loaded 500,000+ Amazon reviews using Dask DataFrame.

Cleaned missing and duplicate records with distributed operations.

Run parallel grouped aggregations.

Analyzed rating distribution, most reviewed products, and most active users.

Visualized insights using Matplotlib.

Insights:

The majority of customers rated products either 4 or 5, which means they are very satisfied.

Since a small number of products usually gain extremely high review counts, so we name it popularity concentration here. A minority of reviewers contribute disproportionately large numbers of reviews. Dask efficiently handled the dataset using partition-based parallel computation.
