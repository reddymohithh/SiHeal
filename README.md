This project focuses on predicting health risks based on real-time environmental conditions such as temperature, humidity, and air quality. Using a Random Forest algorithm, the system analyzes weather inputs and alerts users if they are at risk for specific health conditions like asthma, bronchitis, or heart disease.

The frontend was developed using React, allowing users to enter personal details (name, date of birth, and health conditions). 
The backend, implemented in Python via Google Colab, uses predefined medical thresholds to compare current weather data with condition-specific limits.

When a match is found between weather data and a user’s risk profile, the system triggers a health alert. 
The model achieved 95% accuracy on both training and test datasets, making it highly reliable for real-time health notifications.

This project was implemented as part of an academic submission and has potential applications in preventive healthcare systems.

How to run the backend code.

We did the backend code in Python on Google Colab. Here's how you can run it.

- Download the Python code using the .ipynb or .py extension.
- Open Google Colab on Google Chrome.
- Click on the file. Then, on the upload notebook option.
- Choose the respective file from your computer.
- The code opens upon successful upload.
- Run the code module by module.

How to run the front-end code.

We did the front-end part in React on Visual Studio. Here's how you can run it.

- Down the zip file.
- Extract contents into a folder.
- Open Visual Studio.
- Click on the file option.
- Then, on the open folder.
- Select the extracted folder.
- In the terminal, run this command - npm run dev
- A local host link shall come. Click on it.
- The output shall open in the chrome.
- Fill in the required details and then the submit button.
- The notification shall pop up.
