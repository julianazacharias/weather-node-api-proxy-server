# Weather API Proxy Server

Server used for hiding API keys, rate limiting and caching. 
This project uses the [OpenWeather API](https://openweathermap.org/api)

### Install dependencies

```bash
npm install
```

### Run on http://localhost:5000

```bash
npm run dev
```

### How to add public API info:

If the public API URL is **https://api.openweathermap.org/data/2.5/weather?q={city}&appid={APIkey}**

Insert your API KEY value on **.env** file:

- API_BASE_URL = "https://api.openweathermap.org/data/2.5/weather"
- API_KEY_NAME = "appid"
- API_KEY_VALUE = "YOUR API KEY"
