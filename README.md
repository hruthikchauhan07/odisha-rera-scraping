# Odisha RERA Project Scraper

This Python script is designed to scrape project details from the Odisha Real Estate Regulatory Authority (RERA) website. It extracts key information such as RERA registration number, project name, promoter name, promoter address, and GST number for listed projects.

## Features
- Fetches a list of projects from the Odisha RERA website.
- Navigates to individual project detail pages.
- Extracts specific details: RERA Registration Number, Project Name, Promoter Name, Promoter Address, and GST Number.
- Organizes the extracted data into a Pandas DataFrame.
- Includes robust error handling for network requests and data parsing.

## Prerequisites
Before running this script, ensure you have Python 3 installed on your system. You will also need the following Python libraries:

- **requests**: For making HTTP requests to web pages.
- **BeautifulSoup4 (bs4)**: For parsing HTML content.
- **pandas**: For data manipulation and creating DataFrames.

## Installation
Clone the repository (or download the script):
If you're setting up a new Git repository, you'll create it first, then add this file.

```bash
# If you haven't initialized a git repo yet
git init
git add .
git commit -m "Initial commit of RERA scraper"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
git push -u origin main
```

Install the required Python packages:
Open your terminal or command prompt and run:

```bash
pip install requests beautifulsoup4 pandas
```

## Usage
1. **Save the script**:
   Save the provided Python code (e.g., `rera_scraper.py`) in a directory on your computer.

2. **Run the script**:
   Navigate to the directory where you saved the script using your terminal or command prompt, and then execute:

   ```bash
   python rera_scraper.py
   ```

## Output
The script will print the scraped project details to your console in a tabular format (Pandas DataFrame).

### Example Console Output:
```
--- Scraped Project Details ---
  Rera Regd. No       Project Name             Promoter Name Address of the Promoter      GST No.
0  RP/01/2025/01362  BASANTI ENCLAVE  NEELACHAL INFRA DEVELOPERS PVT. LTD          Angul  B21AADCN5439J2ZH
1  RP/01/2025/01363         UDYAYEEN  SHAMCHAND BUILDERS PRIVATE LIMITED        Khordha  B21AADCN5439J2ZH
...
```

## Deployment to GitHub
To deploy this project to GitHub, follow these steps:

1. **Create a new GitHub repository**:
   - Go to GitHub and log in to your account.
   - Click on the **+** sign in the top right corner and select **New repository**.
   - Give your repository a name (e.g., `odisha-rera-scraper`), an optional description, and choose whether it's **Public** or **Private**.
   - Do **NOT** initialize the repository with a README, .gitignore, or license at this stage, as you'll be pushing your local files.

2. **Initialize a Git repository in your project folder**:
   Open your terminal or command prompt, navigate to the directory where your `rera_scraper.py` and this `README.md` file are located, and run:

   ```bash
   git init
   ```

3. **Add your files to the staging area**:

   ```bash
   git add .
   ```

   This command adds all files in the current directory to the staging area.

4. **Commit your changes**:

   ```bash
   git commit -m "Initial commit: Odisha RERA Scraper"
   ```

5. **Connect your local repository to the GitHub repository**:
   Replace `YOUR_USERNAME` and `YOUR_REPOSITORY_NAME` with your actual GitHub username and the name of the repository you created.

   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
   ```

6. **Rename your branch to main** (optional, but good practice):

   ```bash
   git branch -M main
   ```

7. **Push your code to GitHub**:

   ```bash
   git push -u origin main
   ```

   You might be prompted to enter your GitHub username and Personal Access Token (if you have 2FA enabled, which is recommended).

Your project will now be live on GitHub!

## Contributing
Feel free to fork this repository, make improvements, and submit pull requests. Any contributions are welcome!

## License
This project is open-sourced under the MIT License. See the LICENSE file for more details.
