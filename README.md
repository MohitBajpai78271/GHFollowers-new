 # GitHub Follower (iOS Application)

## Overview

Developed a search functionality that allows users to search and display GitHub followers by username,
showcasing their avatar images and names with an optimized, user-friendly UI and other functionalities.

## Features

- **Search Option**: Allows users to search for followers by name.
- **List of Followers**: Displays a list of followers in a table view.
- **Profile View**: Clicking on a follower displays their profile details.
- **Follower Details**: Users can check the follower's profile or visit their GitHub page in Safari.

### Technology Stack

- **Swift**: Frontend built using UIKit.
- **Alamofire**: Networking library for API calls.
- **JSON**: Handling data exchange between frontend and Github APIs.

## Screenshots

| Screen            | Description                       |
|-------------------|-----------------------------------|
|<p align="center"> <img src="https://github.com/user-attachments/assets/a9065492-f3ab-4072-8af1-a50bb19bea96" width="200"/> </p>| **Search Github UserName**: Enter Respective userName of the person and request followers. |
|<p align="center"> <img src="https://github.com/user-attachments/assets/c7c4dc7b-85ea-4f52-a224-b5952f71d36b" width="200"/> </p>| **Empty State View**: View of screen in case of no followers exist with respect to that userName. |
|<p align="center"> <img src="https://github.com/user-attachments/assets/0276e1cc-adfa-4293-9ac3-975f8aaaf480" width="200"/> </p>| **List of Followers**: Returns list of followers in a table view format with search controller to filter based on Follower name. |
| <img src="https://github.com/user-attachments/assets/bd1f6a47-3486-4569-86a1-ded6a1265ef0" width="200"/> | **User Profile Section**: Shows basic user details like Name,Bio,Location,Avatar Image,followers,gists,repos,Button for github profile and to view followers. |
|<p align="center"> <img src="https://github.com/user-attachments/assets/82ecd01a-bcc5-4ac9-a7fd-ea736fe37e76" width="200"/> </p>| **Followers of Followers**: To View Followers of Followers and so on. |
|<p align="center"> <img src="https://github.com/user-attachments/assets/b1327947-a6ce-4e44-82c3-9b282eb47fb5" width="200"/> </p>| **Github Profile**: Opens Safari view controller using SFSafariServices. |
