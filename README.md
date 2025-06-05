## **A Transferable Spatio-temporal Learning Framework for Cross-city Logistics Demand Prediction**
[](https://img.shields.io/badge/PyTorch-1.10%2B-orange)
Official implementation for "A Transferable Spatio-temporal Learning Framework for Cross-city Logistics Demand Prediction".

## **Abstract**
In logistic systems, demand prediction is an essential task providing the basis for improving the quality of terminal services, such as pick-up and delivery efficiency. However, the geographical scope of operations across multiple cities brings challenges due to the spar- sity of user behavior data, hindering accurate predictions. Despite cross-city prediction methods potentially solving this problem by relying on the label of overlapping users in different cities, annotat- ing these overlapping users is expensive. Additionally, the dynamic and diverse nature of user behaviors complicates feature transfer between cities. In this work, we define the logistics demand predic- tion problem as forecasting pick-up and delivery demand for zones, the smallest operational units in logistics systems, in different cities. To address the challenge, we propose TSTL, a Transferable Spatio- Temporal Learning framework for cross-city logistics prediction with sparse user data. TSTL advances existing methods from two aspects: (1) User-level invariant representation module extracts con- sistent user representations for overlapping and non-overlapping users across cities. (2) User-zone graph aggregation module en- hances user embeddings by integrating dynamic interactions, such as logistics behaviors, into inherent user relations. Finally, the multi- city transfer module fine-tunes model parameters for city-invariant knowledge adoption and predicts future logistics demand. We im- plement and evaluate TSTL on one of the largest logistics systems. Extensive offline experiments and real-world deployment demon- strate the effectiveness of TSTL.

## Data Preparation
```
Due to the internal data disclosure agreement involving JD Logistics, we are actively communicating the feasibility of data disclosure to pursue the legal disclosure of data. 
```
Certainly! Here is the "Start Jupyter Notebook" section translated into English:

## Start Jupyter Notebook

To run the `main.ipynb` file, please follow these steps:

1. Navigate to the project directory in the command line:

   ```bash
   cd /project_directory
   ```

2. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. In the opened browser window, locate and click on the `main.ipynb` file to open it.
