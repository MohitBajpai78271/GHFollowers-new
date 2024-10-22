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
| <img src="https://github.com/user-attachments/assets/f71e68d8-46c0-49c6-9619-a7c0767c6f62" width="400"/> | **Search Github UserName**: Enter the respective username of the person and request followers.<br> - **Feature**: Search functionality with user validation. |
| <img src="https://github.com/user-attachments/assets/9b406a34-6c73-44ce-849a-4bb893e704e0" width="400"/> | **Empty State View**: Screen view in case no followers exist for the entered username.<br> - **Feature**: Clean design with informative empty state UI. |
| <img src="https://github.com/user-attachments/assets/3dc745e3-777f-4a19-aca8-1b928ccd6dae" width="400"/> | **List of Followers**: Returns a list of followers in a table view format with a search controller to filter based on follower name.<br> - **Feature**: Searchable list with smooth UI updates. |
| <img src="https://github.com/user-attachments/assets/518d34dc-a34b-4d2e-b80d-69b790ef5d22" width="400"/> | **User Profile Section**: Shows basic user details like name, bio, location, avatar image, followers, gists, repos, and buttons for GitHub profile and to view followers.<br> - **Feature**: Detailed user profile with external links. |
| <img src="https://github.com/user-attachments/assets/e63ff8ce-5e3c-4a28-b610-46715683f493" width="400"/> | **Followers of Followers**: Allows viewing of followers of followers, and so on.<br> - **Feature**: Recursive follower exploration with dynamic loading. |
| <img src="https://github.com/user-attachments/assets/986c4200-4fbb-4e18-bc51-cf3ac633d6d5" width="400"/> | **Github Profile**: Opens Safari view controller using SFSafariServices to show GitHub profile.<br> - **Feature**: Secure in-app browsing using SFSafariViewController. |

