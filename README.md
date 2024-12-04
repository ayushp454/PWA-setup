### Steps to Set Up the PWA Project

1. **Clone the PWA GitHub Repository:**
   Open your terminal and clone the repository from GitHub:
   ```bash
   git clone https://github.com/waveRFID/pwa
   ```

2. **Navigate to the Project Root Folder:**
   Change to the project directory:
   ```bash
   cd pwa
   ```

3. **Set the Node Version to 14:**
   The project requires Node.js version 14. If you don't have it installed or want to switch to this version, you can use `nvm` (Node Version Manager).

4. **Install NVM (if not already installed):**
   If you don't have `nvm` installed, you can do so with the following command:
   ```bash
   curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
   ```
   After installation, restart your terminal or run the following to make `nvm` available:
   ```bash
   source ~/.bashrc   # or source ~/.zshrc for zsh users
   ```

5. **Install Node.js Version 14 Using NVM:**
   To switch to Node.js version 14, use:
   ```bash
   nvm install 14
   ```
   To verify that Node.js version 14 is active, run:
   ```bash
   node -v
   ```
   It should return something like `v14.x.x`.

6. **Install Project Dependencies:**
   Now that you're using the correct Node version, install the project dependencies by running:
   ```bash
   npm install
   ```

7. **Start the Project:**
   After the installation is complete, you can start the project with:
   ```bash
   npm start
   ```
