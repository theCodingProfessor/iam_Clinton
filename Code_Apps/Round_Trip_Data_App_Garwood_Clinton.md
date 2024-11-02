## 📝 In-Browser Notepad Application

This notepad application lets website visitors create, edit, and delete notes directly in their web browser (e.g., Firefox, Chrome). There are no accounts, service logins, or downloads required; the data lives only on the device where it was created, ensuring privacy and simplicity.

### Application Overview

The site consists of four pages:
- **index.html** – Home page with options to view, edit, or create notes.
- **new_note.html** – Create a new note.
- **edit_note.html** – Edit an existing note.
- **about.html** – Information about the application.

One stylesheet (`notes.css`) and one main JavaScript file (`storage.js`) control the app’s functions. Bootstrap 5 is used for layout and styling.

### Key Features

- **Erase All Notes**: Delete all saved notes.
- **View/Edit**: Opens a note for viewing or editing.
- **Delete/Remove**: Erases a single selected note.
- **Save**: Save a newly created or edited note.

### Storage Information

The app uses the browser’s HTML5 `localStorage` to save notes, with storage capacity varying depending on the browser and device. Storage typically ranges from 2 to 10 MB, allowing for multiple notes while respecting each device’s limitations.

---

**Functionality**: A lightweight, browser-based notepad app for local note-taking.  
**Stack**: HTML/CSS, JavaScript, LocalStorage  
**License**: MIT License, 2023  
**Tags**: `Productivity`, `To-Do`, `LocalStorage`, `Tutorial`

---
[GitHub Repository](https://github.com/theCodingProfessor/Round_Trip_Data_Python_Flask_MongoDB)

### Notepad Home 
![App Home](../img/app_img/app_home_700.png 'The home page for the data application.') 

### Notepad Form Entry
![App Form](../img/app_img/app_form_700.png 'The web form used to collect information from the website visitor.') <br>

### Notepad Notes Page 
![App User](../img/app_img/new_user_700.png 'The information received from the user is displayed.') 

### App Database Table Display
![App Show](../img/app_img/show_users_700.png 'The records from the MongoDB data store are display.')
<hr><br>

&copy; Clinton Garwood  
[Home](../Hello_World.md) | [Work](../Experience) | [Apps](../Code_Apps) | [Degrees](../Degrees) 
