# Testing JavaScript Applications

> **Note:** The below files were reviewed for correctness and tests were executed and verified. Readers are requested to change the file path in the codebase to match their respective platform - e.g. Windows/Linux/Mac. I changed the file path for log files wherever required and committed the changes to [my fork](https://github.com/srihari-sridharan/testing-javascript-applications). May be users running this on Windows will find this useful.

While reviewing chapters 2, 3 and 4 I observed that the `name` in `package.json` and `package-lock.json` was getting updated.

## Chapter 4: Testing back-end applications

### Listing 4. 1. server.js

No comments.

### Listing 4. 2. server.test.js

No comments.

### Listing 4. 3. server.js

No comments.

### Listing 4. 4. server.test.js

No comments.

### Listing 4. 5. inventoryController.js

No comments.

### Listing 4. 6. cartController.js

No comments.

### Listing 4. 8. server.test.js

No comments.

### Listing 4. 9. cartController.test.js

No comments.

### Listing 4. 10. logger.js

Please add a note for Windows users, a generic note to change file path wherever needed. e.g 'logs.out'

### Listing 4. 11. cartController.js

No comments.

### Listing 4. 12. cartController.js

No comments. (File path for Windows users 'tmp\logs.out')

### Listing 4. 13. cartController.js

No comments.

### Listing 4. 14. cartController.js

No comments.

### Listing 4. 15. cartController.test.js

No comments.

Note: Super test is a good choice for testing HTTP endpoints. I have used it in the past and found it robust and handy!

### Listing 4. 16. server.test.js

No comments.

### Listing 4. 17. server.test.js

No comments.

### Listing 4. 18. server.test.js

No comments.

### Listing 4. 19. server.js

No comments.

### Listing 4. 20. server.js

No comments.

### Listing 4. 21. server.test.js

No comments.

### Listing 4. 22. server.js

No comments. ("crypto" usage - neat and clean!)

### Listing 4. 23. server.js

No comments.

### Listing 4. 24. server.test.js

No comments.

### Listing 4. 25. authenticationController.test.js

No comments. Many times developers forget transitive guarantee and keep retesting stuff! Thanks for getting this mentioned.

### Listing 4. 26. authenticationController.js

No comments.

### Listing 4. 27. authenticationController.test.js

No comments.

### Listing 4. 28. authenticationController.js

No comments.

### Listing 4. 29. authenticationController.test.js

No comments.

### Listing 4. 30. server.js

No comments. Clean usage of middleware!

### Listing 4. 31. server.test.js

No comments.

### Listing 4. 32. server.test.js

No comments. Good that the author left certain parts as things to be tried by readers. Doing the changes help understand the subject better!

### Listing 4. 33. knexfile.js

No comments. Quick question on `chapter4\3_dealing_with_external_dependencies\1_database_integrations\package.json`. Any reason why the package.json has the entry for `sqlite3` as `"sqlite3": "file:node_modules/sqlite3"`? I had to remove this entry to install the npm packages for sqlite3.

### Listing 4. 34. dbConnection.js

No comments.

### 20200325082401_initial_schema.js or (datetimestamp_initial_schema.js - based on when it was run)

No comments.

### authenticationController.js - page 48

No comments.

### authenticationController.test.js - page 49 - 50

No comments.

### authenticationController.test.js - page 51

No comments.

### knexfile.js - page 52

No comments.

### dbConnection.js - page 53

No comments.

### knexfile.js - page 53

No comments.

### dbConnection.js - page 54

No comments.

### example.js - page 55

No comments. :-)

### dbConnection.js - page 55

No comments.

Cool to see the approach using `process.env.NODE_ENV`. Good one.

### jest.config.js - page 56

No comments.

### migrateDatabases.js - page 57

No comments.

### jest.config.js - page 57 and 58

No comments.

### truncateTables.js - page 58

No comments.

### jest.config.js - page 59

No comments.

### seedUser.js - page 59 and 60

No comments.

### disconnectFromDb.js - page 61

No comments.

### jest.config.js - page 61 and 62

No comments.

### Listing 4. 35. server.js

No comments.

### Listing 4. 36. server.test.js

No comments.

### Listing 4. 37. server.js

No comments.

### Listing 4. 38. server.test.js

No comments.

### Listing 4. 39. server.test.js

No comments.

### Listing 4. 40. server.test.js

No comments.

### Listing 4. 41. server.test.js

No comments.

### Listing 4. 42. server.test.js

No comments.

`jest-when` - nice and handy! Good one.

### Listing 4. 43. server.test.js

No comments.

`nock` - Good one!

### Listing 4. 44. server.test.js

No comments.
