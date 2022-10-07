# Estate Filter
<img width="1433" alt="Screen Shot 2022-09-30 at 10 50 28 PM" src="https://user-images.githubusercontent.com/41307771/194508424-bda8ff23-0b4e-4504-945d-21dd469f3505.png">


## About This Project
SITE LINK: http://www.estatefilter.com/

This site is a tool that will enable real estate investors, agents, and other industry professionals to easily and quickly sort through the large number of properties added to the MLS everyday. Users will also be able to view, customize, and create customized analysis for properties, as well as view market data.

## Features
The backend calls an external api daily to update the database with all the current listings in each target area. I implemented a variety financial functions which I integrated into custom model methods so that the properties can be sorted right after the api is called. I also used these functions with custom serializers that allow users to access detailed reports in the frontend, as well as customize those results and perform their own analysis. The analysis is based on similar properties in that area.

The fronted allows users to sort through these properties based on: location, price, and several commonly used real estate metrics. Users can then view detail pages for each of the properties and see up to 30 years projected returns on each property. Users also have the option to customize the assumptions and recalculate based on their own inputs. Users can also view aggregate data for each city and zipcode EstateFilter operates in.

For authentication, I implemented a custom user model in the backend and used Redux Toolkit & Redux Persist for the frontend.

I'm working on fine tuning the financial analysis (particularly rent projections) using machine learning and adding other custom, more advanced functionality for a premium version of the app.


### Built With
-	Django/Django Rest Framework
- ReactJs
- Redux Toolkit (Authentication)
- Postgresql
- Heroku


## Contact
Sam Recile - recilesam@gmail.com

<img width="1426" alt="Screen Shot 2022-10-06 at 10 42 50 PM" src="https://user-images.githubusercontent.com/41307771/194512103-6414ee2a-5948-4108-938d-90130acc4119.png">

<img width="1436" alt="Screen Shot 2022-10-06 at 10 43 11 PM" src="https://user-images.githubusercontent.com/41307771/194512184-e7208d3d-f1c0-4f28-894c-2b20f0a2e4c8.png">


