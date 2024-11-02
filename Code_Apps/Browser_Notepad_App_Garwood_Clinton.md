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
![Notepad Home](../img/app_img/notepad_home.png 'The home page for the Notepad App.') 

### Notepad New Note Entry Form
![Notepad Form](../img/app_img/notepad_entry.png 'The web form used to collect information from the website visitor.') <br>

### Notepad All Note Display 
![Notes Display](../img/app_img/notepad_list.png 'All notes received from the user are displayed.') 

### Notepad About Page
![About Notepad](../img/app_img/notepad_about.png 'General data about the Notepad App.')

### Notepad Limitations
![Notepad Limits](../img/app_img/notepad_limits.png 'Statement on limits of the Notepad App.')
<hr><br>
<hr><br>

&copy; Clinton Garwood  
[Home](../Hello_World.md) | [Work](../Experience) | [Apps](../Code_Apps) | [Degrees](../Degrees) 

