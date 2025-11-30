# 🍿 VibBar AI

**An intelligent movie & TV show discovery agent powered by Google Gemini 2.0 Flash.**

Unlike traditional search engines that rely on keywords, this agent understands **context, vibe, and intent**. It acts as a personalized concierge that can filter content strictly by format (Movie vs TV), suggest watch orders for franchises, and curate recommendations based on abstract queries like "Psychological thrillers like Death Note".

---

## 🚀 Key Features

### 🧠 1. Smart Reasoning Engine
- **Vibe Matching:** Understands complex queries like *"Mind-bending sci-fi movies about space"* and provides a reasoned explanation for each pick.
- **Strict Format Enforcement:** Solves the common hallucination problem. If you ask for a *"Movie"*, it strictly filters out TV shows, and vice versa.
- **Franchise Knowledge:** Can generate complete watch orders for large universes like *Marvel* or *The Sandman* (including spin-offs).

### 💎 2. Premium User Experience
- **Cinematic AMOLED UI:** A custom-styled Streamlit interface with a pitch-black theme, rounded aesthetics, and immersive grid layouts.
- **Smart Chips:** Dynamic suggestion chips that refresh on every reload to give you new ideas.
- **Deep Drill-Down:** Click "View Details" to see Cast, Runtime, Budget, Revenue, and check **OTT Availability** (e.g., Netflix/Prime) in your region.

### 📝 3. Memory & Watchlist
- **Session-Based Memory:** Users can add movies/shows to a sidebar Watchlist to keep track of their discoveries during the session.
- **Auto-Retry Logic:** Built-in handling for API rate limits (429 errors) ensures a smooth experience without crashes.

---

## 🛠️ Tech Stack

- **AI Model:** Google Gemini 2.0 Flash (via `google-generativeai`)
- **Data Source:** The Movie Database (TMDB) API
- **Frontend:** Streamlit (Python)
- **Deployment:** Docker on Hugging Face Spaces / Streamlit Cloud

---

## 📸 How to Use

1.  **Search by Vibe:** Try *"Movies like Interstellar"* or *"Comedy anime for beginners"*.
2.  **Filter Strictly:** Try *"Hindi movies under 90 minutes"* or *"TV Shows like F1"*.
3.  **Explore:** Click on any poster to view the trailer and streaming details.
4.  **Save:** Click **"➕ Add to Watchlist"** to save your favorite picks.

---

## 🔮 Future Roadmap

Currently, the app uses **Session State** for instant, privacy-focused memory. In the next major update, I plan to integrate:
- **Firebase Authentication** for permanent user accounts and cross-device syncing.
- **Custom React Frontend** to overcome Streamlit's styling limitations for a truly pixel-perfect cinematic experience.

---

*Created for the Google AI Agents Intensive Course 2025.*
