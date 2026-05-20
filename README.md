# CSE110 Lab 7

Names:
- Yizhen Han

## Check Your Understanding

### 1) Where would you fit your automated tests in your Recipe project development pipeline?

I would fit automated tests within a GitHub Action that runs whenever code is pushed. This helps catch bugs early and ensures that new code does not break existing features. It also improves teamwork because everyone can immediately see whether the project still passes all tests after changes are made. Automated testing in the pipeline makes development more reliable and efficient.

### 2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

No, end-to-end testing is not usually used to check whether a single function returns the correct output. End-to-end testing focuses on testing the entire user flow and how different parts of the application work together through the UI.

### 3) What is the difference between navigation and snapshot mode?

Navigation mode analyzes the webpage right after it loads and measures overall page performance. Snapshot mode analyzes the webpage in its current state and is mainly used for checking accessibility issues instead of page loading performance.

### 4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

1. Optimize and compress images to improve loading speed.
2. Improve accessibility by adding better labels and alt text for images.
3. Reduce unnecessary JavaScript and CSS files to improve overall performance.