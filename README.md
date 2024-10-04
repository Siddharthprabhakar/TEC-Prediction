# TEC Prediction

## Overview

The Total Electron Content (TEC) in the ionosphere is influenced by various factors such as solar extreme UV radiation, geomagnetic storms, and atmospheric waves that propagate from the lower atmosphere. This project aims to develop a predictive model for TEC based on these factors, considering seasonality, geomagnetic conditions, and solar activity that impact climate change.

This project has been published in a book chapter titled:
**"Total Electron Content Forecasting in Low Latitude Regions of India: Machine and Deep Learning Synergy"**  
**DOI**: [10.1007/978-3-031-56703-2_9](https://doi.org/10.1007/978-3-031-56703-2_9)  
**Conference**: IACC 2023  
**First Online**: 26 March 2024  
**Pages**: 104–119  
**Contributors**: Pooja Bagane, Chahak Sengar, Sumedh Dongre, Siddharth Prabhakar, Shreya Baldua, Shashidhar Gurav  
**Link to the chapter**: [Springer Link](https://link.springer.com/chapter/10.1007/978-3-031-56703-2_9)

## Guidelines to Run Code

### Required Libraries

Ensure you have the following libraries installed:

- `numpy` 
- `pandas`
- `scikit-learn`
- `tensorflow` (for Keras)
- `matplotlib` 

You can install the required libraries using:

```bash
pip install numpy pandas scikit-learn tensorflow matplotlib
```

### Instructions to Run the Code

1. **Download the Dataset**: Obtain the dataset named `data1.xlsx` and place it in the same directory as your code file.
   
2. **Open Your IDE**: Use any Python IDE such as VSCode, Spyder, or Jupyter Notebook.

3. **Copy the Code**: Create a new Python file and copy the provided code into it.

4. **Save the File**: Save the file with a suitable name and the `.py` extension.

5. **Run the Code**: Execute the code by:
   - Clicking the Run button in your IDE or
   - Running the following command in your terminal:

   ```bash
   python filename.py
   ```

6. **Model Training and Evaluation**: The code will load data from `data1.xlsx`, preprocess it, and train the specified models. Training and validation losses for each model will be printed in the terminal.

7. **Visualizing Results**: The code will also generate and display plots of the training and validation losses for the LSTM, MLP, and CNN models.

---

## Contact

For any inquiries or further information, feel free to reach out to me:
- Email: sid130803@gmail.com
- [LinkedIn](https://www.linkedin.com/in/siddharth1308/)

---
