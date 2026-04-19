# 📚 KamaiKitab Frontend

**Empowering Pakistan's gig workforce to track, verify, and leverage their income data for a fairer future.**

[![Live Demo](https://img.shields.io/badge/Live_Demo-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://kamai-kitab-frontend.vercel.app/)
[![React](https://img.shields.io/badge/React-18.x-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-5.x-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)

## 🌐 Live Demo

**Deployed URL:** [https://kamai-kitab-frontend.vercel.app/](https://kamai-kitab-frontend.vercel.app/)

---

## ✨ Features

### For Gig Workers
- **Earnings Dashboard** - Unified view of gross income, platform deductions, and net pay across all platforms
- **Verified Certificates** - Generate printable certificates verified by community peers for banks or landlords
- **Anonymous Reports** - Securely report rate drops or unfair deactivations without fear of retaliation
- **Shift Logging** - Enter hours and earnings manually or via bulk CSV import
- **Verification System** - Upload screenshots for community authentication

### For Advocates
- **Income Heatmaps** - Identify city zones where earnings are dropping below survival levels
- **Commission Tracker** - Monitor real-time shifts in platform deduction rates
- **Cluster Analysis** - Auto-group similar complaints to identify systemic deactivation patterns

### Platform Statistics
- 📊 **2.4Cr+** Earnings Tracked
- ✅ **98.2%** Grievance Accuracy
- 👥 **10k+** Community Members
- 🟢 **99.9%** Uptime

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| Framework | React 18 |
| Build Tool | Vite |
| HTTP Client | Axios |
| Deployment | Vercel |
| Version Control | Git & GitHub |

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/aayma-codes/project-repo.git
   cd project-repo
Install dependencies

bash
npm install
# or
yarn install
Set up environment variables

Create a .env file in the root directory:

env
VITE_API_BASE_URL=your_api_endpoint_here
# Add other required variables
Run development server

bash
npm run dev
# or
yarn dev
The app will be available at http://localhost:5173

Build for production

bash
npm run build
# or
yarn build
📁 Project Structure
text
project-frontend/
├── public/                 # Static assets
├── src/
│   ├── assets/            # Images, fonts, etc.
│   ├── components/        # Reusable UI components
│   ├── pages/             # Page components
│   ├── services/          # API services (api.js)
│   ├── styles/            # Global styles
│   ├── utils/             # Helper functions
│   ├── App.jsx            # Main app component
│   └── main.jsx           # Entry point
├── .env                   # Environment variables (git-ignored)
├── .gitignore
├── index.html
├── package.json
├── README.md
└── vite.config.js
🔄 Keeping Your Code Updated
To pull the latest changes from GitHub:

bash
# Discard local changes (if any)
git restore .

# Remove untracked .env file (Windows)
del .env
# OR (Mac/Linux)
rm .env

# Pull latest code
git pull origin main
🚢 Deployment
The frontend is automatically deployed to Vercel from the main branch.

Live URL: https://kamai-kitab-frontend.vercel.app/

To deploy manually:

bash
npm run build
# Deploy the 'dist' folder to Vercel
🤝 Contributing
Create a feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

📝 Important Notes
🔒 The .env file is git-ignored for security - never commit it

📦 package-lock.json should be committed to ensure consistent dependencies

🧹 Run npm run lint to check code quality (if ESLint is configured)

👥 Team
Frontend Developer: @aayma-codes

📄 License
This project is proprietary and confidential.

🙏 Acknowledgments
Built for Pakistan's gig workforce

Community-driven verification system

Powered by React & Vite

📧 For support or queries, please open an issue in this repository.

<div align="center">
Made with ❤️ for Pakistan's Gig Workers

⬆ Back to Top

</div> ```
