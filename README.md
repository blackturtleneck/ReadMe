# A M P R
This file contains information about:

[About Our Product](#about-our-product)

[The Problem Space](#the-problem-space)

[What You'll Find (Our Repositories)](#what-you'll-find)

[Technology Decisions](#technology-decisions)

[Contact Information](#contact-information)


the repositories contained in the blackturtlenack organization, an overview of our product, our technology decisions, and our contact information. 

AMPR is a project for the University of Washington Information School Informatics Capstone 2018.

# ABOUT OUR PRODUCT
We connect people in a meaningful way by taking online dating, offline. AMPR is for those who are tired of mindless swiping and superficial conversations. Our unique date generator plans dates for users based on mutual interests, first date preferences, and individual schedules so they can focus on developing meaningful relationships. We want users to use our product as a tool, not a crutch; that is why we welcome all users, whether they’re looking to meet someone new or discover local spots. Swipe less, date more.

# THE PROBLEM SPACE
Through our research, we have found that the current online dating culture puts a heavy emphasis on quick interaction to many people and not about the quality of interactions. Users go through a cycle of downloading a dating app(s), making quick, superficial conversations with other users, rarely actually going on dates, feeling discouraged, deleting the app, unhappy with not meeting people, downloading a dating app(s), and repeat.

## WHAT YOU'LL FIND
### [capstoneWeb](https://github.com/blackturtleneck/capstoneWeb)
This repo contains the web version of AMPR

### [capstoneReactNative](https://github.com/blackturtleneck/capstoneReactNative)
This repo contains the mobile version of AMPR.

### [website](https://github.com/blackturtleneck/website)
This repo contains the overview website for AMPR. 
Visit the final product at dateampr.com


## TECHNOLOGY DECISIONS:
### React
React is a JavaScript library for building user interfaces. It is maintained by Facebook, Instagram and a community of individual developers and corporations. We chose to use this because it's what we are most comfortable with using since it is what we were taught in the Informatics core requirement: Client-Side Web Development. 


### React Native
React Native lets you build mobile apps using only JavaScript. It uses the same design as React, letting you compose a rich mobile UI from declarative components. When considering mobile development, we chose to use react native because it allows developers to create a product that's friendly for both Android and iOS. From our experiences developing in Swift and Java for iOS and Android projects, respectively, we thought that React Native was the best choice for this project. Additionally, since we are already using React for web, react native allows the developmental transition from web to mobile more seemless.

### Firestore
Cloud Firestore is a flexible, scalable database for mobile, web, and server development from Firebase and Google Cloud Platform. Like Firebase Realtime Database, it keeps your data in sync across client apps through realtime listeners and offers offline support for mobile and web so you can build responsive apps that work regardless of network latency or Internet connectivity. Cloud Firestore also offers seamless integration with other Firebase and Google Cloud Platform products, including Cloud Functions. [(Firestore Documentation)](https://firebase.google.com/docs/firestore/)
We chose to use this platform because it provides cloud storage for our users' information and easy integration with Facebook login verification. We chose Firestore over Firebase due to ease of information access due to the way it is stored. Firebase stores information in large JSON files whereas information is stores data in documents and organized in collections Firestore. The data is then able to be queried and automatically scaled. Firestore offers offline for iOS, Android, and Web whereas Firebase only offers offline support for mobile. With the large amounts of user data we expect to store, using Firestore is the reliable choice.


## CONTACT INFORMATION
Jessica Libman: jlibman@uw.edu | 
[LinkedIn](https://www.linkedin.com/in/jessica-libman/)

Joycie Yu: joycie@uw.edu | 
[LinkedIn](https://www.linkedin.com/in/joycieyu/)

Sarah Feldmann: sarahf95@uw.edu | 
[LinkedIn](https://www.linkedin.com/in/sarahpfeldmann/)

Zhanna Voloshina: zhannav@uw.edu | 
[LinkedIn](https://www.linkedin.com/in/zhannavoloshina/)
