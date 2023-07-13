<h1 align="center">YandexAPI_WEATHER_Bot </h1>

This telegram bot was created as a practice to learn how to work with APIs, Docker and databases.
It uses Yandex API weather data (https://developer.tech.yandex.ru/) 

The bot implements:
- Binding of the city to the user, and weather browsing;
- Weather display in any other city;
- Saving the history of weather requests and output for the user;
- Admin commands.

Bot link: https://t.me/Weather_pracbot (Not deployed yet.)

#


### :computer: Technologies:
- Aiogram;
- Docker (Compose);
- DataBases (PostgreSQL, SQLAlchemy).
---





### :hammer_and_wrench: Installation:
1. $ pip install -r requirements.txt
2. Create **.env** file in your project directory and add the following variables to the **.env** environment, to work with the python_dotenv library:
  
       - GEO_KEY = <Api key from Yanex.Geocoder>
       - WEATHER_KEY = <Api key from Yanex.Weather>
       - BOT_TOKEN = <API key from Telegram bot>
       - URL = <URL of the PostgreSQL database>  
       - TG_BOT_ADMIN = <Your Telegram ID>  

  **Optional**

3. You can set up a project from docker-compose by using the command "docker-compose up"