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

## GHFollowers Screenshots

| **Screen**            | **Description**                       |
|-----------------------|---------------------------------------|
| <img src="https://github.com/user-attachments/assets/a9065492-f3ab-4072-8af1-a50bb19bea96" width="400"/> | **Search Github UserName**: Enter the respective username of the person and request followers.<br> - **Feature**: Search functionality with user validation. |
| <img src="https://github.com/user-attachments/assets/c7c4dc7b-85ea-4f52-a224-b5952f71d36b" width="400"/> | **Empty State View**: Screen view in case no followers exist for the entered username.<br> - **Feature**: Clean design with informative empty state UI. |
| <img src="https://github.com/user-attachments/assets/0276e1cc-adfa-4293-9ac3-975f8aaaf480" width="400"/> | **List of Followers**: Returns a list of followers in a table view format with a search controller to filter based on follower name.<br> - **Feature**: Searchable list with smooth UI updates. |
| <img src="https://github.com/user-attachments/assets/bd1f6a47-3486-4569-86a1-ded6a1265ef0" width="400"/> | **User Profile Section**: Shows basic user details like name, bio, location, avatar image, followers, gists, repos, and buttons for GitHub profile and to view followers.<br> - **Feature**: Detailed user profile with external links. |
| <img src="https://github.com/user-attachments/assets/82ecd01a-bcc5-4ac9-a7fd-ea736fe37e76" width="400"/> | **Followers of Followers**: Allows viewing of followers of followers, and so on.<br> - **Feature**: Recursive follower exploration with dynamic loading. |
| <img src="https://github.com/user-attachments/assets/b1327947-a6ce-4e44-82c3-9b282eb47fb5" width="400"/> | **Github Profile**: Opens Safari view controller using SFSafariServices to show GitHub profile.<br> - **Feature**: Secure in-app browsing using SFSafariViewController. |

