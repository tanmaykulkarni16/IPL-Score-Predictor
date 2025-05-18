This is a machine learning-based project built to predict the final score of an IPL (Indian Premier League) innings in T20 cricket matches. The model uses real-time match inputs like venue, batting team, bowling team, striker, bowler, current score, overs, wickets, and last 5-over performance to forecast the projected final score.

📌 Project Highlights

Achieved an impressive 90% accuracy in predicting scores compared to actual match results.

Trained on a rich dataset containing 76,015 records of IPL match data.

Developed a clean, user-friendly front-end interface using HTML, CSS, and Flask with dropdown menus for teams, venues, players, and real-time match inputs.

Built and saved Label Encoders for venue, teams, players to handle categorical variables.

Deployed a TensorFlow Keras regression model for score prediction.

🛠️ Tech Stack

Python

TensorFlow / Keras

Flask

HTML, CSS (front-end)

Pandas, NumPy

Scikit-learn (Label Encoding)

Joblib (Model and Encoder serialization)

📌 Workflow

1️⃣ Data Collection and Preprocessing

2️⃣ Feature Engineering (overs, wickets, etc.)

3️⃣ Model Training and Evaluation (TensorFlow Keras model)

4️⃣ Encoders creation for venue, teams, and players

5️⃣ Front-end development using HTML & CSS with Flask integration

6️⃣ Model Deployment with interactive form inputs

📊 Key Features

Predicts final score of a T20 innings based on live match stats.

Clean front-end with dropdown menus for seamless input selection.

Real-time score prediction powered by a trained machine learning model.

Encoders handled via Joblib serialization for consistent input processing.

📢 Acknowledgements

Data Source: Kaggle

Technologies: Python, TensorFlow, Flask, Scikit-learn, HTML, CSS
