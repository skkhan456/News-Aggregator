
# 📰 News Aggregator Web App

A dynamic and responsive web application that aggregates real-time news articles from multiple categories and countries. Built using the **MERN stack** (MongoDB,Express.js, React.js, Node.js) and styled with **Tailwind CSS**.

## 🚀 Features

- 📢 **Top Headlines**: Displays the latest news fetched from the News API.
- 🗂️ **Category-Based Filtering**: View news from different categories like Sports, Business, Technology, Health, etc.
- 🌍 **Country Selector**: Filter news headlines based on country selection.
- 🌓 **Light/Dark Mode Toggle**: Switch between light and dark themes for better readability.
- 🔗 **Redirect to Full Article**: Click on the **source link** to read the complete article on the original website.
- 📅 **Published Timestamp**: Displays when the article was published.
- 📱 **Responsive Design**: Optimized for mobile, tablet, and desktop screens.
- 🌐 **RESTful API Integration**: Backend interacts with the News API and serves relevant data to the frontend.

## 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### External API
- [News API](https://newsapi.org/) for real-time news data

## Getting Started
These instructions will help you set up the project on your local machine for development and testing purposes.
### Prerequisites

- Node.js and npm installed on your machine
- A NewsAPI.org API key

### Installation

1. Fork the repository on GitHub.
2. Clone the repository to your local machine.
3. Navigate to the server directory and create a new file named `.env`.
4. Add your NewsAPI.org API key to the `.env` file in the following format: `API_KEY=your_news_api_key`.
5. In the server directory, run `npm install` to install the necessary dependencies.
6. Start the server by running `node server.js`.
7. Navigate to the client directory and run `npm install` to install the necessary dependencies.
8. Start the client by running `npm run dev`.

## Usage

Once the project is set up and running, you can view news articles from various sources on the client side.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
