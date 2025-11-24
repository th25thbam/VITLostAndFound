
# Problem Statement: VIT Lost and Found

1. Project Goal and Justification
The VIT Lost and Found platform is developed to provide a centralized, efficient, and reliable digital solution for managing lost and found items within the VIT University campus. This addresses the current reliance on informal and manual methods, which often results in items remaining unclaimed or not being reported effectively.

The primary goal is to reunify students with their belongings by creating a structured system for reporting, searching, and verifying claims, thereby enhancing convenience and fostering a trustworthy community environment.

2. Project Scope and Key Features
The platform's scope encompasses the full item lifecycle, from initial reporting to final claiming.

```bash
   Feature	               Description
   User                    Secure login and registration for all VIT students.
   Authentication

   Reporting Items         Students can submit comprehensive details (description, photo, location, date)
                           for both lost and found items.

   Search Functionality    Filter listings by category, location (hostels, academic blocks, mess halls), and keywords.

   Claim Management        Verification process that uses similarity checking to match the claimant's description against
                           the registered item details, ensuring items are returned to their rightful owners.

   Status Tracking         Items are tracked with status updates (Open, Claimed).
```

3. Technical Implementation and Architecture
The application is built as a console-based or backend-driven system using Python, prioritizing functionality and stability.
 
4. Project Structure (Files)
The project is structured modularly for clear separation of concerns:

main.py: Entry point of the application.

authentication.py: Handles student registration and login.

item_management.py: Contains logic for reporting, listing, and claiming items.

data.py & file_management.py: Handle interaction with the locally hosted data storage.

README.md & statement.md: Project documentation.

5. Validation and Testing
The system's core functionality is validated through specific test scenarios:

Registration Test (Test 1): Ensures new student profiles are created and saved correctly.

Reporting Test (Test 2): Verifies that new items are uploaded with accurate details and an Open status.

Claiming Test (Test 3): Confirms that the difflib-based similarity check accurately approves claims only when the distinction provided by the claimant sufficiently matches the distinction provided by the original finder, thus securing the item return process.





