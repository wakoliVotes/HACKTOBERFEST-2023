## WeatherApp-Android-Kotlin
In this Hacktoberfest project, we are creating a weather app for a city.
Of the various tools, we are using:
- AndroidStudio
- Kotlin and
- OppenWeatherMap API
### API SetUp
- App uses API from openweather API
- To get the API key visit [OpenWeatherMap](https://openweathermap.org/)
- Create account or login if already have one
- Then goto "My API Keys" under profile name
- Check the API key, copy and paste below in the API section.
### In Manifest
- Allow uses internet permission for access to openweathermap

### Main API Code
- In this project, the API code enabling accessing and retrieving the weather information is the main component
- Upon designing the app outlook with XML, creating API in the Kotlin file (.kt) is essential
- This can be summarized as below:
```kt
    // First, define the City variable

    val CITY: String = "nairobi, ke"

    // Second, use API from openweather API to access weather information

    val API: String = "ADD API KEY HERE"
    
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main)
    // Third, call the created function
        weatherTask().execute()
    }
    // Additional code goes here in the Kotlin file (.kt)

```
### Visuals for Outlook on Different

<img src="https://user-images.githubusercontent.com/77758884/197149496-7fba6f76-9b65-4fba-b412-645ad733fbe7.png" width="218" height="420" > <img src="https://user-images.githubusercontent.com/77758884/197149529-f6ad136d-9cda-4ac6-8b12-5d2a5abe0c48.png" width="218" height="420">
