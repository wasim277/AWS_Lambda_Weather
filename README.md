# Weather Forecast Email Notification

## Project Overview
The Weather Forecast Email Notification project is designed to provide users with timely weather updates directly to their inbox. It retrieves a 3-day weather forecast for a specified city using the OpenWeatherMap API and sends this information via email using the Outlook SMTP server. This project is particularly useful for individuals who want to stay informed about weather conditions without needing to check a weather website or application daily.

## Features
- **3-Day Weather Forecast**: Fetches and displays the current day's weather along with forecasts for the next two days.
- **Email Notifications**: Automatically sends the weather report to the user's email address.
- **Customizable City**: Users can easily change the city for which they want to receive weather updates.
- **Simple Setup**: Straightforward installation and configuration process.

## How It Works
1. **Fetch Weather Data**: The script makes a request to the OpenWeatherMap API to get weather data for the specified city.
2. **Parse Response**: It processes the API response to extract relevant weather details, including temperature and weather conditions.
3. **Format Report**: The weather information is formatted into a readable report that includes today's date and weather, as well as forecasts for the following two days.
4. **Send Email**: The formatted report is sent via email using the SMTP protocol through an Outlook account.

## Getting Started

### Prerequisites
- Python 3.x
- `requests` library (install using `pip install requests`)

### Configuration
1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
