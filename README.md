# old-Chain-Vaccine-Monitoring

![image](https://github.com/ksparsh443/Vaccine-Cold-Chain-Monitoring/assets/84833857/734fb647-8d52-4905-bf51-72e9ffaef3b5)



Cold Chain Vaccine Monitoring System

During the COVID-19 pandemic, the vaccine industry suffered losses due to issues with storing and maintaining vaccines properly. The traditional method of monitoring vaccine temperatures manually had flaws, leading to lower vaccine effectiveness. This paper introduces a solution using fog computing and LoRaWAN technology. The system uses wireless sensors to monitor temperature and humidity, enabling real-time tracking of vaccine storage and transport conditions. A web-based dashboard offers insights and alerts for any deviations. Machine learning techniques are also applied to improve storage efficiency and quality control. The system aims to enhance vaccine quality, reduce waste, and optimize cold chain management, especially in challenging remote areas, as demonstrated through simulated testing.
## Installation

!pip install numpy
!pip install pandas
!pip install scikit-learn
!pip install joblib

# Install required library to access Google Drive from Colab
!pip install gdown

import gdown


## Importing Dataset
# Provide the Google Drive file ID for 'DATA-large.CSV'
file_id = '13STraJ_TlmhNoVKDlS6oRjW49l3OukUR'

# Download the file
output_file = 'DATA-large.csv'
gdown.download(f'https://drive.google.com/uc?id={file_id}', output_file, quiet=False)

