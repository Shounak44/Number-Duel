# Number-Duel

🔗 Play the game:
https://wonderful-belekoy-932bc0.netlify.app/

Number Duel is a fast-paced player-vs-player number guessing game featuring competitive ranked matches, online multiplayer, and multiple ways to play. Challenge friends in private rooms, compete against bots with three difficulty levels, or test your skills across different game modes. The game includes power-ups, daily challenges with rewards, leaderboards, and a currency system used to unlock characters and visual themes. Players can sign in quickly using their Google account and jump straight into the action.

🚀 Setup

### 1. Create a Firebase project
1. Go to [https://console.firebase.google.com](https://console.firebase.google.com)
2. Create a new project
3. Enable **Authentication** → Sign-in method → **Google**
4. Enable **Realtime Database** → Start in test mode
5. Go to **Project Settings → Your Apps** → Add a Web App
6. Copy your config object

2. Add your Firebase config
Open `index.html` and find this block near the top of the `<script>` tag:

```js
const app = initializeApp({
  apiKey:            "YOUR_API_KEY",
  authDomain:        "YOUR_PROJECT_ID.firebaseapp.com",
  databaseURL:       "https://YOUR_PROJECT_ID-default-rtdb.YOUR_REGION.firebasedatabase.app",
  projectId:         "YOUR_PROJECT_ID",
  storageBucket:     "YOUR_PROJECT_ID.firebasestorage.app",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId:             "YOUR_APP_ID",
});
```

eplace each placeholder with your real values from Firebase Console.

### 3. Run
Just upload `index.html` in netlify — you're good to go.
