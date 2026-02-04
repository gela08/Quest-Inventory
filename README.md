===========================================================
    QUEST LOG: CLOUD IMAGE MANAGER - SETUP GUIDE
===========================================================


<!-- token : ??? -->
 <!-- name: gela08 -->
  <!-- repo: gela08/Quest-Inventory -->
   <!-- folder path: images -->


PHASE 1: PREPARE THE VAULT (GITHUB SETUP)
-----------------------------------------
1. LOG IN to your GitHub account.
2. CREATE A REPOSITORY: Give it a name like "my-inventory".
3. CREATE A FOLDER: (Optional) Inside the repo, create a folder
   named "images". 
   *Note: Add a small text file to it so GitHub saves the folder.*

4. GENERATE YOUR SECRET KEY (TOKEN):
   - Go to Settings > Developer Settings.
   - Click "Personal access tokens" > "Tokens (classic)".
   - Click "Generate new token (classic)".
   - SCOPE: Check the box for "repo".
   - EXPIRY: Set it to "90 days".
   - COPY the code (ghp_...) and keep it safe!

PHASE 2: CONNECTING THE GEAR
----------------------------
1. OPEN index.html in your browser.
2. [SECRET KEY]: Paste your GitHub Token.
3. [USER/REPO]: Type your username and repo name 
   (Example: octocat/my-inventory).
4. [FOLDER_PATH]: Type your folder name (Example: images).
5. Click "RELOAD GEAR" to establish the connection.

PHASE 3: HOW TO PLAY
--------------------
- UPLOAD ITEM: Select an image from your computer to store it
  in the cloud vault.
- RELOAD GEAR: Sync with the cloud to see your current items.
- DISCARD: Permanently remove an item from your cloud vault.

TECHNICAL LOGS
--------------
- Storage Backend: GitHub REST API
- Encoding: Base64
- Theme: 2D Retro Game (8-bit)
===========================================================
