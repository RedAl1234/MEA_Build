TEAM Alpha:
* Load Testing
* Spike Testing

TEAM Bravo:
* Soak Testing
* Stress Testing

TEAM Charlie:
* Compatibility Testing
* Usability Testing

TEAM Delta:
* Scalability Testing
* Localization Testing
* Internationalization Testing

WHAT METRICS ARE USEFUL AND WHY???  <---- ASK THIS

----------------------------------------------------------------

1. Open Chrome, and add the [Selenium IDE](https://chrome.google.com/webstore/detail/selenium-ide/mooikfkahbdckldjjndioackbalphokd?hl=en) extension.

2. Open git bash and `cd` into the `LBG-Python` directory.

3. In git bash use the command `python lbg.py` to run the application.

4. Navigate to `http://localhost:8080/index.html` in Chrome.

5. Run the Selenium IDE extension and select "Record a new test in a new project".

6. Pick a name you like for the project, something like **LBG-Python** and hit the "OK" button.

7. Add the url `http://localhost:8080/index.html` in the box and hit "START RECORDING"

8. Record yourself creating a new item then stop the recording in the Selenium IDE.

9. Create a new test for each of the steps of CRUD.

10. Run all of the tests in order (you can rename them things like '01 - create' to order them easily)


----------------------------------------------------------------


1. Download the [Chrome driver](https://chromedriver.chromium.org/downloads) for your version of Chrome.

2. 