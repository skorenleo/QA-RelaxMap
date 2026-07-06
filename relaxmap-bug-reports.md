# RelaxMap Bug Reports

## sk-001

**Reporter:** Svitlana Koren

**Assignee:** Developer

**Status:** New

**Type:** UI/UX

**Severity:** Minor

**Priority:** Low

**Environment:** OS: macOS Tahoe v26.2<br>Browser: Google Chrome 149.0.7827.54<br>Testing Devices: Descktop(1440)(Chrome DevTools), iPad mini (Chrome DevTools), iPhone SE (Chrome DevTools)

**Summary:** Copyright displays an outdated year in the footer

**Description:** 

**Pre-conditions:** 

**1** Open the Register page https://relax-map-front-end.vercel.app/register

**Steps to reproduce:** 

**1** Check the copyright text in the footer.

**Actual result:** 

**The footer displays: "© 2025 Relax Map".** 

**Expected result:** 

**The footer displays: "© 2026 Relax Map".** 

**Attachments:** [Screenshot 1.png](https://drive.google.com/file/d/1S4QX4g_keAOWvEn5p5roWAKFv0uU1Vi1/view?usp=drive_link)

**Additional info:** 

**The same issue is also present on the Login page https://relax-map-front-end.vercel.app/login** 


---

## sk-002

**Reporter:** Svitlana Koren

**Assignee:** Developer

**Status:** New

**Type:** UI/UX

**Severity:** Minor

**Priority:** High

**Environment:** OS: macOS Tahoe v26.2<br>Browser: Google Chrome 149.0.7827.54<br>Testing Devices: Descktop(1440)(Chrome DevTools), iPad mini (Chrome DevTools), iPhone SE (Chrome DevTools)

**Summary:** The "Sign Up" button has no background color in the default state

**Description:** 

**Pre-conditions:** 

**1** Open the Register page https://relax-map-front-end.vercel.app/register

**Steps to reproduce:** 

**1** Locate the "Sign Up" button.

**2** Check the button appearance without hovering over it.

**Actual result:** 

**The button has no background color in the default state. The background color appears only when the cursor hovers over the button.** 

**Expected result:** 

**The button is displayed with a background color in the default state according to the UI Kit. The hover state color matches the design specification.** 

**Attachments:** [video1.mov](https://drive.google.com/file/d/1tpz4iR20_s83pTMeHwMWLAv4vHzimqw1/view?usp=sharing)

---

## sk-003

**Reporter:** Svitlana Koren

**Assignee:** Developer

**Status:** New

**Type:** UI/UX

**Severity:** Trivial

**Priority:** Low

**Environment:** macOs Tahoe v.26.2, “Google Chrome” (“Version 149.0.7827.54”)

**Summary:** The copyright section is visible only after scrolling on the Registration page

**Description:** 

**Pre-conditions:** 

**1** Open the Register page https://relax-map-front-end.vercel.app/register

**Steps to reproduce:** 

**1** View the page without scrolling.

**2** Check the copyright section at the bottom of the page.

**Actual result:** 

**The copyright section is outside the initial viewport and becomes visible only after scrolling down.** 

**Expected result:** 

**The copyright section is visible within the initial viewport without scrolling, according to the Figma design.** 

**[Screenshot sk-003.png](https://drive.google.com/file/d/1eQ_gPmAunJfuvNybb8Qxqct_B5eupBTg/view?usp=drive_link)**

**Attachments:** [video2.mov](https://drive.google.com/file/d/1JUu7vYG3tPWOm9a-ZlwsIpepgtv2ir6b/view?usp=drive_link)

---

## sk-004

**Reporter:** Svitlana Koren

**Assignee:** Developer

**Status:** New

**Type:** Functional

**Severity:** Critical

**Priority:** High

**Environment:** OS: macOS Tahoe v26.2<br>Browser: Google Chrome 149.0.7827.54<br>Testing Devices: Descktop(1440)(Chrome DevTools), iPad mini (Chrome DevTools), iPhone SE (Chrome DevTools)

**Summary:** The "Locations" link in the footer redirects to an incorrect route

**Description:** 

**Pre-conditions:** 

**1** Open the Home page https://relax-map-front-end.vercel.app/

**Steps to reproduce:** 

**1** Scroll down to the footer.

**2** Click the "Locations" link.

**3** Check the destination route.

**Actual result:** 

**The footer link redirects to the /places route.** 

**Expected result:** 

**The footer link redirects to the /locations route.** 

**Attachments:** [sk-004(1).png](https://drive.google.com/file/d/1gQJzy2dGXFAwf4srUHjqqpWNAMLnscRA/view?usp=drive_link), [sk-004(2).png](https://drive.google.com/file/d/1-Cc7NOEPSO3mlHjlripXgf_SXk3iFrvj/view?usp=drive_link)

---

## sk-005

**Reporter:** Svitlana Koren

**Assignee:** Developer

**Status:** New

**Type:** Functional

**Severity:** Major

**Priority:** Medium

**Environment:** OS: macOS Tahoe v26.2<br>Browser: Google Chrome 149.0.7827.54<br>Testing Devices: Descktop(1440)(Chrome DevTools), iPad mini (Chrome DevTools), iPhone SE (Chrome DevTools)

**Summary:** After successful authentication, the user is redirected to the Home page instead of their Profile page.

**Description:** 

**Pre-conditions:** 

**1** Open the Login page https://relax-map-front-end.vercel.app/register

**Steps to reproduce:** 

**1** Enter valid credentials (e.g., email: skorenleo@gmail.com, password: 12345678).

**2** Click the "Log In" button.

**Actual result:** 

**The user is redirected to the Home page.** 

**Expected result:** 

**The user is redirected to their Profile page according to the requirements.** 

**Attachments:** [video3.mov](https://drive.google.com/file/d/15zh0Yc4DyegupwfUoMS6u89ga9wAEtxI/view?usp=drive_link)

---

## sk-006

**Reporter:** Svitlana Koren

**Assignee:** Developer

**Status:** New

**Type:** UI

**Severity:** Minor

**Priority:** Low

**Environment:** macOs Tahoe v.26.2, “Google Chrome” (“Version 149.0.7827.54”)

**Summary:** Header and footer links do not display an underline on hover

**Description:** 

**Pre-conditions:** 

**1** Open https://relax-map-front-end.vercel.app/.

**Steps to reproduce:** 

**1** Hover over the "Home" link in the header.

**Actual result:** 

**The underline hover effect is not displayed.** 

**Expected result:** 

**The underline hover effect is displayed according to the requirements.** 

**Attachments:** [sk-006.png](https://drive.google.com/file/d/1QDYjNxZPe-GKhhO3z7x4RD5QXLjFiSRN/view?usp=drive_link)

**Additional info:** 

**The issue is also present on all header links: Logo, Locations, and My Profile.** 

**The issue is also present on all footer links: Logo, Home, and Locations.** 


---

## sk-007

**Reporter:** Svitlana Koren

**Assignee:** Developer

**Status:** New

**Type:** Functional

**Severity:** Major

**Priority:** High

**Environment:** OS: macOS Tahoe v26.2<br>Browser: Google Chrome 149.0.7827.54<br>Testing Devices: iPad mini (Chrome DevTools), iPhone SE (Chrome DevTools)

**Summary:** The burger menu does not close after navigating to another page

**Description:** 

**Pre-conditions:** 

**1** Open https://relax-map-front-end.vercel.app/.

**2** Open the burger menu.

**Steps to reproduce:** 

**1** Click any navigation link in the burger menu.

**Actual result:** 

**The burger menu remains open.** 

**Expected result:** 

**The user is navigated to the selected page, and the burger menu closes automatically.** 

**Attachments:** [video-sk-007.mov](https://drive.google.com/file/d/1KXz6WWBeSlK8TxvJg_mO-QUsPdb0VR0J/view?usp=drive_link)

---

## sk-008

**Reporter:** Svitlana Koren

**Assignee:** Developer

**Status:** New

**Type:** Functional

**Severity:** Critical

**Priority:** High

**Environment:** OS: macOS Tahoe v26.2<br>Browser: Google Chrome 149.0.7827.54<br>Testing Devices: Descktop(1440)(Chrome DevTools), iPad mini (Chrome DevTools), iPhone SE (Chrome DevTools)

**Summary:** The "My Profile" link redirects to an incorrect route

**Description:** 

**Pre-conditions:** 

**1** Log in to the application using:<br><br>Email: koren@gmail.com<br>Password: 1q2w3e4r

**2** Open https://relax-map-front-end.vercel.app/

**Steps to reproduce:** 

**1** Click the "My Profile" link in the header.

**Actual result:** 

**The user is redirected to the /pro route.** 

**Expected result:** 

**The user is redirected to their Profile page at the /profile/[userId] route.** 

**Attachments:** [sk-008-01.png](https://drive.google.com/file/d/11p8qBHE5ssjWSLGGJTFtmBMnhFni3FCN/view?usp=drive_link), [sk-008-02.png](https://drive.google.com/file/d/19yuyVy4rTZB7gjoKCJZPXqyj7-0R-Sfs/view?usp=drive_link)

---

## sk-009

**Reporter:** Svitlana Koren

**Assignee:** Developer

**Status:** New

**Type:** UI/UX

**Severity:** Trivial

**Priority:** Medium

**Environment:** OS: macOS Tahoe v26.2<br>Browser: Google Chrome 149.0.7827.54<br>Testing Devices: Descktop(1440)(Chrome DevTools), iPad mini (Chrome DevTools), iPhone SE (Chrome DevTools)

**Summary:** The default profile avatar placeholder is missing in the header

**Description:** 

**Pre-conditions:** 

**1** Log in to the application using:<br><br>Email: koren@gmail.com<br>Password: 1q2w3e4r

**Steps to reproduce:** 

**1** Check the user's profile avatar displayed in the header.

**Actual result:** 

**The default avatar placeholder is missing. The profile icon is displayed incorrectly.** 

**Expected result:** 

**A standard profile avatar placeholder is displayed.** 

**Attachments:** [sk-009.png](https://drive.google.com/file/d/1GouJCoKUeRcEvo-TgDpljqXmqj6xCNPG/view?usp=drive_link)

---

## sk-010

**Reporter:** Svitlana Koren

**Assignee:** Developer

**Status:** New

**Type:** Functional

**Severity:** Critical

**Priority:** High

**Environment:** OS: macOS Tahoe v26.2<br>Browser: Google Chrome 149.0.7827.54<br>Testing Devices: Descktop(1440)(Chrome DevTools), iPad mini (Chrome DevTools), iPhone SE (Chrome DevTools)

**Summary:** The "Sign Up" link redirects to an incorrect route

**Description:** 

**Pre-conditions:** 

**1** Open https://relax-map-front-end.vercel.app/

**2** The user is not logged in.

**Steps to reproduce:** 

**1** Click the "Sign Up" link in the header.

**2** Check the URL after navigation.

**Actual result:** 

**The user is redirected to the /signup route.** 

**Expected result:** 

**The user is redirected to the Registration page at the /register route.** 

**Attachments:** [sk-010.png](https://drive.google.com/file/d/1GNlV3gQxoX1XMdkwyVmS-IYNJj5i0lyS/view?usp=drive_link)

---

## sk-013

**Reporter:** Svitlana Koren

**Assignee:** Developer

**Status:** New

**Type:** Functional

**Severity:** Minor

**Priority:** High

**Environment:** OS: macOS Tahoe v26.2<br>Browser: Google Chrome 149.0.7827.54<br>Testing Devices: Descktop(1440)(Chrome DevTools), iPad mini (Chrome DevTools), iPhone SE (Chrome DevTools)

**Summary:** The location rating in the Popular Locations section does not match the rating on the Location Details page

**Description:** 

**Pre-conditions:** 

**1** Open https://relax-map-front-end.vercel.app/

**2** Locate "Lvivskyi Zatyshok" in the Popular Locations section.

**Steps to reproduce:** 

**1** Note the location rating displayed in the Popular Locations section.

**2** Click the "View Location" button to open the Location Details page.

**3** Compare the rating displayed on the Home page with the rating on the Location Details page.

**Actual result:** 

**The location displays a 5-star rating in the Popular Locations section, while the Location Details page has no reviews, resulting in a 0-star rating.** 

**Expected result:** 

**The rating displayed in the Popular Locations section matches the rating displayed on the corresponding Location Details page.** 

**Attachments:** [video-sk-013.mov](https://drive.google.com/file/d/1jQcziwz9Ia_5NyJg1nH9Xg05NgwoFO3m/view?usp=drive_link)

---

## sk-014

**Reporter:** Svitlana Koren

**Assignee:** Developer

**Status:** New

**Type:** UI/UX

**Severity:** Minor

**Priority:** Medium

**Environment:** iPad mini (Chrome DevTools), Google Chrome (“Version 149.0.7827.54”)

**Summary:** Long review text is not truncated and increases the height of the review card

**Description:** 

**Pre-conditions:** 

**1** Open https://relax-map-front-end.vercel.app/.

**2** Locate a review card with a long review text.

**Steps to reproduce:** 

**1** Check how the review text is displayed.

**Actual result:** 

**The long review text is displayed in full, causing the review card height to increase.** 

**Expected result:** 

**The long review text is truncated with an ellipsis (...), and the review card maintains the size specified in the design.** 

**Attachments:** [sk-014.png](https://drive.google.com/file/d/12PFBQXPLz6cC7WX9EQ_3HZ4n-g_zIHJB/view?usp=drive_link)

---

## sk-015

**Reporter:** Svitlana Koren

**Assignee:** Developer

**Status:** New

**Type:** Functional

**Severity:** Minor

**Priority:** Medium

**Environment:** OS: macOS Tahoe v26.2<br>Browser: Google Chrome 149.0.7827.54<br>Testing Devices: Descktop(1440)(Chrome DevTools), iPad mini (Chrome DevTools), iPhone SE (Chrome DevTools)

**Summary:** Search by location type returns no results on the Locations page

**Description:** 

**Pre-conditions:** 

**1** Open https://relax-map-front-end.vercel.app/

**Steps to reproduce:** 

**1** Enter "Пляж" in the search field.

**2** Click the "Find a Place" button.

**Actual result:** 

**The /locations page opens, but the search query "Пляж" returns no matching results. A message indicating that no locations were found is displayed.** 

**Expected result:** 

**The /locations page displays locations matching the entered search query.** 

**Attachments:** [video-sk-015.mov](https://drive.google.com/file/d/1f-VTAj4T542lzvyM5vzKqtyN-DNdG9g_/view?usp=drive_link)

---

## sk-017

**Reporter:** Svitlana Koren

**Assignee:** Developer

**Status:** New

**Type:** Functional

**Severity:** Trivial

**Priority:** Low

**Environment:** OS: macOS Tahoe v26.2<br>Browser: Google Chrome 149.0.7827.54<br>Testing Devices: Descktop (1440) (Chrome DevTools), iPad mini (Chrome DevTools), iPhone SE (Chrome DevTools)

**Summary:** A review with a one-character description cannot be submitted

**Description:** 

**Pre-conditions:** 

**1** Log in to the application using:<br><br>Email: koren@gmail.com<br>Password: 1q2w3e4r

**2** Open https://relax-map-front-end.vercel.app/locations/68d568270e6bcc357e98343d

**Steps to reproduce:** 

**1** Click the "Add Review" button.

**2** Enter a single character in the review text field.

**3** Submit the review.

**Actual result:** 

**The system displays the message "Review is too short."** 

**Expected result:** 

**The system successfully submits the review when the description field contains one character, according to the requirements.** 

**Attachments:** [sk-017.png](https://drive.google.com/file/d/1sybn9ojDbUB3YY1dZ-xhcprRxV7xyWf6/view?usp=drive_link)
