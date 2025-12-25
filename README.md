# AgriSmart - Smart & Sustainable Agriculture App 🌾

AgriSmart is a comprehensive Flutter application designed to empower farmers with modern technology. It aids in decision-making through features like disease detection, market price analysis, and personalized advisory services.

## ✨ Features

- **Leaf Disease Scanner**: AI-simulate scanner to detect crop diseases (e.g., Early Blight) and suggest treatments.
- **Market Intelligence**:
    - **Price Prediction**: 7-day forecast for crops like Onion, Potato, Tomato.
    - **Selling Advice**: AI-driven "Sell vs Hold" recommendations.
- **Weather Advisory**: Real-time alerts (Heatwave, Storms) tailored to the user's selected location (State/District).
- **Fertilizer & Pesticide Guide**: Calculator for NPK dosage and organic alternatives.
- **Govt Schemes**: Database of subsidies (PM-KISAN, Fasal Bima Yojana) with application guides.
- **Voice Assistant (AgriBot)**: Offline-capable voice interface for handling queries about prices, weather, and schemes.
- **Smart Plantation Tips**: Location-aware farming advice.
- **Marketplace**: Buy fertilizers/equipment with a complete checkout flow.

## 🚀 Getting Started

### Prerequisites
- Flutter SDK (v3.10+)
- Dart SDK

### Installation

1. **Clone the repository** (or unzip):
   ```bash
   git clone https://github.com/your-repo/agri_smart.git
   ```

2. **Install Dependencies**:
   ```bash
   flutter pub get
   ```

3. **Run the App**:
   - For Web (Recommended for Demo):
     ```bash
     flutter run -d chrome
     ```
   - For Mobile (Android):
     ```bash
     flutter run
     ```

## 📱 Screenshots & Navigation

- **Dashboard**: Central hub accesses all features via a Glassmorphic grid.
- **Profile**: Update your location (Country/State) to see personalized Weather and Plantation data.
- **Mic Button**: Tap the FAB on the dashboard to speak to AgriBot.

## 🛠️ Tech Stack

- **Flutter & Dart**: Core framework.
- **Riverpod**: State management (Cart, etc.).
- **Google Fonts**: Typography (Poppins).
- **SharedPreferences**: Local data persistence (Location, Settings).
- **Mock Data**: Simulation of AI and API responses for offline reliability.

---
Built with 💚 for Indian Agriculture.
