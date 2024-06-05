# Weather Application

## Project Overview
This is an Android application designed to fetch and display weather details based on the user's input of a city name and an optional country code. The application utilizes a simple and clean user interface, providing a seamless experience for users to get real-time weather information.


![Screenshot 2024-06-05 195710](https://github.com/yasanthae/Weather-Application/assets/92664737/d1990ea5-b038-4348-949c-78196273fdda)
![Screenshot 2024-06-05 195752](https://github.com/yasanthae/Weather-Application/assets/92664737/f622fecd-469e-4526-b48b-11c22feae8ae)



## Features
- **User Input for City and Country Code:** Users can enter the city name and optionally the country code to get specific weather details.
- **Fetch Weather Details:** Upon clicking the "Get Weather Details" button, the application retrieves and displays weather information.
- **Scroll View for Results:** The weather details are displayed in a scrollable text view to accommodate lengthy information.
- **Ad Integration:** The app integrates a banner ad at the bottom of the screen using Google AdMob.
- **Responsive UI:** The UI is designed to be responsive with proper use of layout weights and margins.

## Setup Instructions
### Prerequisites
- **Android Studio:** Ensure you have Android Studio installed on your machine.
- **API Key:** You need an API key from a weather service provider (e.g., OpenWeatherMap).
- **Google AdMob Account:** You need to create an account with Google AdMob and obtain an Ad Unit ID for the banner ad.

### Step-by-Step Setup
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/your-repository/weather-app.git
   ```
   
2. **Open the Project in Android Studio:**
   - Start Android Studio and select `Open an existing Android Studio project`.
   - Navigate to the cloned repository and open it.

3. **Add API Key:**
   - Obtain an API key from a weather service provider.
   - Add the API key in the `strings.xml` file:
     ```xml
     <string name="weather_api_key">YOUR_API_KEY_HERE</string>
     ```

4. **Configure Google AdMob:**
   - Sign up for Google AdMob and create a new Ad Unit.
   - Add the Ad Unit ID in the `strings.xml` file:
     ```xml
     <string name="banner_adunit_id">YOUR_AD_UNIT_ID_HERE</string>
     ```

5. **Build and Run the Project:**
   - Connect your Android device or start an emulator.
   - Click on the `Run` button in Android Studio.

### Project Structure
- **MainActivity.java:** Handles the main logic of fetching weather details and updating the UI.
- **activity_main.xml:** Defines the UI components and layout of the main screen.
- **strings.xml:** Contains all the string resources used in the application, including the API key and Ad Unit ID.
- **AndroidManifest.xml:** Configures essential information about the application, including permissions and activities.

### Additional Features
- **Input Validation:** Basic validation to ensure the city name is not empty before making the API call.
- **Error Handling:** Handles errors gracefully, displaying appropriate messages to the user in case of issues such as network errors or invalid input.
- **Loading Indicator:** A loading indicator can be implemented to show progress while fetching data from the weather API.
- **Improved UI/UX:** Further enhancements can be made to the UI/UX, such as animations, themes, and user preferences.

### Future Enhancements
- **Forecast Feature:** Adding a feature to display weather forecasts for upcoming days.
- **Location Services:** Implementing GPS-based location services to fetch weather details based on the user's current location.
- **Advanced Weather Details:** Providing more detailed weather information such as humidity, wind speed, and UV index.

## Conclusion
This Weather Application provides a basic yet functional solution for users to fetch and view weather details. With its clean interface and straightforward functionality, it serves as a solid foundation for further enhancements and features. Follow the setup instructions carefully to get the app up and running on your device.
