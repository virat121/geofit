
# GeoFit

This project is a fitness tracking application that allows users to log workouts, view their details on a map, and receive motivational quotes. It utilizes modern JavaScript features, Object-Oriented Programming (OOP), and API fetching to provide a comprehensive user experience.


## Features

- Workout Tracing
- Map Integeration (Leaflet.js Library)
- API Integeration
- Local Storage to trace the prevous response


## API Reference
https://api-ninjas.com/api/quotes
#### Get data

```http
 fetch(apiUrl, {
      method: 'GET',
      headers: {
        'X-Api-Key': apiKey
      }
    })
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**.  |

