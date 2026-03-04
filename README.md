# 📍 Travel Book

Travel Book is a functional iOS application developed with **Swift** and **UIKit** that allows users to save their favorite locations on a map with personalized titles and notes. It leverages Apple's native frameworks to provide a seamless location-saving experience.

## 🛠 Features
- **Interactive Mapping:** Integration with **MapKit** to select and view locations globally.
- **Long Press Interaction:** Users can drop a pin anywhere on the map using a long-press gesture.
- **Data Persistence:** Utilizes **Core Data** to save, fetch, and manage user-defined locations locally.
- **Navigation:** Integrated with **Apple Maps** to provide directions to saved locations.

## 💻 Tech Stack
- **Language:** Swift
- **Frameworks:** UIKit, MapKit, CoreLocation
- **Database:** Core Data
- **Architecture:** MVC

## 🚀 Key Technical Implementation
- Implemented `CLLocationManagerDelegate` for real-time user location tracking.
- Designed a custom data model in Core Data to store coordinates (latitude/longitude), titles, and descriptions.
- Managed seamless transitions between the location list and the map view using **Segues**.




