function weather() {
String apiKey = "Key123123123"
WeatherAPI weatherAPI = WeatherAPI(apiKey)
return weatherAPI.getTodayWeather()
}
