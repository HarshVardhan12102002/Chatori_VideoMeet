# Chatori VideoMeet

*Chatori VideoMeet* is a web-based video conferencing application that enables seamless peer-to-peer communication using WebRTC. Designed with simplicity in mind, the app offers essential controls for managing video meetings and is integrated with Agora SDK for robust real-time interaction.

## Key Features
- **Peer-to-peer video calls** powered by WebRTC for a direct, secure connection.
- **Agora SDK integration** to ensure smooth, real-time audio and video communication.
- **User-friendly UI** with a clean, responsive design for effortless navigation.

## Prerequisites
Before getting started, make sure to:
1. [Sign up](https://www.agora.io) for an Agora account.
2. Generate an **APP ID** and **Temporary Token** for your application.

## Installation

1. **Clone the repository** to your local machine:

    ```bash
    git clone https://github.com/HarshVardhan12102002/Chatori_VideoMeet.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd Chatori_VideoMeet
    ```

3. **Update the configuration** in `main.js` by replacing the placeholders with your actual values:

    ```js
    let APP_ID = "YOUR-APP-ID";
    ```

4. **Launch the application** by opening `index.html` in your preferred browser.

## Technologies Used
- **HTML** for structure
- **CSS** for styling
- **JavaScript** for functionality
- **Agora SDK** for real-time communication
- **WebRTC** for peer-to-peer video calling

## Project Structure
A quick overview of the key files in the project:

- `index.html`: The main webpage for hosting video meetings.
- `main.js`: Contains the core logic for WebRTC communication and Agora integration.
- `main.css`: Stylesheet that defines the look and feel of the application.
- `lobby.html`: Pre-meeting lobby page.
- `lobby.css`: Stylesheet for the lobby page design.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
