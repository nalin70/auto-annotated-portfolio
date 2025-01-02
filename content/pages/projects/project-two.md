---
type: ProjectLayout
title: ' Employee Attendance Tracker'
colors: colors-a
date: '2021-10-20'
client: CareerPhi
description: ' Employee Attendance Tracker for offices This web app enables employees to check in/out and tracks attendance history. Admins can monitor attendance records and manage absentees, enhancing work flow management.'
featuredImage:
  type: ImageBlock
  url: /images/bg2.jpg
  altText: Project thumbnail image
media:
  type: ImageBlock
  url: 'https://assets.stackbit.com/components/images/default/default-image.png'
  altText: altText of the image
  caption: Caption of the image
  elementId: ''
---
## Project Summary

**Objective**: Develop a simple attendance tracker to record employees’ daily check-ins and check-outs, display attendance history, and mark absences.

**Core Features**:

1.  **Record Attendance**: Log employee check-in and check-out with date and time.

2.  **View Attendance History**: Display an individual employee’s attendance history.

3.  **Mark Absence**: Automatically identify and display employees marked as absent if no check-in is recorded by a specific time.



**User Story**: As an employee, I want to be able to log my check-in and check-out times so that my attendance is recorded accurately.

```
Employee Check-in and Check-out

  Scenario: Employee checks in
    Given the employee is logged into the system
    When the employee clicks the "Check-in" button
    Then the system records the check-in time with the current date and time
    And the system shows a message "Check-in successful at 04:34:50"

  Scenario: Employee checks out
    Given the employee is logged into the system
    And has checked in for the day
    When the employee clicks the "Check-out" button
    Then the system records the check-out time with the current date and time
    And the system shows a message "Check-out successful at 04:34:50"
```



Wireframes

### 1. **Dashboard**

*   **Components**: A list of employees with options to view individual attendance records.

*   **Actions**: Each employee has a button for “Check-in” and “Check-out.”

### 2. **Employee Attendance History**

*   **Components**: A table showing attendance records, with columns for Date, Check-in Time, Check-out Time, and Status (Absent/Present).

*   **Actions**: Allows the manager to filter by date range or sort by employee name.





