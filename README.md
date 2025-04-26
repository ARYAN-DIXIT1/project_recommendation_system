# Project Recommendation System

This is an AI-powered application that recommends the best GitHub projects based on a user's prompt.  
It uses SentenceTransformer (all-MiniLM-L6-v2) to intelligently rank projects according to their relevance.  
Each user's search history is stored and managed separately for future use.

---

## Features

- Fetches GitHub projects using GitHub API.
- Ranks projects using SentenceTransformer model (all-MiniLM-L6-v2).
- Displays the best matching project with a clear reason.
- Saves user profiles and past searches locally.
- Keeps GitHub token secure via .env file.
- Simple and interactive Streamlit frontend.

---

## Folder Structure


---

## Setup Instructions

### 1. Clone the repository


---

### 2. Create a virtual environment


---

### 3. Activate the virtual environment

- On Windows:


---

### 4. Install the required packages


---

### 5. Set up GitHub Token

- Create a .env file in the root directory.
- Add your GitHub token:


Your token is never shown publicly in the app.

---

### 6. Run the Streamlit App
