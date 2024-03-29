# NewsHub - Personalized News Aggregator App

NewsHub is a Django-powered news aggregator application that allows users to customize their news feed based on their interests and preferences. It collects news articles from multiple sources through API calls and presents them in a user-friendly interface.



## Table of Contents

- [Tech Stack](#tech-stack)
- [Key Features](#key-features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Tech Stack

- Python: The core programming language used for building the application's backend logic.
- Django: A powerful web framework that enables rapid development and robust security.
- HTML/CSS/JavaScript: Frontend technologies used to create an intuitive and responsive user interface.
- API Integration: Utilized to fetch news data from multiple sources and integrate it seamlessly into the app.

## Key Features

1. **News Aggregation:** NewsHub pulls in news articles from a wide range of reputable sources, ensuring users have access to diverse and up-to-date content.

2. **Personalization:** Users can customize their news feed by selecting specific categories, keywords, or sources that align with their interests.

3. **User-Friendly Interface:** The app boasts an intuitive and visually appealing design, making it easy for users to navigate and access their chosen news.

4. **Daily Digest:** NewsHub offers a personalized daily digest, summarizing the most relevant news based on each user's preferences.

5. **Notifications:** Users receive notifications for breaking news or updates related to their selected topics, ensuring they stay informed.

6. **Search and Save:** The app allows users to search for specific news articles and save them for later reading.

7. **Cross-Platform Compatibility:** NewsHub is accessible on various devices, including smartphones, tablets, and desktop computers.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Python (3.7 or higher) installed on your system.
- Pip package manager installed.
- A modern web browser to access the app.

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/skin-disease-prediction.git
   ```

2. Create a virtual environment:

   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source venv/bin/activate
     ```

4. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

5. Configure the database settings in `settings.py` to connect to your MySQL database.

6. Run migrations:

   ```bash
   python manage.py migrate
   ```

7. Create a superuser for admin access:

   ```bash
   python manage.py createsuperuser
   ```

8. Start the development server:

   ```bash
   python manage.py runserver
   ```

9. Access the application in your web browser at `http://localhost:8000`.


7.Start the development server: 

python manage.py runserver

8.Open your web browser and visit http://localhost:8000 to access Caloriefy.
