# Live Tracker 

Live Tracker is a real-time Android application developed using Flutter and Flask API for live location tracking. This project implements dynamic path tracing with second-by-second updates of latitude and longitude, utilizing the Folium library to create interactive maps for precise location marking.

## Features

- **Real-time Location Tracking**: Track live locations with second-by-second updates.
- **Dynamic Path Tracing**: Visualize the path taken in real-time.
- **Interactive Maps**: Use Folium to create dynamic maps that mark precise locations.

## Tech Stack

- **Frontend**: Flutter
- **Backend**: Flask API
- **Programming Language**: Python
- **Libraries**: Folium for map visualization
- **Techniques**: Polling for real-time data processing

## Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/Maitrey27/Live-Tracker.git
    cd RealTrack
    ```

2. **Backend Setup**
    - Create a virtual environment
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
    - Install the required packages
    ```bash
    pip install -r requirements.txt
    ```
    - Run the Flask API
    ```bash
    python app.py
    ```

3. **Frontend Setup**
    - Navigate to the Flutter project directory
    ```bash
    cd flutter_app
    ```
    - Get the required dependencies
    ```bash
    flutter pub get
    ```
    - Run the Flutter app
    ```bash
    flutter run
    ```

## Usage

1. Ensure the Flask server is running.
2. Launch the Flutter app on your Android device or emulator.
3. The app will start tracking and updating the location in real-time, displaying the path on an interactive map.

## Demo

Include screenshots or a GIF demonstrating the app in action.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Project Link: [https://github.com/Maitrey27/Live-Tracker](https://github.com/Maitrey27/Live-Tracker)
