# Bugs

Below are some Bug samples that I wrote while working on previous projects.

**Priority and Severity:** P1 - Critical

**Title:** Banking application does not request a password during login, exposing sensitive financial data

**Description:** The banking application only prompts the user to enter a username during login and does not request a password. This flaw allows unauthorized access to the user's account, where all financial transactions and sensitive data are visible, posing a significant security risk.

**Steps to Reproduce:**
1.	Go to  https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login
2.	Enter a correct username
3.	Notice that the application logs in without asking for a password, granting access to all transactions and account details.
   
**Expected Result:**
The application should require both a username and password before granting access to the user's account, ensuring that only authorized users can view sensitive financial information.

**Actual Result:**
The application only asks for the username and provides access to the account without requesting a password, exposing all financial transactions.

**Test Data:**
**User:** Hermoine Granger

**Status:** NEW (NEW, IN PROGRESS, DONE, REOPEN)

------------------------------------------------------------------------
**Priority and Severity:** P3 - Medium

**Title:** Caffeine consumption calculator rounds off the final value incorrectly

**Description:** The Angular Consumption Calculator rounds the final caffeine consumption value to the nearest whole number. This behavior may lead to inaccuracies, especially when users need precise measurements. For example, a calculated value of 107.5 mg of caffeine is rounded to 108 mg, which might not be acceptable in scenarios requiring exact figures.

**Steps to Reproduce:**
  1.	Open the Consumption Calculator (globalsqa.com).
  2.	Enter 1 cup of coffee.
  3.	Set the caffeine per cup value to 107.5 mg.
  4.	Observe that the final caffeine consumption is displayed as 108 mg instead of 107.5 mg.
     
**Expected Result:**
The calculator should display the exact value of caffeine consumption without rounding, such as 107.5 mg.

**Actual Result:**
The calculator rounds the final value to 108 mg, leading to a potential loss of precision.

**Test Data:**
Cups of coffee: 1
Caffeine per cup: 107.5 mg

**Status:**: NEW (NEW, IN PROGRESS, DONE, REOPEN)
 ------------------------------------------------------------------------

**Priority and Severity:** P2 - High

**Title:** Non-responsive elements on the Demoblaze website

**Description:** Certain elements on the Demoblaze website (https://www.demoblaze.com/index.html) are not responsive, leading to a poor user experience on different devices. When the site is accessed from mobile devices or smaller screen sizes, some elements do not adjust properly, resulting in overlapping content, distorted images, or inaccessible navigation options.

**Steps to Reproduce:**
   1.	Open the Demoblaze website (https://www.demoblaze.com/index.html) on a mobile device or resize the browser window to a smaller screen size.
   2.	Navigate through different sections of the site, such as the homepage, product pages, and navigation bar.
   3.	Observe the behavior of various elements as the screen size changes, particularly:
        o	Header Navigation Bar: Does not collapse or adjust correctly, causing options to overlap.
        o	Product Images: Some images stretch or do not scale down properly, leading to distortion.
        o	Footer: Certain links are not accessible or overlap when viewed on smaller screens.
     	
     	
**Expected Result:**
All elements on the website should be fully responsive, adjusting seamlessly to different screen sizes without causing content overlap, distortion, or functionality issues.

**Actual Result:**
Some elements on the website do not respond properly to changes in screen size, leading to a compromised layout and reduced usability on mobile devices.

**Test Data:**
Browser: Chrome, Firefox
Devices: Mobile (iPhone, Android), Desktop (using responsive design mode)

**Status:** NEW (NEW, IN PROGRESS, DONE, REOPEN)

