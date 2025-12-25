# AgriSmart - Hackathon Submission Report 🌾

**Project Name:** AgriSmart
**Theme:** Sustainable Agriculture & Rural Development
**Platform:** Flutter (Mobile & Web)

---

## 1. Problem Statement ❓
Indian farmers often face challenges due to:
*   **Lack of Real-time Information**: Unpredictable weather and market rates.
*   **Crop Diseases**: Inability to identify diseases early, leading to crop loss.
*   **Knowledge Gap**: Unawareness of government schemes (PM-KISAN) and modern farming techniques.
*   **Access to Resources**: Difficulty in finding correct fertilizers and organic alternatives.

## 2. Our Solution: AgriSmart 💡
**AgriSmart** is a "Super App" for farmers. It bridges the gap between technology and traditional farming by providing a unified platform for:
*   **Decision Support**: AI-based disease detection and crop recommendations.
*   **Financial Security**: Market price predictions and subsidy information.
*   **Advisory**: Hyper-local weather alerts and plantation tips.
*   **Accessibility**: Voice-enabled assistant ("AgriBot") for illiterate users.

---

## 3. Key Workflows & Features 🚀

### A. Smart Disease Detection (AI Scanner)
*   **Workflow**:
    1.  User opens **Scanner**.
    2.  Captures photo of affected leaf (e.g., Tomato).
    3.  **Analysis**: App simulates AI detection (Mocked for prototype).
    4.  **Output**: Identifies "Early Blight" and prescribes "Copper Fungicide".

### B. Intelligent Market Analysis
*   **Workflow**:
    1.  User selects **Analytics** from Dashboard.
    2.  Chooses crop (e.g., Onion).
    3.  **Prediction**: App shows Today's Rate vs. 7-Day Forecast.
    4.  **Verdict**: Suggests "Hold" or "Sell" based on price trends.

### C. Hyper-Local Weather Advisory
*   **Workflow**:
    1.  User sets Location (e.g., Rajasthan) in **Profile**.
    2.  **Logic**: App fetches state-specific conditions.
    3.  **Output**:
        *   If Rajasthan: "Heatwave Alert" -> Advise "Increase Irrigation".
        *   If Punjab: "Storm Alert" -> Advise "Stop Spraying".

### D. Voice Assistant (AgriBot)
*   **Goal**: Accessibility for all.
*   **Workflow**:
    1.  User taps **Mic Button** on Home.
    2.  Speaks query (e.g., "Mandi bhav?").
    3.  **Offline Processing**: App matches keywords locally.
    4.  **Response**: Speaks back the answer instantly.

### E. Government Schemes Portal
*   **Feature**: Unified information center.
*   **Content**: Details on **PM-KISAN**, **Fasal Bima Yojana**, and **Soil Health Cards**.
*   **Details**: Eligibility criteria, application steps, and deadlines.

### F. Smart Plantation Tips
*   **Workflow**:
    1.  App detects User Location.
    2.  **Recommendation**: Suggests best crops for the season (e.g., Wheat in Winter for Punjab).
    3.  **Organic Tips**: Promotes sustainable practices like vermicomposting.

---

## 4. Technical Stack 🛠️

*   **Framework**: Flutter & Dart (Cross-platform).
*   **State Management**: Riverpod.
*   **Local Storage**: SharedPreferences (for offline location/settings).
*   **UI/UX**: Glassmorphism design, Google Fonts (Poppins), Responsive Layouts.
*   **Architecture**: Modular (Screens, Models, Providers).

## 5. Future Roadmap 🔮
*   **IoT Integration**: Connect with soil moisture sensors.
*   **Real-time Backend**: Firebase integration for live community chat.
*   **Language Support**: Full translation into 10+ Indian regional languages.

---

*Built with ❤️ for the Future of Farming.*
