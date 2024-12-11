# Flight Path Visualizer - SkyNav AI ✈️

SkyNav AI is an advanced flight navigation system that visualizes and optimizes flight routes between multiple destinations. This project integrates **custom-built data structures** with **interactive graphics** using **SFML** to provide users with an engaging and highly functional flight planning experience.

## 🚀 Features

### 1. **Flight Data Representation**
- Parses flight data from `Flights.txt` into a **graph** where:
  - Vertices represent cities.
  - Edges represent flights with details like airline name, flight duration, and travel dates.
- **Graphics:** Visualizes the graph with nodes as cities and edges as flight routes.
  - Edge colors and widths indicate flight durations.
  - Tooltips display flight details.

### 2. **Flight Booking System**
- Allows users to book flights, displaying direct and connecting routes with feasible layover times.
- **Graphics:** Highlights all possible routes from source to destination.

### 3. **Shortest and Cheapest Route Finder**
- Implements **Dijkstra’s** and **A*** algorithms to calculate optimal paths.
- Utilizes **priority queues** (custom heaps) for efficient route discovery.
- **Graphics:** Animates the real-time pathfinding process with glowing highlights for the final path.

### 4. **Custom Preferences**
- Users can filter results based on preferred airlines or transit cities.
- **Graphics:**
  - Marks preferred cities with unique icons.
  - Highlights recalculated paths based on user preferences.

### 5. **Layover Management**
- Uses **queues** to manage and calculate layover times efficiently.
- **Graphics:**
  - Visualizes layovers with dashed lines.
  - Dynamically updates layover details as users explore routes.

### 6. **Advanced Route Generation**
- Manages multi-leg journeys dynamically using a **linked list**.
- **Graphics:**
  - Represents each trip segment with arrows.
  - Allows users to interactively adjust routes.

### 7. **Subgraph Query Generation**
- Generates subgraphs for user-specific queries like preferred airlines or transit routes.
- **Graphics:**
  - Displays excluded cities with reduced opacity.
  - Highlights active routes for better focus.

## 🛠️ Technologies Used
- **Graphics Framework:** SFML for visualization.
- **Programming Language:** C++ (Custom data structures only).
- **Algorithms:** Dijkstra’s, A*, and bidirectional search for optimized pathfinding.

## 📁 File Structure
- `Flights.txt` and `HotelCharges.txt`: Input data files.
- `src/`: Contains all modular C++ source code files.
- `docs/`: Documentation, including a PDF of GPT prompts used during development.

## 💻 How to Run
1. Clone the repository.
2. Install [SFML](https://www.sfml-dev.org/).
3. Compile the C++ files using your preferred compiler (e.g., g++).
4. Run the executable and explore the features!

## 🏆 Innovation Highlights
- Real-time visualization of algorithms.
- Dynamic flight and layover management using custom data structures.
- Personalized flight planning with filtered queries and preferences.

## 🤝 Contributions
Feel free to fork the repository and suggest improvements. Let's build better travel tools together!

## 📥 Download the Code
To download the code, click on this [link](https://drive.google.com/drive/u/0/folders/1lgHv5jWi5XBilKp87ml0nJ9npZgAlQ2M).

## 👀 View the Code Without Downloading
To view the code without downloading, click on this [link](https://drive.google.com/drive/u/0/folders/1lgHv5jWi5XBilKp87ml0nJ9npZgAlQ2M).

## 📸 Screenshots
![WhatsApp Image 2024-12-11 at 11 04 27 PM](https://github.com/user-attachments/assets/e7a71e7e-63d7-41e5-af86-6ee1d30b621a)

![WhatsApp Image 2024-12-11 at 11 04 27 PM (2)](https://github.com/user-attachments/assets/ec9b1023-0aa8-4d3d-ae8a-90d2337af4d5)

![WhatsApp Image 2024-12-11 at 11 04 29 PM](https://github.com/user-attachments/assets/59464c62-b690-4474-b723-6e2695366e57)

![WhatsApp Image 2024-12-11 at 11 04 28 PM (1)](https://github.com/user-attachments/assets/cdb61adc-5779-404d-85c3-ec590c85cb82)

![WhatsApp Image 2024-12-11 at 11 04 28 PM](https://github.com/user-attachments/assets/e90d1157-55fb-44af-8dad-a130eb83ecb6)

![WhatsApp Image 2024-12-11 at 11 04 27 PM (1)](https://github.com/user-attachments/assets/470e27dc-5d22-4da2-8d66-802e8235f72f)






