
## VIT Lost and Found

VIT Lost and Found is a centralized platform for VIT University students to quickly report, search for, and claim lost or found items on campus. Users can provide detailed descriptions, images, and location specifics to facilitate the easy and efficient reunification of students with their belongings.


## Table of Contents

1.Project Overview

2.Key Features

3.Technology Stack

4.How to Use

5.Instructions for Testing

6.Project Structure 
## 1.Project Overview

The VIT Lost and Found platform addresses the common problem of students losing personal belongings and struggling to locate them. This system provides a streamlined digital solution, allowing students to:

~Report Lost Items: Submit comprehensive details (description, photo, last known location, date) of a missing item.

~Report Found Items: Post information about articles they have found, including where and when the item was discovered.

~Search Functionality: Filter and search existing listings based on item category, location, and keywords.

~Claim Management: Implement a verification process to ensure items are returned to their rightful owners.
## 2.Key Features

✅ User Authentication (VIT Student Login).

🗺️ Location-based searching (e.g., specific hostels, academic blocks, mess halls).

🖼️ Image upload for visual identification.

🔔 Notification system for matching items.
## 3.Technology Stack

This project is intended to be built using modern web development tools.

Language:Python

Database:Locally Hosted(SQL)

Libraries:
difflib (For verifying similarity),
os, datetime
## 4.How to Use

Follow these instructions to run the project.

Prerequisites:

~Python installed

~An active internet connection

Step 1: Clone the repository Open terminal and run:

git clone [https://github.com/YourUsername/VIT-Lost-Found.git](https://github.com/YourUsername/VIT-Lost-Found.git)

cd VIT-Lost-Found

Step 2: Install Dependencies

Step 3: Run the application

python main.py
## 5.Instructions for Testing

To verify the functionality of the system, follow these steps:

Test 1: Registering a New Student

Launch the app

Select option 2.

Enter registration number, name and password.

The system saves your profile, now you can login.

Test 2: Reporting an item

Login

Select option 1 from dashboard.

Enter the details:

Item Name: Water bottle

Location: AB-1 418

Distinction: has a car sticker

The item is uploaded with a status Open.

Test 3: Claiming an item

Login with a different user.

Select option 2 from dashboard to see the list of all lost items.

Enter the item ID from the list.

Enter description: The system checks the similarity of the 
description enter with the disctinction entered by the finder.

Case 1: Type blue bottle.

System denies the claim.

Case 2: Type blue bottle with a sticker.

System approves the claim.

The item status is changed to Claimed and the system shares the finder's details.

## 6.Project Structure

VIT-Lost-and-Found

├── authentication.py
├── data.py           
├── file_management.py     
├── item_management.py    
├── main.py         
├── README.md              
└── statement.md      