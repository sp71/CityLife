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
- TableView has subcell support for improved category precision
- Displays a plethora of categories onto map
- Detail Venue Screen
  - Venue image shown (if available)
  - Dynamically displays information only if available
    - Call: Directly contact them
    - Website: Deep Link into Safari browser
    - twitter: Deep Link into Twitter app
    - Menu: Display Menu onto webview
  - Address selection supports deep linking for navigation with following apps
    - Apple Maps
    - Waze
    - Google Maps
  - Reviewer Images are dynamically fetched as they appear
    - Using an internal image cache based upon url to avoid duplicate network calls

# Lessons Learned
- Stack Views are amazing for supporting dynamic content
- Image Cache greatly improves performance
- Deep Linking
- CollectionView support for dynamic height
- [Fastlane](https://github.com/fastlane/fastlane)
  - Provides amazing automated tools for taking screenshots across multiple devices
  - Uploads screenshots directly to iTunes
- iOS is super fun =D

# Specifications
- Language: Objective-C
- Development Environment: Xcode 7.0 and above
- Target: iOS 9.0 and above
- Memory: Full ARC support
- Interface Builder: Storyboard

# AppStore
- Pending Review for this updated version
- [AppStore](https://itunes.apple.com/WebObjects/MZStore.woa/wa/viewSoftware?id=1017362846&mt=8)
