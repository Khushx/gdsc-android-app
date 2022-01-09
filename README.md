# GDSC-PHCET-ANDROID-APP

Community App of Google Developer Student Club @ PHCET

<b> Problem Statement: </b>

Getting Information and all the resource related to Google Developer Student Club PHCET and all the Events, Hackathons, etc. that we conduct gets complicated as Information and resources are divided on multiple platforms such as the DSC Community Website, WhatsApp Group of GDSC PHCET, Discord Server of GDSC PHCET, GitHub Org of GDSC PHCET, YouTube channel of GDSC PHCET and so on. Specific Technologies can be used to Implement a solution to ease the process and concentrate all the Information related to GDSC PHCET on a single platform.

<b> Proposed Solution : </b>

This project proposes a "Community Android Application" to accumulate all the Information and Resources related to our developer community here at GDSC PHCET in one single Android Application, which will make it a one-stop destination for all community members to access all the resources from one single platform rather than searching over all our social media handles and web-pages.

<img width="559" alt="sampleimages" src="https://media.discordapp.net/attachments/917143189457104938/929786609522589706/Orientation1.jpg?width=671&height=671">
    	  	
# <b> Functionality & Concepts used : </b>


## Functionalities in the app :

- Find all our Social Media handles and Developer Profiles.
- Get to know more about Google Developer Student Clubs.
- See Upcoming Event and all the Details.
- See Past Events and all the Details.
- Get Past Event's Video Recording.
- Verify the Certificate's authenticity issued by GDSC PHCET via this app and get all details.
- Check out all the Profiles of the Lead as well as of the whole team here at GDSC PHCET

## Concepts used in the app :

- **ConstraintLayout & NestedScrollView:** Most UI Controllers (Activities and Fragments) in the app take advantage of the flexibility on ConstraintLayout as well as uses NestedScrollViews and HorizontalScrollViews as necessary to display a list of data / make layouts scrollable.
- **Navigation Component Library + SafeArgs Plugin (Android Jetpack):** Navigation Libraries are used to make navigating throughout the app easier, using navGraph with destinations and safeArgs to pass data between destinations with type safety.
- **LiveData, ViewModel + Room DB (Android Jetpack):** LiveData, Room and ViewModels such as EventDetailViewModel and AboutViewModel are used to make the architecture of the app more robust and scalable by making sure data survives configuration changes of user devices, all data gathering and model objects are present inside ViewModels.

- **Firebase RealtimeDatabase:** Google's Firebase is used as the online Backend Database to retrieve most of the data from, such as the Event Details as well as the Data for Verified Certificates issued by GDSC PHCET.
- **DataBinding + LiveData:** DataBinding is used along with LiveData to connect Views with Data as a 2-way connection, and make sure the data on the screen changes if the data is updated in the Database.
- **BottomNavigationView:** BottomNavigationView is implemented using navController of the NavigationGraph to easily navigate between the 3 Fragments AboutFragment, HomeFragment and TeamFragment.

- **Glide + Lottie:** Third-Party Libraries such as Glide is used to load images in the app using URIs as well as Lottie is used to render smooth animations in our app as views from the raw JSON.
- **MaterialUI by Material.io from Google:** This app follows the Material UI design pattern to implement a minimal UI to provide an enhanced user experience.
- This app is made using many Android Jetpack Libraries such as the Navigation Component Libraries, Architecture Component Libraries, DataBinding, etc. as well as various external third-party android libraries.

<b> Application Link & Future Scope : </b>

- The app is in the Alpha stage current and is being tested, discussed and developed by the student developers here at GDSC PHCET, the app will be released to the Google Play Store as soon as it's ready for the Beta Release. For now, the app can be downloaded from : [here](https://test.link)

- We are currently discussing all the possible features that can be Implemented in this community app, in the coming months we will be adding many more functionalities to this application.