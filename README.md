





# NYTimes

NY Times is an Minimal News 🗞 iOS application built to describe the use of **SwiftSoup** and **CoreData** with **SwiftUI**.

## ⛓ Features


## 📝 Table of Contents  
- [Requirements](#requirements)
- [What you can learn?](#whatyoucanlearn)
- [Technical Background](#techbackground)
- [Dependencies](#dependencies)




<a name="requirements"/>

## ⚙️ Requirements
```
iOS 14+
Xcode 12.2 and Up
```

<a name="whatyoucanlearn"/>

## 📚 What you can learn?
- You can learn Technologies like
  - SwiftUI
  - CoreData
  - Combine
  - Web Scraping
- You can learn various Design patterns from this project such as
  - Dependency injection
  - Repository 
  - Singleton
  - Observers
- You can learn MVVM Two way binding Architecture for SwiftUI with Combine framework

<a name="techbackground"/>

## 🛠 Technical Background
- NYTimes App was made using SwiftUI as the Core interface with Two Way Binding MVVM Architecture using Combine framework. 
- CoreData is used to store the Article Bookmarks offline in device so that the user can access it at later time.
- SwiftSoup is used to scrap the required details from the NYTimes website.
- The User interface of this app mostly uses the inbuilt iOS components to keep the User experience close to the native feel.
- Bookmarks can be added as easy as a 3d-touch from Homescreen or a tap in bookmark icon in the detailed article screen.
- This project was built in the mindset of modularity and good coding patterns. Multiple design patterns like Dependency injection, Repository pattern, Singleton Pattern etc.

<a name="dependencies"/>

## 🔗 Dependencies

This project uses SPM (Swift Package Manager) as Dependency manager.

 - [SwiftSoup](https://github.com/scinfu/SwiftSoup)
 - [Kingfisher](https://github.com/onevcat/Kingfisher)
 - [Reachability](https://github.com/ashleymills/Reachability.swift)

<a name="projectstructure"/>

## ⛓ Project Structure

    NYTimes                 # Root Group
    .
    ├── Utilities           # Utilities for Fetching data ans Scraping HTML
    ├── Extensions          # Some useful extensions
    ├── Globals             # Contains App constants
    ├── Persistence         # Coredata files. Contains coredata model and Singleton for ManagedObjectContext
    ├── Views               # SwiftUI Views
    ├── Repository          # Repository for Coredata
    ├── ViewModel           # Viewmodels for SwiftUI Views
    ├── Model               # Model files
    |   └── Coredata Model  # Coredata model subclasses
    |
    └── Supporting files    # Misc. files like Appdelegate, SceneDelegate.

