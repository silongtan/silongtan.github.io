# E-Commerce

A online web application based on Vue to simulate a online commercial service.

## Implementation
### Frontend
Utilized Vue.js with routers for frontend development. The frontend is a single page application that communicates with the backend through RESTful API. 

### Backend
Utilized Node.js with Express framework for backend development. The backend is a RESTful API that communicates with the frontend through HTTP requests. Sessions are used to maintain user login status, and JWT is used to verify user identity. Load balancing is implemented using Nginx.

### Database
Utilized MongoDB for database development. The database is a NoSQL database that stores the data of the application. Including user information, product information, order information, etc. 

## Test and Deploy

Test is fully automated using Playwright. The test script is located in `test/`. The test script will automatically create a new user, login, add products to cart, and checkout. The test script will also automatically delete the user after the test is completed.
Use the built-in continuous integration in GitLab.

# ML-Project-Accent-ID
## Introduction
For functions in modern smart devices like smart phones or laptops, some voice recognition functions can be enabled to achieve dictation or AI assistant. However, such mechanisms have problems when applied to complicated language environments. In China, there are many different accents or dialects that sounds too different to be processed under a standardized voice library. Many cases have shown that the current voice recognition system is not enough for complex language system, especially for languages that have distinctive accents. To ensure the accuracy of the recognition, this program offers an initial step to the solution: build an identification system which could classify which accent or dialects, so that the device could then find the corresponding database to interpret the commands.

## Model Illustration
![Dialect-ML](https://user-images.githubusercontent.com/70916756/219559776-127becf5-9273-49e6-aa2a-8052a081f540.png)


## Module Used:
Sklearn
Librosa
Numpy

