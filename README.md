# UV install ation steps for Windows

1. Create a folder

2. uv package installer
	powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"

3. uv init

4. uv --version

5. uv venv

6. Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser

7.  .\.venv\Scripts\activate

8. virtual environment is created with (folder_name)

# UV installation in Mac

1. Create a folder
2. UV package installer
        curl -LsSf https://astral.sh/uv/install.sh | sh
3. Uv init
4. Uv —version
5. Uv venv
6. Source .venv/bin/activate —> it activate the virtual environment with (folder name)


# Git commands to push the code in github

1. git init
2. git add .
3. git commit -m "first commit"
4. git branch -M main
5. git git remote add origin https://github.com/AIAGENTGURUSHANTHA/GURU_GENAI_LEARN.git
6. git push -u origin main