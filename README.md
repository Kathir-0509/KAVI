Diabetes Status Checker
Overview
This Streamlit application predicts diabetes status based on user input and visualizes the user's data compared to a dataset. It uses a RandomForestClassifier model trained on the diabetes dataset to make predictions and generate informative visualizations.

Features
User Input: Users can enter their health data via sliders in the sidebar.
Model Prediction: The application uses a RandomForestClassifier to predict diabetes status based on user inputs.
Data Visualization: Provides scatter plots comparing the user's data against the dataset, including features such as Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, and Diabetes Pedigree Function.
Accuracy Display: Shows the model's accuracy on the test set.
Dependencies
Ensure the following libraries are installed:

streamlit
pandas
numpy
matplotlib
seaborn
scikit-learn
You can install these packages using pip:

bash
Copy code
pip install streamlit pandas numpy matplotlib seaborn scikit-learn
Usage
Prepare the Data:

The application reads data from E:/HGS TEAM/phases/diabetes.csv. Ensure this file path is correct or update it as necessary.
Run the Application:

Save the script as app.py or any preferred name.

Run the Streamlit application with the following command:

bash
Copy code
streamlit run app.py
Interact with the App:

Adjust the sliders in the sidebar to input personal health data.
View the visual comparisons of your data against the dataset.
Check the prediction result and the model's accuracy.
Code Overview
Data Handling:

Loads and preprocesses the diabetes dataset.
Removes entries with zero values in critical features.
Model Training:

Trains a RandomForestClassifier on the processed dataset.
User Input:

Collects data from sliders in the sidebar.
Visualization:

Generates scatter plots comparing user input against the dataset for various features.
Output:

Displays the diabetes prediction result and the model accuracy.
Example Output
Prediction: "You Are Not Diabetic" or "You Have Diabetes."
Accuracy: Model accuracy on the test set displayed as a percentage.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For questions or feedback, please contact [Kaviyarasu.LV] at [kaviyarasulv25@gmail.com].
