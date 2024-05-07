# Nirnaya

Nirnaya is an innovative project aimed at revolutionizing the way farmers choose crops and make decisions about their farming operations. With the use of cutting-edge technology and machine learning algorithms, Nirnaya provides farmers with a comprehensive and accurate picture of their farm's potential. This includes soil analysis, location-based data, and rainfall information, which can be used to determine the most suitable crops for a given area.

## Features of the Project
1. Crop Prediction based on Locality and seasons.
2. Crop Prediction based on the soil fertility
3. Crop Price Prediction.

### Project is live at : https://agrovision-trinit.netlify.app/

## API's of our project.

## List of API's

1. GET `/api/soilcrop` - Provides optimum soil conditions for each crop.
2. POST `/api/soilcrop` - It takes soil Nutrients as a parameter and predicts suitable and alternative crops.
3. GET `/api/cropanalysis` - Provides top most crops grown in states of India. (Note: Crops array be more than 10 in some cases)
4. POST `/api/croplocation` - Crop prediction based on locality and season.
5. GET `/api/getlocations` - List of state-wise districts that are used in our project.
6. GET `/api/cropprice` - Provides Top5, Bottom5 crops of this month and also Six months forecaster.
7. GET `/api/cropprice/<cropname>` - Analytics of individual crop.

## Interface of the project
### Homepage
![Homepage](https://github.com/satyamsoni228/Nirnaya-new/assets/62495706/b7fa225b-1ad2-45bc-8c69-cc857d199143)

### Crop Prediction based on locality and seasons
![Crop Prediction based on locality and seasons](https://github.com/satyamsoni228/Nirnaya-new/assets/62495706/efbf3abf-d042-4d29-86d8-550fb4ae068e)

### Crop prediction based on soil fertility
![Crop prediction based on soil fertility](https://github.com/satyamsoni228/Nirnaya-new/assets/62495706/934aa542-d30a-4f88-b976-9e05c39e1d58)

### Crop Analytics.
![Crop Analytics](https://github.com/satyamsoni228/Nirnaya-new/assets/62495706/1071a75d-240a-4188-bbfc-36613388ccb7)


### Individual Crop Prediction - Ex: Arhar
![Individual Crop Prediction (Arhar)](https://github.com/satyamsoni228/Nirnaya-new/assets/62495706/57844ff5-0b91-4c94-9552-f4987daeaf8b)


## Run Locally

Clone the project

```bash
  git clone https://github.com/satyamsoni228/Nirnaya.git
```

Go to the Backend project directory

```bash
  cd Nirnaya/server/
```

Install dependencies

```bash
  pip install -r requirements.txt
```

Start the server(backend)

```bash
  python app.py
```

Go to the Frontend project directory

```bash
  cd client
```
Install dependencies

```bash
  npm install -g vite
```
Start the frontend

```bash
  npm run dev
```
## Results

### Crop Recommendation

| Algorithm   | Accuracy | Precision|Recall|F1-Score|
| :---        |    :----:   | :---: | :---: | :---: |
|SVM|97.82|0.99|0.98|0.99|
|Random Forest|97.72|0.98|0.98|0.98|
|Decision Tree|95.22|0.96|0.95|0.95|
| Logistic Regression | 94.54 | 0.95   |0.95| 0.94  |


## Authors

- [@satyamsoni](https://github.com/satyamsoni228)
- [@tanmayshahi](https://github.com/tanmayshahi)
- [@nehaahirwar](https://github.com/neha-ahirwar)

## Feedback

If you have any feedback, please reach out to us at ssoni6149@gmail.com
