# scribd-downloader
Download your books from Scribd in PDF format for personal and offline use.

### Please note:
1) this is a very first version, so expect bugs to happen. Please report them [opening a new issue](https://github.com/evmer/scribd-downloader/issues).
2) only Scribd **eBooks** are supported for now (no PDF Documents/Audiobooks etc.)

## Installation

Install the required Python libraries:

  >$ pip install PyPDF2

Install Playwright for Python:
  
  >$ pip install playwright
  
  >$ playwright install

## Running

Watch the [demonstration video](https://youtu.be/sbMb_EOFNTA).

1) Run the script:

>$ python3 run.py [BOOK URL]

2) A browser instance will open. Proceed with the login on Scribd and make sure to solve the captcha (if any). This step is required only for the first run. If you later want to login with another account, delete the session.json file and re-run the script.

3) The script will start downloading the book:

![image](https://user-images.githubusercontent.com/10036897/208117827-afc6087e-fc76-4bca-8138-be839113d666.png)

## TODO:
- [ ] Scale/reduce pdf page size
- [ ] Render links in the PDFs
- [ ] Add EPUB conversion feature
- [ ] Add support for Documents
- [ ] Add support for Audiobooks

# DISCLAIMER:
The code is not intended for piracy or unlawful re-sharing purposes. You can only download the books you have purchased for the sole purpose of personal use. I do not take responsibility for illegal use of the software.
