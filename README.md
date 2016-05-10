# PopularMovies-Stage1
Project 1 of the Udacity Android Nanodegree course. In this project, you’ll build an app to allow users to discover the most popular movies playing.
Your app will:
- Present the user with a grid arrangement of movie posters upon launch.
- Allow your user to change sort order via a setting:
- The sort order can be by most popular or by highest-rated

Allow the user to tap on a movie poster and transition to a details screen with additional information such as:
- original title
- movie poster image thumbnail
- A plot synopsis (called overview in the api)
- user rating (called vote_average in the api)
- release date

###Why this Project?
To become an Android developer, you must know how to bring particular mobile experiences to life. Specifically, you need to know how to build clean and compelling user interfaces (UIs), fetch data from network services, and optimize the experience for various mobile devices. You will hone these fundamental skills in this project.
By building this app, you will demonstrate your understanding of the foundational elements of programming for Android. Your app will communicate with the Internet and provide a responsive and delightful user experience.

###Getting Started
This sample uses the Gradle build system. To build this project, use the "gradlew build" command or use "Import Project" in Android Studio.

This app uses The Movie Database API to retrieve movies. To use this app, you will need to generate your own API Key and input in the app's 'build.gradle' file:


      buildTypes.each {

          it.buildConfigField 'String', 'API_KEY', "YourApiKeyHere"
          }
    
