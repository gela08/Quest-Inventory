===========================================================
GITHUB IMAGE MANAGER - SETUP & INSTRUCTIONS
===========================================================

1. GITHUB CLOUD SETUP
---------------------
To use this app, you must first prepare your GitHub storage:

A. Create a Repository:
   Go to GitHub and create a new repository (e.g., "my-cloud-storage").

B. Generate an Access Token:
   1. Go to GitHub Settings > Developer Settings.
   2. Select "Personal access tokens" > "Tokens (classic)".
   3. Click "Generate new token (classic)".
   4. Check the "repo" box (this allows the app to save images).
   5. Set expiration to "90 days".
   6. Click "Generate" and COPY the token immediately.

2. RUNNING THE APPLICATION
--------------------------
1. Open "index.html" in any web browser (Chrome, Edge, etc.).
2. In the top settings panel, enter:
   - Token: Paste your secret key here.
   - Repo: Your username/repository-name (e.g., "johnsmith/my-cloud").
   - Path: The folder name where images are kept (e.g., "images").
3. Click "RELOAD GEAR" or "Refresh List" to see your files.

3. FEATURES
-----------
- LOOT ITEM: Click this to upload a new image from your computer.
- RELOAD GEAR: Click this to fetch the latest images from GitHub.
- DISCARD/DELETE: Click the delete button on any image to remove it.

4. IMPORTANT NOTES
------------------
- Security: Do not share your GitHub Token with others. 
- Overwriting: If you upload an image with the same filename as 
  one already in the folder, the app will update the existing file.
- Formats: Use .jpg, .png, .gif, or .webp files.

===========================================================
