# Instagram Scraping Script

This Python script is designed to download post images from a specific Instagram account using Selenium and some other libraries.

## Requirements

- Python 3.x
- Selenium
- wget

You can install the required libraries by running the following commands in the terminal or command prompt:

\`\`\`bash
pip install selenium wget
\`\`\`

## Usage

1. Clone or download this repository to your computer.
2. If Python is not installed, download and install it from the [official Python website](https://www.python.org/downloads/).
3. Navigate to the project directory in the terminal or command prompt:

\`\`\`bash
cd path/to/instagram_scraping_accaunt_images
\`\`\`

4. Set your Instagram username and password:

\`\`\`python
username = 'your_instagram_username'
password = 'your_password'
\`\`\`

5. Specify the destination location to download the images:

\`\`\`python
dest_loc = r'C:\Users\ASUS\Desktop\instagram_scraping_accaunt_images\instaphotos'
\`\`\`

6. Run the script in the terminal or command prompt:

\`\`\`bash
python instagram_scraper.py
\`\`\`

7. The script will prompt you to enter a search query. After selecting a result, it will proceed to download the post images from that account.

## Notes

- Downloaded images will be saved in the \`instaphotos\` folder located at the specified destination.
- The download process may take some time, so please be patient.
- The script may need updates depending on changes to the Instagram website. Check this repository for updates. 
