# ⚽ Upcoming Premier League Matches Dashboard

![](https://via.placeholder.com/800x400?text=Upcoming+Matches+Demo) 
![image](https://github.com/user-attachments/assets/982a5e1e-7e92-4b28-b025-5ed168e2a79b)


A Next.js application that fetches and displays upcoming English Premier League matches from a free API, featuring a clean table layout with responsive design.

🔗 **Live Demo**: [https://api-match.vercel.app/](https://api-match.vercel.app/)

## Features

- 📅 Fetches real-time match data from FixtureDownload API
- 🏟️ Displays match details including:
  - Date & Time (formatted)
  - Home and Away teams
  - League information
- ⚡ Built with Next.js API routes for server-side fetching
- 🔄 Loading state for better UX
- 📱 Fully responsive design

## Tech Stack

- **Framework**: [Next.js](https://nextjs.org/) (App Router)
- **Styling**: Vanilla CSS (no CSS frameworks)
- **Deployment**: [Vercel](https://vercel.com)
- **API**: [FixtureDownload.com](https://fixturedownload.com)

## Getting Started

### Prerequisites
- Node.js (v18 or later)
- npm or yarn

### Installation
1. Clone the repository
   ```bash
   git clone https://github.com/dhruvmeeena36/API-fetch-.git
   cd API-fetch-
   
### Project Structure
/API-fetch-
├── app/
│   ├── api/
│   │   └── matches/
│   │       └── route.js    # API endpoint for matches
│   └── page.js             # Main page component
├── public/                 # Static files
└── README.md

### API Documentation
The application uses the following API endpoint:

GET https://fixturedownload.com/feed/json/epl-2023

### Sample Response
json
[
  {
    "Id": 1,
    "Date": "2023-08-12T14:00:00",
    "HomeTeam": "Arsenal",
    "AwayTeam": "Brentford",
    "Location": "Emirates Stadium"
  }
]

### Future Improvements
Add filtering by team

Include match results

Implement a refresh button

Add caching for API responses
