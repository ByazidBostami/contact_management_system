Simple Contact Management System
This is a basic Django-based Contact Management System where users can store, view, update, delete, and search for contact information. Additionally, the application includes functionality for admin login to manage contacts.

Features
Add Contact: Create new contacts with first name, last name, email, phone number, and address fields.
View Contacts: View a list of all contacts on the homepage, showing their first name, email, and phone number.
Contact Details: Clicking on a contact displays detailed information, including the last name and address.
Edit Contact: Modify existing contact information.
Delete Contact: Remove any contact from the system.
Search Contacts: Search for contacts by first name or email.
Superuser Login: Admin login for managing contacts with the following credentials:
Username: admin
Password: 123

contact_management/
│
├── contacts/
│   ├── migrations/
│   ├── templates/
│   │   └── contacts/
│   │       ├── add_contact.html
│   │       ├── edit_contact.html
│   │       ├── contact_detail.html
│   │       └── home.html
│   ├── forms.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
│
├── contact_management/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── db.sqlite3
├── manage.py
├── README.md
└── requirements.txt
Usage
Add Contact:

Click "Add Contact" on the homepage.
Fill in the form and submit.
View Contact:

The homepage lists all contacts. Click a contact’s name to view its details.
Edit Contact:

Click the "Edit" button next to a contact on the homepage to modify the contact's information.
Delete Contact:

Click the "Delete" button to remove a contact.
Search Contact:

Use the search bar on the homepage to search by first name or email.
