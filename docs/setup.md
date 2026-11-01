# Setup

1. PowerShell (Admin): `wsl --install -d Ubuntu-24.04`, restart, run it again if Ubuntu didn't install
2. `sudo apt update && sudo apt upgrade -y`
3. `sudo apt install -y verilator build-essential git python3-venv`
4. Git identity: `git config --global user.name/user.email`, `init.defaultBranch main`
5. SSH key: `ssh-keygen -t ed25519 -C "<machine>"`, add to GitHub, test with `ssh -T git@github.com`
6. VS Code + WSL extension, open projects with `code .`
