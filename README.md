# **G U I D E**

1. Clone the Repository
    ```bash
    git clone https://github.com/mselletoe/brgy-kiosk-602.git
    ```

2. Install Vue Extension in VSCode

3. Setup Frontend
    ```bash
    cd frontend
    npm install -D tailwindcss@3.4.13 postcss autoprefixer
    npx tailwindcss init -p
    npm install daisyui
    npm i -D daisyui@latest
    ```

4. RUN FRONTEND
    ```bash
    npm run dev
    ```

5. Go back to root folder
    ```bash
    cd ..
    ```

6. Setup Backend
    ```bash
    cd backend
    python -m venv .venv
    ```

Windows Powershell: 
```powershell
.\.venv\Scripts\Activate.ps1
```
Mac: 
```bash
source .venv/bin/activate
```

7.  
```bash
python -m pip install --upgrade pip
```

8. RUN BACKEND
    ```bash
    uvicorn main:app --reload
    ```

9. When done, deactivate the virtual environment:
    ```bash
    deactivate
    ```

# **GIT WORKFLOW**

1. Create a branch
    ```bash
    git checkout -b branch-name
    ```

2. Make changes, commit, and push
    ```bash
    git add .
    git commit -m "Describe your changes"
    git push
    ```

# **REMINDERS**

1. Work on backend and frontend separately. If frontend, 'cd frontend' muna before you do anything. Same goes if backend-related.

2. Update your repository everytime-- before gumawa and mag-commit. Make sure nasa root folder kada mag a-add ng changes-- not inside backend or frontend.
    ```bash
    git pull origin main
    ```

3. Create a branch every week. Branch name format: name-week1

4. daisyUI: https://daisyui.com/

