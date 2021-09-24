# Accessibility Review Data Collection

!!! alert "How accessible are state election information sites, especially the information about accessible voting?"
    We know that’s a bit meta, but we had to choose a consistent page to review, and that was an easy choice

If you are continuing from collecting basic website information you already have the links to the state website you will be reviewing for accessibility.

If you are starting with this site, or want to do another state site, go to [this resource](state_resources.md) to pick a state and find a link to their voter information site and the accessible voting information page.

[Check with WebAim's WAVE](https://wave.webaim.org){: .md-button .md-button--green }

[Check with Microsoft Insights](https://beta.lfocalculator.org){: .md-button .md-button--blue }

[Check with WAI’s Easy Checks](https://beta.lfocalculator.org){: .md-button .md-button--amber }


## Sample flows

### Check with WebAim’s WAVE

* Go to wave.webaim.org
* Enter the URL for the page you are checking (for example: [https://vote.ST.gov/accessible-voting.html](https://vote.ST.gov/accessible-voting.html)

The results will appear on the screen. Look at the panel on the left for a Summary report. WAVE gives a summary report of 6 items. Then click on Details to see more

Use [this form](form.md) to report what you found.
You can continue with another page at the end.

#### Fields to collect

* Your name and email
* What state is this website in (List)
* What kind of page: Home Page, Accessible Voting Page, Other: ____
* URL of the page

### WAVE Results

* How many errors were found?
* What types of errors and how many of each are shown on the details page?
* How many contrast errors?
* How many alerts?
* What type of alerts are shown on the details page?
* How many features were found?
* How many structural elements were found?
* How many ARIA elements were found?

### Check with WAI’s Easy Checks

* Go to the page you want to test
* Follow the instructions in the form to complete 5 quick checks

#### Fields and instructions

Enter information to identify the page you are testing

* Your name and email
* What state is this website in (List)
* What kind of page: Home Page, Accessible Voting Page, Other: ____
URL of the page

!!! alert "Easy Check 1: Is there a meaningful page title?"
    Look at the text that appears in the browser tab to identify the web page. You can also bookmark the page and then look at the how the page is listed in your bookmarks:

* Page TITLE: What is the text in the page title in the browser tab or bookmarks
* Page CONTENT TITLE: What is the title of the page shown in the page content (it may be different or longer

!!! alert "Easy Check 2: Do images have alt text"
    Follow the instructions from the Web Accessibility Initiative to check for alt text on images using WAVE, or with the WebDev toolbar. Or, use your own tool.

* How many images without alt text are found (enter 0 for none)
* How many of those  images are in the page navigation or frame?
* How many of those images are in the content?
* If possible, describe an example of information or navigation that a voter would not have access to because of missing alt text.

!!! Easy Check 3: Is content structured with headings>
    Follow the instructions from the Web Accessibility Initiative to check for alt text on images using The HTML Validator. Or, use your own tool.

* Does the content include structural headings?
* Do you see any text that looks like a heading, but is not marked up to be a structural heading?
* Are the headings numbered in a logical order matching the logic of the content.

!!! alert "Easy Check 4: Can text be resized and does it redisplay when the browser window is resized?"

* Change the width of the browser window.
* Does the text “reflow” to fit in the window?
* Does it maintain a logical order when the browser window gets very narrow?
* Does the banner or menu layout of the page change when as the browser width changes?
* Is the page readable at 100% zoom at a narrow browser width

Resize the text to 200%. In most browsers, you can do this by holding the ```Option``` or ```Command``` key and pressing ```+```; 4-5 presses should reach 200% . You can find instructions from the [Web Accessibility Initiative](https://wai.org) if needed.

* Does the text “reflow” to fit in the window, maintaining the layout of the page
* Is there any horizontal scrolling at 200%
