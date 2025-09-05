=============== G U I D E ===============

1. Clone the Repository
    git clone https://github.com/mselletoe/brgy-kiosk-602.git


2. Install Vue Extension in VSCode


3. Setup Frontend
    cd frontend
    npm install -D tailwindcss@3.4.13 postcss autoprefixer
    npx tailwindcss init -p
    npm install daisyui
    npm i -D daisyui@latest


4. RUN FRONTEND
    npm run dev


5. Go back to root folder
    cd ..


5. Setup Backend
    cd backend
    python -m venv .venv

    Windows Powershell: .\.venv\Scripts\Activate.ps1
    Mac: source .venv/bin/activate

    python -m pip install --upgrade pip


6. RUN BACKEND
    uvicorn main:app --reload


7. When done, deactivate the virtual environment:
    deactivate



=============== GIT WORKFLOW ===============

1. Create a branch
    git checkout -b branch-name


2. Make changes, commit, and push
    git add .
    git commit -m "Describe your changes"
    git push


=============== REMINDERS ===============

1. Create a branch every week. Branch name format: name-week1

2. daisyUI: https://daisyui.com/

3. 