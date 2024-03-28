

# News Feed App

## Project Overview

The News Feed App is a part of the Android Application, aiming to create a dynamic and user-friendly application that provides users with regularly updated news from the internet based on specific topics, persons, or locations of interest. For this project, we utilize the Guardian API, a well-maintained API that returns news information in JSON format.

### API Key Note

To access the Guardian API, you need to insert your API key. Navigate to a file named `Constants.java` within the project, locate the value assigned to `API_KEY`, and replace the placeholder "YOUR-API-KEY" with your actual API key to fetch news data successfully.

```java
public static final String API_KEY = "YOUR-API-KEY";
```

## Features

- **Navigation Drawer:** Implement a navigation drawer to facilitate easy navigation between different sections or categories of news.
  
- **Fragments:** Utilize fragments to create reusable UI components for displaying news categories and individual news articles.
  
- **ViewPager plus TabLayout:** Implement ViewPager along with TabLayout to allow users to swipe between different sections or categories of news effortlessly.
  
- **Loaders:** Implement loaders to efficiently load and display news data from the Guardian API in the background, ensuring smooth user experience.
  
- **Intent:** Utilize intents to navigate to external web browsers for reading full news articles or sharing news links with others.
  
- **Guardian API:** Integrate the Guardian API to fetch and display news articles, headlines, and related information in real time.
  
- **JSON Parsing:** Parse JSON responses from the Guardian API to extract relevant news data and display it in a structured format.
  
- **Glide:** Use Glide library for efficient image loading and caching to display news thumbnails or images associated with news articles.
  
- **CardView:** Implement CardView to create visually appealing news article previews with images, titles, and brief descriptions.
  
- **RecyclerView:** Utilize RecyclerView to efficiently display a list of news articles with optimized scrolling and memory usage.
  
- **SharedPreferences:** Implement SharedPreferences to store and manage user preferences, such as selected news categories or saved articles.


