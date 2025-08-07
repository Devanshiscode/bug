# Influenzer Bugs Report

## 1. Login Error Message

- **Issue:** When entering email and password on the login page, the message "Something went wrong" is displayed.
- **Suggested Fix:** The message should be more specific (e.g., invalid email format, missing password, or incorrect credentials) to help users correct the issue.

## 2. Input Field Validation

- **Issue:** Fields like name, email, and password have no character limits.
- **Suggested Fix:** Add appropriate length restrictions to improve validation and prevent unexpected input issues.

## 3. Layout Overlap on Error

- **Issue:** When a login error occurs, the layout shifts and the "Create new account" link overlaps with the help email at the bottom.
- **Suggested Fix:** Adjust layout spacing to prevent overlap when an error message is shown.

## 4. Grammar Mistake in Tagline

- **Issue:** The tagline says “The ChatGPT of Influencer Industry.”
- **Suggested Fix:** It should say **“The ChatGPT of the Influencer Industry”** for grammatical accuracy.

## 5. E.R. Value Misalignment

- **Issue:** The "E.R." value appears misaligned or extending outside the layout.
- **Suggested Fix:** Likely a CSS issue. Ensure the content fits within the layout properly.

## 6. Image Loading Issues

- **Issue:** Some images are not loading properly.
- **Suggested Fix:** Check image paths or server response for broken or slow-loading assets.

## 7. Influencer Search

- **Issue:** Some influencers are not found even when searching with exact names or handles.
- **Suggested Fix:** Improve search algorithm or ensure the influencer data is complete and indexed.

## 8. Profile Image Load Time

- **Issue:** Profile images take longer to load, affecting user experience.
- **Suggested Fix:** Optimize image sizes and consider lazy loading with placeholders.
