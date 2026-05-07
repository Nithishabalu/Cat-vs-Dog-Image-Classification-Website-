# Cat-vs-Dog Image Classification Website
🐱 vs 🐶 PawDetect — Cat vs Dog AI Classifier
A beautiful, fully interactive Cat vs Dog image classifier that runs 100% in your browser using TensorFlow.js. No API key, no server, no cost — just drop a photo and get an instant AI verdict.
🔗 Live Demo: https://your-username.github.io/cat-vs-dog

✨ Features

📸 Drag & Drop Upload — drop any pet photo or click to browse
🤖 On-Device AI — MobileNet neural network runs entirely in your browser
🎊 Confetti Animation — fires when AI confidence is high
📊 Confidence Ring — animated SVG donut chart showing cat vs dog probability
📈 Live Tally — counts cats and dogs classified in your session
💡 Fun Fact Ticker — rotating cat and dog facts with prev/next controls
📜 Classification History — thumbnail grid of all photos you've classified
🔍 Image Zoom — hover to zoom, click to open full size
🌐 Particle Background — animated floating network of dots
📱 Fully Responsive — works on mobile and desktop


🚀 How to Use

Open the website
Wait for the AI model to load (5–10 seconds on first visit)
Drag & drop or click "Choose Photo" to upload a pet image
Get an instant Cat 🐱 or Dog 🐶 verdict with confidence score


🛠️ Tech Stack
TechnologyPurposeHTML / CSS / JavaScriptFrontend — single file, no frameworkTensorFlow.jsMachine learning in the browserMobileNet v2Pre-trained image classification modelGitHub PagesFree hosting

📁 Project Structure
cat-vs-dog/
│
├── index.html       ← entire app (single file)
└── README.md        ← this file

🧠 How It Works

TensorFlow.js loads the MobileNet v2 model (~5MB) directly in the browser
When you upload a photo, the model classifies it into 1000 ImageNet categories
The app scans the top predictions for cat-related and dog-related keywords
It calculates a Cat % vs Dog % confidence score and shows the verdict
All processing happens locally — your photos are never sent anywhere


🖥️ Run Locally
No installation needed. Just open the file in any browser:
bashgit clone https://github.com/your-username/cat-vs-dog.git
cd cat-vs-dog
open index.html
Or simply double-click index.html to open it in your browser.

📸 Screenshots

Add your own screenshots here after deploying!


🔒 Privacy
Your photos never leave your device. The AI model runs entirely in your browser using TensorFlow.js. No data is sent to any server.

📄 License
This project is open source and available under the MIT License.

🙏 Credits

TensorFlow.js — ML in the browser
MobileNet — image classification model
Google Fonts — Syne & DM Sans typefaces
