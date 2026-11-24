# Accessibility Conformance Starter

Use this small site for Module 5 practice if you do not want to use your capstone yet.

## Files

- `index.html`: sample page with intentional accessibility issues.
- `styles.css`: starter styles with some focus, contrast, reflow, and motion issues to audit.

## Practice goal

Audit and remediate:

- landmarks and heading structure
    Issue: The heading structure in the hero section skipped h2. 
    Fix: I switched the h3 to an h2. 
    Retest result: I checked the page outline with W3C Html validator and reran the Lighthouse to confirm that heading elements are in a sequentially descending order. 
- link and button names
    Issue: The button did not have an accessible name.
    Fix: I added a text "submit" to the button.  
    Retest result: The button has an accessible name, so the users, including screen reader users, can understand what the button is for. 
- keyboard access and visible focus
    Issue: There was no visible focus indicator when using the keyboard.
    Fix: I edited the focus outline in CSS. 
    Retest result: I tested that the interactive elements have an outline when focused. 
- zoom/reflow behavior  
    Issue: A horizontal scrollbar appeared when the page was zoomed in. 
    Fix: I added max-width where it was needed. 
    Retest result: The horizontal scrollbar no longer appears. 
- contrast
    Issue: The gray link text on the cards and the background did not have a sufficient contrast ratio.
    Fix: I changed the font color to dark gray. 
    Retest result: I re-ran the Lighthouse accessibility test and confirmed that it is no longer an issue. 
- form labels and required states
    Issue: The form did not provide visual indicator that the email field is also required, and it did not have associated labels. 
    Fix: I added a visible indicator to the Email field and associated labels. 
    Retest result:
- table caption/headers
    Issue: 
    Fix:
    Retest result:
- image alternatives
    Issue:
    Fix:
    Retest result:
- motion preference
    Issue:
    Fix:
    Retest result:

Document each issue, fix, and retest result.
