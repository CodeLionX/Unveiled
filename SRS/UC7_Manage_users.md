# Unveiled - Use-Case Specification: Manage users

## 1. Use-Case Name
Manage users on website.

### 1.1 Brief Description
On the website the administrator of the Unveiled server is able to manage all registered users. This includes chanching
permissions of specific users or deactivate them from the server.

### 1.2 Screenshot Mockup
![][screenshot]

## 2. Flow of Events

### 2.1 Basic Flow
![][basic flow]

### 2.2 Alternative Flow
(n/a)

## 3. Special Requirements
(tbd)

## 4. Preconditions
### 4.1 User has to be administrator
Only users with the administrator-permission are allowed to change user permission and deactivate users on the manage_users screen.

### 4.2 Logged-in user
The user should be logged-in as administrator.

## 5. Postconditions
No use cases require this use case to be completed.

## 6. Extension Points
(n/a)

## 7. Function Point calculation
This use case was estimated with 9 FPs. See the table and screenshot below for details:

| Transaction | DET's | RET's | FTR's | Complexity |
|-----------------------|:-:|:-:|:-:|:---:|
| EI Userlist           | 2 | - | 0 | Low |
| EO Userlist           | 3 | - | 1 | Low |
| ILF User              | 12 | 0 | - | Low |
| EIF                   | - | - | - | - |

![][fp calculation]

All function point calculation tables are also located in one spreadsheet. Please take a look at this [document][fpc spreadsheet].

<!-- Link definitions: -->
[basic flow]: https://raw.githubusercontent.com/SAS-Systems/Unveiled-Documentation/master/Bilder/UC_Diagrams/UC_Diagram_Manage_users.png "Use Case Diagram: Manage users"
[screenshot]: https://raw.githubusercontent.com/SAS-Systems/Unveiled-Documentation/master/Bilder/Screenshots_website/manage_users.PNG "Manage users screenshot"
[fp calculation]: https://raw.githubusercontent.com/SAS-Systems/Unveiled-Documentation/master/Bilder/FP%20calculation/FP_manage_users.PNG "FP calculation"
[fpc spreadsheet]: https://docs.google.com/spreadsheets/d/1qaz88UHaRb7cXoiOkJ0dJ-R7JvfTxPslJvZ183o6wnU/edit?usp=sharing "Function point calculation spreadsheet"
