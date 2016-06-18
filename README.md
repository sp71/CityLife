# CityLife

An iOS Objective-C application for finding specific venues near a user's location. An animated Gif should display shortly (Note: Actual application is much smoother) <br />

![alt tag](https://github.com/sp71/CityLife/blob/master/demo.gif)

# Objective
- Build a iPhone & iPad application that queries FourSquare
- Explore Fousquare API [CategoryTree](https://developer.foursquare.com/docs/)
- Fun Personal Project to showcase my talent

# Features
- Initial launch displays collection view of Images
  - Images are directly from Foursquare
  - Cells are of dynamic height depending upon text length
- TableView have subcell support for improved category precision
- Displays a plethora of categories onto map
- Detail Venue Screen
  - Venue image shown (if available)
  - Dynamically displays information only if available
    - Call: Directly Call
    - Website: Display Website via Safari
    - twitter: Deep Link into Twitter app
    - Menu: Display Menu onto webview
  - Address selection supports deep linking for navigation with following apps
    - Apple Maps
    - Waze
    - Google Maps
  - Reviewer Images are dynamically loaded as they appear
    - Using an internal image cache based upon url

# Lessons Learned
- Stack Views are amazing for supporting dynamic content
- Image Cache greatly improves performance
- Deep Linking
- CollectionView support for dynamic height
- iOS is super fun =D

# Specifications
- Language: Objective-C
- Development Environment: Xcode 7.0 and above
- Target: iOS 9.0 and above
- Memory: Full ARC support
- Interface Builder: XIBs and Storyboard are allowed

# AppStore
- Pending Review for this updated version
- [AppStore](https://itunes.apple.com/WebObjects/MZStore.woa/wa/viewSoftware?id=1017362846&mt=8)
