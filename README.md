    🚗 CO2 Emissions & Ford Focus Machine Learning Model

This repo contains a machine learning model trained on a dataset of CO2 emissions and Ford Focus vehicle features, using classic ML techniques without deep learning.

  🚀 Technologies Used

  🐍 Python

  🗃️ Pandas (Data processing)

  🔢 NumPy (Mathematical operations)

  🤖 Scikit-learn (Machine learning algorithms)

  📊 Matplotlib & Seaborn (Data visualization)
  
    📂 Dataset

 --- Ford Focus Vehicle Data:

🚗 model: Vehicle model (Focus)

📅 year: Manufacturing year

💰 price: Vehicle price (GBP)

⚙️ transmission: Transmission type (Manual, Automatic, Semi-Auto)

📏 mileage: Vehicle mileage (in miles)

⛽ fuelType: Fuel type (Petrol, Diesel)

💸 tax: Annual tax (GBP)

🔄 mpg: Fuel efficiency (miles per gallon)

🚀 engineSize: Engine size (liters)

--- CO2 Emissions and Fuel Consumption Data:

📅 Model_Year: Manufacturing year

🚀 Engine_Size: Engine size (liters)

🔩 Cylinders: Number of cylinders

🏙️ Fuel_Consumption_in_City (L/100 km): City fuel consumption

🛣️ Fuel_Consumption_in_City_Hwy (L/100 km): Highway fuel consumption

⚡ Fuel_Consumption_comb (L/100km): Combined fuel consumption

🌍 CO2_Emissions: CO2 emission amount

💨 Smog_Level: Air pollution level



The dataset has been cleaned and preprocessed before training the model.

    🏗️ Model Training

The project uses Polynomial Regression to capture non-linear relationships by increasing the polynomial degree. Poly Regression has been applied to both datasets.

The dataset is split into training and test sets, and model accuracy is evaluated using various metrics.

    🛠️ Installation & Usage

To run this project on your local machine, follow these steps:

    📥 Clone the repository:

git clone <repo-link>
cd <repo-name>
  
    📦 Install the required Python libraries:

pip install -r requirements.txt

  🏃 Run the model:

python train.py

    📊 Results & Outputs

The model's performance has been evaluated using various metrics and visualized. Results can be found in the results folder as graphs and analyses.

    🤝 Contributions

If you would like to contribute, feel free to fork the repo or submit a pull request.
