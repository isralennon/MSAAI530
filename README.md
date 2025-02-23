## **Human Activity Recognition for Senior Adults Using Smart Devices**

###This project is part of the course USD MS AAI - 530 Data Analytics and Internet of Things - at the University of San Diego (USD).

It was created by Team 2: Ali Mohtat, Israel Romero, and Yaakov Sternberg.

### Installation

To run this project on your local machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/isralennon/MSAAI530.git```
2. Run with Jypiter: https://jupyter.org/install 

## Jupyter Notebook File Location
Our Jupyter Notebook file can be found in this root folder under file name FinalProject.ipynb.
Previous versions of the notebook files and other materials are stored in the Archive subfolder, but they are only for reference and not needed for the final project to work.

## Project Intro/Objective
This project aims to develop a classification model to correctly identify the activity of 18 senior patients measured by 2 accelerometers worn in the thigh and the back. Additionally, an LSTM was used to predict 30 seconds of future accelerometer readings based on the last 2 minutes, and with it predict the next activity for the patient.

### Technologies
- Python
- Jupyter Notebook

#### Dataset
- **Source**: https://doi.org/10.3390/S23052368
- **Size**: The dataset contains 18 files with 45 minutes of activities captured with 2 accelerometers at 50Hz, for a total of over 2.5 million records.

#### Models Used
- **Random Forest:** An ensemble model that builds multiple decision trees and combines them for more stable and accurate predictions.
- **LSTM:** a Long Short-Term Memory algorithms were used in two layers with 64 and 32 units to predict accelerometer activities.

#### License
This project is licensed under the GNU License - see the [LICENSE.txt](LICENSE.txt) file for details.

