# Applied Machine Learning Project

Project Topic: Prediction of Expected Goals in soccer using machine learning

## File Types:

- All project files are Jupyter notebooks, as it is easy to analyze the data and model performance.
- Since the productionaisation is not in the scope of project, there isn't any need for python scripts.

## Follow below table to refer code files:

|  File  |  Description  | Final Output |
|  ---   |      ---      |    ---       |
|data_prep_1.ipynb| Combine the JSON files: Competitions, Matches, Lineups and Events into four final dataframes.  | four pickle files each representing one of the four final dataframes. |
|data_prep_2.ipynb | Prepare data for baseline model training. | one pickle file representing the final dataframe used for baseline model. |
|baseline_model_notebook.ipynb | Training baseline model. | Accuracy and feature importance of baseline model. |
|data_prep_3.ipynb| Feature engineering from events data for improvised model training. | one pickle file representing final dataframe used for improvised model. |
|improvised_model_notebook.ipynb | Training improvised model. | Accuracy and feature importance of improvised model. |
|rxg_notebook.ipynb | Training RxG model. | Accuracy xG shift of improvised model. |
