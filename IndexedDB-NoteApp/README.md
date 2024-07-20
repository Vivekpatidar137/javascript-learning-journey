# IndexedDB Notes Demo

## Description
This project demonstrates the use of IndexedDB for storing, retrieving, and managing notes. IndexedDB is a low-level API for client-side storage of significant amounts of structured data, including files/blobs. This demo showcases basic CRUD operations on notes using IndexedDB.

## Project Structure
- **index.html:** The HTML file contains the structure of the web page, including a form for creating new notes and a section for displaying the notes.
- **style.css:** The CSS file provides basic styling for the web page.
- **index.js:** The JavaScript file contains all the logic for interacting with IndexedDB, handling form submissions, displaying notes, and deleting notes.

## Features
- **Add Notes:** Users can add new notes with a title and body.
- **Display Notes:** Notes stored in IndexedDB are displayed on the page.
- **Delete Notes:** Users can delete notes, which will be removed from both the display and IndexedDB.

## Understanding IndexedDB
- **Opening the Database:** The database is opened or created if it doesn't exist using `indexedDB.open()`.
- **Creating Object Stores:** An object store is created to store the notes, similar to tables in a relational database.
- **Adding Data:** Data is added to the object store using transactions.
- **Retrieving Data:** Data is retrieved using a cursor to iterate through the object store.
- **Deleting Data:** Data is deleted from the object store based on a unique key.

## Usage
1. Open `index.html` in a browser.
2. Enter a note title and body in the form and click "Create new note."
3. The note will be added to the list of notes and stored in IndexedDB.
4. Notes can be deleted by clicking the "Delete" button next to each note.

