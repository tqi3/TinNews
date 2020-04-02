# TinNews
Developed a Tinder Flavor News android application allowing users to like/unlike the news by either swiping right/left the news card or clicking the like/dislike button, to check these saved liked news’ overview with a “read more” link, which could be copied and shared, to go to the corresponding website, and to clear all liked news and change the news source by country; specifically customized the app icon and font, implemented the division of the 3 features described above (i.e. tabs of liking, checking and setting news) with a combination of “bottomnavigationview” and “viewpager” widgets, designed all features with MVP pattern for better decoupling and code reusability, integrated https://newsapi.org/ API with Retrofit as news source and Picasso for loading images, applied Janishar’s “placeholder view” to the Tinder-like swipe feature to like/unlike/cancel the particular news, used recycler view widget with a generic view model handling different viewholders to present “checking” and “setting” pages, utilized room, an ORM library for liked news’ data storage and manipulation with flowable to observe data changes, performed thread changing async tasks for API/database operations with rxjava2, supported the “read more” feature by an intent sent to another activity, a progress bar and a popup menu to share/copy link, enabled info transmission between fragments to change news source with eventbus, added different clicklisteners for user interaction and debugged the project with Steho.