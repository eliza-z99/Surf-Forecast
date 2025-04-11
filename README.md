🌊 Surfline LED Visualizer
This project is a real-time Surf Condition Visualizer built on an ESP32, using live or simulated surf data (wave height, tide, and wind speed) for three different beaches. It transforms that data into a vibrant LED display, giving surfers or hobbyists a quick-glance view of current ocean conditions — without opening an app.

🔧 Features
Three Beach Selector Buttons – Instantly switch between Beach A, B, or C.

Wave Height LEDs – Low, Medium, or High indication via dedicated LEDs.
Wind Speed LEDs – Visual indication of calm, breezy, or windy conditions.
Tide Level LEDs – Shows if the tide is low, medium, or high.
Individual Surf Rating LEDs – A dedicated LED shows the overall surf rating (good/okay/bad) for each beach.
RGB Indicator (optional upgrade) – A global surf status light changes color (green/yellow/red) based on the selected beach’s rating.

⚙️ Tech Stack
Microcontroller: ESP32
Language: C++ (Arduino framework)
Inputs: Push buttons for beach selection
Outputs: LEDs for surf metrics and status indicators

💡 Goals
This project was designed to:
Visualize real-time data in a tangible, embedded system format
Practice GPIO and edge detection logic using ESP32
Create an engineering showcase project with real-world use case appeal
Demonstrate embedded systems and UI feedback in a minimalist form
