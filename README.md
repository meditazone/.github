
## MeditaZone APP ✨
![](/profile/resource/bg-github.png)

Meditazone is a complete platform for your mental health needs. This project was inspired by the number of generation Z in Indonesia who have mental health issues, such as anxiety, stress, and depression. We took the initiative to create a mobile application that can help each individual to recognize the type of mental disorders they experience and how to overcome and manage them. We plan to create an innovative way to detect mental disorders, find suitable meditation and the best way to overcome them. We use machine learning, cloud computing, and mobile development to realize this product.

## Team 🎗️
We are from **CH2-PS084**. We consist of 7 people and here is a list of our team members:

|  Name | Student ID | Learning Path | University |
|---|---|---|---|
| Syarifah Fildzah Shahab | M180BSX1586 | Machine Learning | Universitas Airlangga |
| Dimas Dwi Armaisya | M387BSY0135 | Machine Learning | Universitas Nasional |
| Ridhwan Cahyadi | M159BSY1406 | Machine Learning | Universitas Teknologi Digital Indonesia |
| Tri Nugroho Yosef Irawan | C159BSY3513 | Cloud Computing | Universitas Teknologi Digital Indonesia |
| Rio Ferdinand | C159BSY3529 | Cloud Computing | Universitas Teknologi Digital Indonesia |
| David Saputra | A318BSY2271 | Mobile Development | Universitas Sultan Ageng Tirtayasa |
| Rudy Wijaya | A254BSY2018 | Mobile Development | Universitas Mercu Buana |

<br>

## Theme 📖
Human Healthcare and Living Wellbeings

## Thechnical Details 
### Meditazone Android Aplications 📱
Mobile applications are created starting from UI/UX design and a little UX research, then implementing the design results using native Kotlin Android by utilizing supporting libraries such as Retrofit to interact with APIs. 
Meditazone is an application created to help users meditate. This application is built with Kotlin programming language with Jetpack Compose library. In addition, this application has several features including login / registration, displaying all meditation data, playing meditation audio and directing to the Website to view articles.

**APK Demo :** https://shorturl.at/diJ49

#### 1. [MEDITAZONE-MD](https://github.com/meditazone/MEDITAZONE-MD) (main Mobile Devlopment)

**Flow Android**
![Flow Android](/profile/resource/flow.jpg)

## Meditazone Cloud Computing Platform ☁️

We have made a RestAPI server for our Meditazone app using ExpressJS for our main server and Flask for machine learning model deployment. We deploy our backend services using Cloud Run, with the CI/CD pipeline using Cloud Build. We also utilize Google Cloud Storage for file storage, and Cloud SQL for our database server. We also successfully use cloud logging to debug our application.

The backend of cloud computing is implemented using the Google Cloud Platform. We use Cloud Run, Cloud Build, Google Cloud Storage, and Google Cloud SQL.

**API Documentation :** https://documenter.getpostman.com/view/30136709/2s9Ykq5eyN

**Cloud Architecture**
![Cloud Architecture](/profile/resource/cloud_archi.png)

**Database Structure**

![Database Structure](/profile/resource/database.png)

**List Repostory for Cloud Computing**

#### 1. [MEDITAZONE-CC](https://github.com/meditazone/MEDITAZONE-CC) (main backend API)

Implemented using ExpressJS Framework and Sequelize ORM.

#### 2. [ML-API](https://github.com/meditazone/ML-API) (main API for Machine Learning)
Implemented using Flask Framework.

## Meditazone Machine Learning Platform 🏷️
This repository contains 2 machine learning models to predict the vent sentences given by the user with 3 labels in mind, namely Anxiety, Stress, and Depression. We used 2 techniques namely with RNN and transfer learning with fine-tuning using BERT architecture in TensorFlow framework. The models were trained with custom datasets curated specifically for these tasks. In our application, we implement the RNN model because it has a fairly high level of accuracy where in this RNN model there is an Embedding Layer, Bidirectional LSTM (Long Short-Term Memory), Batch Normalization, and Dense Layers that are used.

#### 1. [MEDITAZONE-ML](https://github.com/meditazone/MEDITAZONE-ML) (main Resource Dataset Model)

System Recommendation
Once the mental disorder prediction model detects the type of mental disorder the user is experiencing, the Meditazone recommendation system will recommend appropriate meditations, articles, and quotes. These recommendations will consider the following factors:
1. The type of mental disorder the user is experiencing
2. User needs and preferences

The meditation recommendations will recommend meditations that can help users to manage and overcome their mental disorders. We will also recommend articles that can provide useful information and insights to the user. These articles can help the user to understand his/her mental disorder, how to overcome it, and improve his/her overall mental health. Also, Recommended quotes will recommend quotes that can provide motivation and inspiration to the user.
