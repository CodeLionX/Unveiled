# Unveiled - Use-Case Specification: View own media

## 1. Use-Case Name
View own media.

### 1.1 Brief Description
The logged-in user is able to search his uploaded media files in the web interface. Therefore he is using the media browser described in [Use Case: Browse media](). When he selects one media file, a new screen is opened. This screen shows the picture or video. It is directly streamed from the server.

### 1.2 Screenshot Mockup
![][screenshot]

## 2. Flow of Events

### 2.1 Basic Flow
![][basic flow]

### 2.2 Alternative Flow
(n/a)

## 3. Special Requirements
(n/a)

## 4. Preconditions
### 4.1 Logged-in user
The user should be logged-in.

### 4.2 Files available
The user should have already uploaded some files to the server. Otherwise no files are available to deletion.

### 4.3 User already in media browser screen
The user should have navigated to the media browser screen. There he is able to select a media file.

## 5. Postconditions
No use cases require this use case to be completed.

## 6. Extension Points
(n/a)

## 7. Function Point calculation
This use case was estimated with 12 FPs. See the table and screenshot below for details:

| Transaction | DET's | RET's | FTR's | Complexity |
|-----------------------|:-:|:-:|:-:|:---:|
| EI Viewer             | 4 | - | 1 | Low |
| EO Notification       | 2 | - | 0 | Low |
| ILF Video             | 1 | 6 | - | Average |
| EIF                   | - | - | - | - |

![][fp calculation]

All function point calculation tables are also located in one spreadsheet. Please take a look at this [document][fpc spreadsheet].

<!-- Link definitions: -->
[basic flow]: https://raw.githubusercontent.com/SAS-Systems/Unveiled-Documentation/master/Bilder/UC_Diagrams/UC_Diagram_View_own_media.png "Use Case Diagram: View own media"
[screenshot]: https://raw.githubusercontent.com/SAS-Systems/Unveiled-Documentation/master/Bilder/Screenshots_website/watch_media.PNG "Watch Media Screenshot"
[fp calculation]: https://raw.githubusercontent.com/SAS-Systems/Unveiled-Documentation/master/Bilder/FP%20calculation/FP_view_own_media.PNG "FP calculation"
[fpc spreadsheet]: https://docs.google.com/spreadsheets/d/1qaz88UHaRb7cXoiOkJ0dJ-R7JvfTxPslJvZ183o6wnU/edit?usp=sharing "Function point calculation spreadsheet"
