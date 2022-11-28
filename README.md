# Dronninglund Data
Data and code for quality-control of data from the water pit thermal energy storage (PTES) in Dronninglund, Denmark.

The notebook **Dronninglund_data_treatment_GitHub** uses as input the raw data for 2014 (**Dronninglund_raw_data_2014**) and quality-controls the data as described in the under revision manuscript *"Dronninglund water pit thermal energy storage dataset"*. The outcome of this notebook is a new dataset named **Dronninglund_treated_data_2014**.

The flow rates and directions reported in the original dataset were found to be erroneous and did not maintain flow balance. For this reason, the notebook named **Dronninglund_flow_directions_GitHub** uses the data file **Dronninglund_treated_data_2014** as input and calculates the flow magnitudes and directions based on the energy and mass-flow balance of the storage. The results are saved in a new data-file named **Dronninglund_treated_data_and_flow_rates_2014**. More detailes on the method used for calculating the flow rates can be found in the previously mentioned under-review journal.

Last, the **Dronninglund_example_plots_GitHub** notebook, uses the data from **Dronninglund_treated_data_and_flow_rates_2014** to create some example plots and calculations for showcasing the operation of the Dronninglund PTES.
