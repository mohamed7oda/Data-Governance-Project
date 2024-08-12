# Data-Governance-Project
In this project, we need to perform four tasks on the data: profiling, cleaning, validation, and privacy and security.

First, we performed profiling using the DataProfiler library.

Next, we moved on to the cleaning step, which is divided into three parts: dealing with duplicates, dealing with missing values, and dealing with outliers. We dropped the duplicates, and for any missing values in numerical columns, we replaced them with the median of the column. For missing values in categorical columns, we replaced them with the mode of the column.

To identify the outliers, we plotted the data and then removed the outliers.

After that, we conducted validation using the Pandera library by creating a schema for the columns.

Finally, in the privacy and security step, we applied techniques such as Randomization, Generalization, Masking, Perturbation, Aggregation, Suppression, Swapping, Nulling, and Pseudonymization.
