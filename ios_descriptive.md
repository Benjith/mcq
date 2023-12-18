**Descriptive Questions and Answers for iOS Development:**

1. **Explain the role of the "AppDelegate" class in an iOS application.**
   
   **Answer:** The "AppDelegate" class in iOS serves as the entry point and central coordinator for the application's lifecycle. It handles events such as app launch, termination, and background execution. The "AppDelegate" class also manages the app's state transitions and is responsible for initializing the app's user interface and other essential components.

2. **Describe the purpose of Interface Builder in Xcode and how it aids in iOS app development.**
   
   **Answer:** Interface Builder is a visual design tool integrated into Xcode for creating and designing user interfaces in iOS applications. It allows developers to design interfaces by dragging and dropping UI elements onto a canvas, simplifying the process of building complex user interfaces. Interface Builder generates the corresponding code (usually in a storyboard file) that is then seamlessly integrated with the app's logic.

3. **Explain the concept of delegation in iOS development and provide an example of its usage.**
   
   **Answer:** Delegation in iOS involves one object (the delegate) acting on behalf of another object. It allows one object to communicate and influence the behavior of another. An example is the UITableViewDelegate in a UITableView. The table view's delegate implements methods that determine the appearance and behavior of the table view, providing a way for customization without subclassing.

4. **Discuss the significance of Core Data in iOS development and how it is used for data management.**
   
   **Answer:** Core Data is a framework in iOS used for managing the model layer of an application. It provides an object-oriented way to interact with and persistently store data. Core Data handles tasks such as data modeling, storage, and retrieval, making it easier for developers to manage complex data relationships. It is commonly used for implementing data-driven features in iOS apps.

5. **Explain the purpose of the "Info.plist" file in an iOS app and the type of information it typically contains.**
   
   **Answer:** The "Info.plist" file in an iOS app is a property list file that contains essential configuration information about the app. It includes details such as the app's bundle identifier, version number, supported device orientations, and required device capabilities. This file is critical for the proper functioning of the app and is used by the system to understand the app's characteristics and permissions.
