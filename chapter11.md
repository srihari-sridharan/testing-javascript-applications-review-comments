# Testing JavaScript Applications

> **Note:** The below tests were executed and verified.

## Chapter 11: Writing UI-based end-to-end tests

### Listing 11. 1. package.json

No comments.

### Listing 11. 2. package.json

In the file present in `chapter11\1_writing_end_to_end_tests\2_writing_your_first_tests\package.json`, the commands below will work only for Linux.

```Terminal
  "cypress:open": "NODE_ENV=development cypress open",
  "cypress:run": "NODE_ENV=development cypress run"
```

For Windows readers should use **`set NODE_ENV=development & cypress open`** and **`set NODE_ENV=development & cypress run`**.

### Listing 11. 3. cypress.json

No comments.

### Listing 11. 4. itemSubmission.spec.js

No comments.

**NOTE:** In case of issue opening Cypress, follow the error log to see if absence of `knex` or `sqlite3` is causing the issue. If so, do a separate `npm i` for these packages.

### Listing 11. 5. itemSubmission.spec.js

No comments.

### Listing 11. 6. cypress.json

No comments.

### Listing 11. 7. knexfile.js

No comments.

### Listing 11. 8. dbConnection.js

No comments.

### Listing 11. 9. dbPlugin.js

No comments.

### Listing 11. 10. index.js

No comments.

### Listing 11. 11. itemSubmission.spec.js

No comments.

### Listing 11. 12. itemSubmission.spec.js

No comments.

### Listing 11. 13. itemSubmission.spec.js

No comments.

### Listing 11. 14. itemSubmission.spec.js

No comments.

### Listing 11. 15. commands.js

No comments.

### Listing 11. 16. commands.js

No comments.

### Listing 11. 17. itemListUpdates.spec.js

No comments.

Observed that the tests were flaky when using wait timeout limits. I presume it is working as intended.

### Listing 11. 18. itemListUpdates.spec.js

No comments.

### Listing 11. 19. itemListUpdates.spec.js

No comments.

### Listing 11. 20. itemListUpdates.spec.js

No comments.

### Listing 11. 21. itemListUpdates.spec.js

No comments.

Used `.only()`! Works as expected.

### Listing 11. 22. itemListUpdates.spec.js

No comments.

> Nice quote - Users act serially, and so does Cypress

### chapter11\2_best_practices_for_end_to_end_tests\1_page_objects

Reviewed the code and executed the tests. Working as expected.

### Listing 11. 23. inventoryManagement.js

No comments.

### Listing 11. 24. itemSubmission.spec.js

No comments.

### Note Page 36

`To see this exercise’s solution and the updated test, go to https://github.com/lucasfcosta/testing-javascript-applications and check the files within the directory named chapter8.`

Should this be **chapter11**?

### Listing 11. 25. inventoryManagement.js

No comments.

### Listing 11. 26. itemSubmission.spec.js

No comments.

### Listing 11. 27. inventoryManagement.js

No comments.

### Listing 11. 28. itemSubmission.spec.js

No comments.

### Listing 11. 29. inventoryManagement.js

No comments.

### Listing 11. 30. itemSubmission.spec.js

No comments.

### Listing 11. 31. inventoryManagement.js

No comments.

### Listing 11. 32. lateralMenuPage.js

No comments.

### Listing 11. 33. inventoryManagement.js

No comments.

### Listing 11. 34. itemSubmission.spec.js

No comments.

### Listing 11. 35. domController.js

No comments.

### Listing 11. 36. itemSubmission.spec.js

No comments.

### chapter11\2_best_practices_for_end_to_end_tests\2_application_actions

Reviewed the code and executed the tests, working as expected.

### Listing 11. 37. domController.js

No comments.

### Listing 11. 38. itemSubmission.spec.js

No comments.

### Listing 11. 39. itemListUpdates.spec.js

No comments.

### Listing 11. 40. cypress.json

No comments.

### Listing 11. 41. itemListUpdates.spec.js

No comments.

### Listing 11. 42. domController.js

No comments.

### Note on Page 60

`The client you’ll find in the chapter8 folder of this book’s GitHub repository at https://github.com/lucasfcosta/testing-javascript-applications already includes this update.` Is it chapter 11?

### Listing 11. 43. itemSubmission.spec.js

No comments.

### Listing 11. 44. itemSubmission.spec.js

No comments.

### Listing 11. 45. index.js

No comments.

### Listing 11. 46. domController.js

No comments.

### Listing 11. 47. itemSubmission.spec.js

No comments.

### Listing 11. 48. domController.js

No comments.

### Text in page 67

`If you’re updating the application from the book’s sixth chapter yourself, make sure to run npm run build again after this change.` - Is the chapter number correct? I am using the code from `client` folder in chapter11.

### index.html - page 67

No comments.

### Listing 11. 49. itemSubmission.spec.js

No comments.

### Listing 11. 50. itemSubmission.spec.js

No comments.

### Listing 11. 51. domController.js

No comments.

### Note in Page 72

It mentions chapter8 should we change it to chapter11?

### Listing 11. 52. itemSubmission.spec.js

No comments.

### Listing 11. 53. itemSubmission.spec.js

No comments.

### Listing 11. 54. cypress.json

No comments.

### Listing 11. 55. example.spec.js

No comments.

### Page 82 mentions about IE.

Should we consider IE given that MS is going to end support?

### Listing 11. 56. commands.js

No comments.

### Listing 11. 57. index.js

No comments.

### Listing 11. 58. itemList.spec.js

No comments.

### Listing 11. 59. package.json

No comments.

### Listing 11. 60. index.html

No comments.

### NOTE on Percy

I couldn't sign up for Percy to run the code and check it, that said, I have reviewed the code and the approach and understand the benefits of using it.
