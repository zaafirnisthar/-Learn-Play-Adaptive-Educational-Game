🎮 Learn & Play — Adaptive Educational Game


An interactive, browser-based educational game for young learners, featuring adaptive difficulty, multiple mini-games, and progress tracking.



📖 About

Learn & Play is an adaptive educational game built with React and TypeScript. Players progress through five language and literacy mini-games that automatically adjust difficulty based on their performance. A built-in dashboard tracks scores and time spent learning across sessions.

This project was developed as a group assignment for CCC1243 Artificial Intelligence at Albukhary International University (AIU).



🕹️ Mini-Games

GameDescription🔤 Alpha GameAlphabet recognition and ordering❓ Missing GameFill in the missing letter or word🃏 Match GameCard matching for vocabulary📝 Sentence GameBuild correct sentences from words🔀 Scramble GameUnscramble jumbled words


✨ Features


🧠 Adaptive difficulty — game difficulty adjusts in real time based on player performance
📊 Progress dashboard — tracks score and total time played across sessions
🎵 Background music — toggleable in-game music for an immersive experience
☁️ Animated UI — smooth transitions and animations powered by Framer Motion
📱 Responsive design — works on desktop and mobile browsers



🛠️ Tech Stack

LayerTechnologyFrameworkReact 18 + TypeScriptBuild ToolViteStylingTailwind CSSAnimationsFramer MotionUI ComponentsRadix UI + shadcn/uiRoutingWouterStateReact hooks + localStorage


🚀 Getting Started

Prerequisites


Node.js v18 or higher
npm or yarn


Installation

bash# Clone the repository
git clone https://github.com/YOUR_USERNAME/learn-and-play.git
cd learn-and-play

# Install dependencies
npm install

# Start the development server
npm run dev

Open your browser and go to http://localhost:5173

Build for Production

bashnpm run build
npm run serve


📁 Project Structure

src/
├── components/         # Shared UI components
│   ├── ui/             # Base shadcn/ui components
│   ├── CloudBg.tsx     # Animated background
│   ├── ScoreBar.tsx    # Score display
│   ├── StarBurst.tsx   # Win animation
│   └── EncouragementBanner.tsx
├── hooks/              # Custom React hooks
│   ├── useAdaptive.ts        # Adaptive difficulty logic
│   ├── useBackgroundMusic.ts # Music toggle
│   ├── useSessionTracker.ts  # Time tracking
│   └── useSpeech.ts          # Text-to-speech
├── pages/              # Game screens
│   ├── Home.tsx
│   ├── AlphaGame.tsx
│   ├── MissingGame.tsx
│   ├── MatchGame.tsx
│   ├── SentenceGame.tsx
│   ├── ScrambleGame.tsx
│   └── Dashboard.tsx
├── data/
│   └── gameData.ts     # Game content and questions
├── lib/
│   └── utils.ts
├── App.tsx
└── main.tsx


🤖 AI Concepts Applied

This project was built for an AI course and demonstrates the following concepts:


Adaptive learning systems — the game tracks accuracy and adjusts question difficulty dynamically using useAdaptive.ts
Session-based performance tracking — data persists across sessions to model a learner's progress over time
User-centered AI design — feedback (encouragement banners, star bursts) is triggered based on performance thresholds



📄 License

This project was created for academic purposes at Albukhary International University.


🙏 Acknowledgements


Radix UI for accessible component primitives
Framer Motion for animations
shadcn/ui for UI component templates
Tailwind CSS for styling

ShareContentlearn-and-play-src.tar.gzgz
