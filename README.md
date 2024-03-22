# Predictive Analytics M5 Walmart Sales Forecasting
Code repository for the M5 Walmart Sales Forecasting Competition - Data prep, Model Training &amp; Submissions.

Different file names suggest different stages of the model training process. Starting from initial Data Prep, Feature Engineering, Model training on different types of models, etc. Please refer to these files for the correct input and output files for different stages.


### About cuDF -  an innovative solution for faster pandas processing:
I have used **'cuDF'** - a plugin/extension by [https://docs.rapids.ai/api/cudf/stable/](RAPIDSAI) to pandas library when performing different kinds of operations on a pandas dataframe. This library takes over the computationally extensiove tasks like joins and aggregations to the GPU (if present on the machine) for faster and parallel processing instead of having a CPU do the job. The best thing about this library is it is fully compatible with the **pandas** library and requires no change in code syntax. If a task is possible to be overtaken by GPU, it conviniently hands over the task to the GPU or else the task continues to execute on the CPU. This ensures and interruption free code execution with a faster and parallel processing of code wherever possible.

Before installing, it first checks if the machine is compatible for faster execution (i.e presence of a compatible GPU). For more info about the cuDF library, please refer [https://docs.rapids.ai/api/cudf/stable/cudf_pandas/](here)
