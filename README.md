# Dronninglund Data

In the folder **notebooks** there are scripts for quality-controlling data from the water pit thermal energy storage (PTES) in Dronninglund, Denmark. A short description of each spript is provided below.

#### [Dronninglund_data_treatment_GitHub](https://github.com/PitStorages/DronninglundData/blob/main/notebooks/Dronninglund_data_treatment_GitHub.ipynb)

It uses as input the raw data for 2014 (**Dronninglund_raw_data_2014**) and quality-controls the data as described in the under revision manuscript *"Dronninglund water pit thermal energy storage dataset"*. The outcome of this notebook is a new dataset named **Dronninglund_treated_data_2014**.


#### [Dronninglund_flow_directions_GitHub](https://github.com/PitStorages/DronninglundData/blob/main/notebooks/Dronninglund_flow_directions_GitHub.ipynb)

The flow rates and directions reported in the original dataset were found to be erroneous and did not maintain flow balance. For this reason, this notebook uses the data file **Dronninglund_treated_data_2014** as input and calculates the flow magnitudes and directions based on the energy and mass-flow balance of the storage. The results are saved in a new data-file named **Dronninglund_treated_data_and_flow_rates_2014**. More detailes on the method used for calculating the flow rates can be found in the previously mentioned under-review journal.


#### [Dronninglund_example_plots_GitHub](https://github.com/PitStorages/DronninglundData/blob/main/notebooks/Dronninglund_example_plots_GitHub.ipynb)

It uses the data from **Dronninglund_treated_data_and_flow_rates_2014** to create some example plots and calculations for showcasing the operation of the Dronninglund PTES.


All data files are located in the folder **data**.
