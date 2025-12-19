# Google Map Search Application

## 📌 Overview
Google Map Search Application is a web application that allows users to search locations on Google Maps, display markers, filter markers within a polygon area, and manage user authentication (login/logout).

---

## ✨ Features

### 🔐 Authentication (Author)
- Login
- Logout

### 🗺️ Google Maps
- Place Autocomplete
- Show marker & marker info
- Search marker information
- Draw polygon area
- Only show markers inside polygon

---

## 🛠️ Technologies
- Frontend: React.js
- Language: JavaScript 
- Google APIs:
  - Google Maps JavaScript API
  - Google Places API
- Authentication: custom save to localstorage
- Styling: css

---

## 📂 Project Structure
```bash
src/
├── components/
│   ├── Auth/
│   ├── Map/
│   └── Search/
├── pages/
├── services/
├── utils/
└── App.tsx



## Step 1: Clone the repository
git clone https://github.com/thinhpham311-dev/react-google-map-search.git
cd react-google-map-search

## Step 2: Install PHP dependencies
```bash
npm install
# or
yarn install

```

## Step 3: Create environment file
VITE_GOOGLE_MAP_API_KEY=your_google_map_api_key


## Step 4: Run project (Local)
```bash
npm run dev
# hoặc
yarn dev

http://localhost:3000
```