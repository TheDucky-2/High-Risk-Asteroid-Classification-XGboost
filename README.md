# High Risk Asteroid Classification

## Project Overview
This project builds a machine learning model to classify asteroids as **high risk** or **low risk** based on their physical and orbital characteristics. The goal is to identify potentially hazardous asteroids that may pose a threat to Earth, enabling better monitoring and early warning.

---

## Features & Data
- Uses features such as asteroid size, velocity, trajectory, and distance from Earth.
- Dataset includes labeled examples for training and testing.
- Data preprocessing includes cleaning and normalization.

---

## Model
- Classification is done using **XGBoost**.
- Performance evaluated with **Accuracy**, **Precision**, **Recall**, and **F1 Score**.
- Focus on maximizing recall to reduce missed hazardous asteroids, while working to improve precision.

---

## Installation & Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/TheDucky-2/High-Risk-Asteroid-Classification-XGboost.git
    cd High-Risk-Asteroid-Classification-XGboost
    ```
2. (Optional) Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

---

## Usage
- Open the Jupyter notebook `Near Earth Close Approach Objects.ipynb` in JupyterLab or Jupyter Notebook.
- Run the cells sequentially to:
  - Preprocess the data
  - Train the XGBoost model
  - Evaluate the model performance
- You can modify hyperparameters and rerun the relevant cells to tune the model.


---

## Results
- Accuracy: ~78%
- Recall: ~94%
- Precision: ~36%
- F1 Score: ~52%

---

## Future Work
- Explore other models and feature engineering.
- Tune threshold to balance precision and recall.
- Add real-time data integration.

---

## Contributing
Feel free to submit issues or pull requests!

---

## License
MIT License

---

## Contact
Contact Kshitij Sharma at Ksharma199@protonmail.com for questions or collaboration.
