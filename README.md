# EnviroGo 2.0 🌍

EnviroGo empowers you to make simple, personalized lifestyle changes that positively impact the environment. By combining local weather data and AI, EnviroGo generates actionable sustainability tips tailored to your location.

## Features

- 🌦️ Uses OpenStreetMap and Open-Meteo APIs for accurate local weather and environmental data.
- 🤖 AI-powered (Gemini) tips for small, medium, and large lifestyle changes.
- 🏙️ Reverse geocoding to show the exact location for which tips are generated.
- 📝 Tips are rendered with Markdown formatting and displayed in individual cards.
- ⚡ Responsive, accessible, and easy to use.

## Screenshot

![EnviroGo Screenshot](screenshot.png)
<!-- Add a screenshot.png to your repo root for best effect -->

## Setup & Usage

1. **Clone or Download** this repository.
2. **Open `index.html`** in your web browser (no server required).
3. **Enter your city or location** and click **Generate Tips**.
4. View personalized environmental tips based on your local weather, displayed in beautiful cards.

### Example

```
Enter your city: San Francisco, CA
[Generate Tips]
```
You will see:
- "Showing results for: San Francisco, California, United States"
- Cards with actionable tips for small, medium, and large lifestyle changes.

> **Note:** You need a valid Gemini API key for AI-powered tips. Replace the placeholder in the code with your own key if needed.

## Dependencies

- [OpenStreetMap Nominatim API](https://nominatim.openstreetmap.org/)
- [Open-Meteo API](https://open-meteo.com/)
- [Google Gemini API](https://ai.google.dev/)
- [marked.js](https://marked.js.org/) for Markdown rendering

## Google Gemini API Key

- There is a Google Gemini API Key inside the `index.html` file. The key is valid, however, please don't use it in your personal projects. Let's keep this open for educational use only—thank you for your trust!

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements, bug fixes, or new features.

## License & Disclaimer

This project is provided **for educational purposes only**.  
**Do not** use the included Gemini API key for commercial or personal projects.

---
EnviroGo © 2025
