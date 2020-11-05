# Testing JavaScript Applications

> **Note:** The below tests were executed and verified.
> Shall we consider running `npm audit fix` across chapters?

**General observation** - For some listings I don't see listing number and it is just the filename. I am OK as long as it is intended and conscious move! In some cases I found listings to have only one line of code change. So thought of checking with you on this. :-)

> Request to run `npm audit fix` across the codebase!
> There are pointers to GitHub repository and folders in the text. Will it help readers if we exactly point out where a code listing lives in GitHub?

## Chapter 6: Testing front-end applications

### Listing 6. 1. index.html

No comments.

### Listing 6. 2. main.js

No comments.

> **Trivial suggestion!** In page 6 - the text reads as - "First, create a package.json file with `npm init -y` and then install JSDOM with `npm install jsdom`." Shall we update the command to have `--save`? While your GitHub sample has the package listed, this is for those who might create the new package as they read the book.

### Listing 6. 3. page.js

No comments.

### Listing 6. 4. example.js

No comments. Ran `node example.js.` - works as expected.

### Listing 6. 5. example.js

No comments. Ran `node example.js.` - works as expected.

### jest.config.js - page 9

No comments.

> **Update Jest Version:** Note in page 9 states that "At the time of this writing, Jest’s current version is 24.9.". At the time of this review the version is 26.6.1. Request you to update this if needed, as 2 major versions have been released. This is something that is native to JavaScript libraries and frameworks as new versions get released at rapid pace! :-)

### Listing 6. 6. main.test.js

No comments.

### Listing 6. 7. main.test.js

No comments.

> chapter6\1_introducing_jsdom\3_jest_jsdom
> `found 4146 vulnerabilities (4144 low, 2 high)` > `run npm audit fix to fix them, or npm audit for details`

### Listing 6. 8. main.js

No comments.

### Listing 6. 9. main.test.js

No comments.

### Listing 6. 10. index.html

No comments.

### Listing 6. 11. package.json

No comments. Executed `npm run build` - Works as expected.

### Listing 6. 12. inventoryController.js

No comments.

### Listing 6. 13. inventoryController.test.js

No comments.

### Listing 6. 14. index.html

No comments.

### Listing 6. 15. domController.js

No comments.

### Listing 6. 16. main.js

No comments.

### Listing 6. 17. domController.test.js

No comments.

### Listing 6. 18. domController.test.js

No comments.

### Listing 6. 19. domController.test.js

No comments.

### Listing 6. 20. index.html

No comments.

### Listing 6. 21. domController.test.js

No comments.

### Listing 6. 22. domController.js

No comments.

### Listing 6. 23. domController.test.js

No comments.

### Listing 6. 24. domController.test.js

No comments.

### Listing 6. 25. domController.test.js

No comments.

### Listing 6. 26. jest.config.js

No comments.

### Listing 6. 27. setupJestDom.js

No comments.

### Listing 6. 28. domController.test.js

No comments. `toBeInTheDocument()` - Good one!

### Listing 6. 29. domController.js

No comments.

### Listing 6. 30. domController.test.js

No comments. `toHaveStyle()` - Good one!

### Listing 6. 31. index.html

No comments.

### Listing 6. 32. domController.js

No comments.

### Listing 6. 33. index.html

No comments.

### Listing 6. 34. domController.js

**Suggestion:** Do we need a `// ...` above and below, just to indicate there is more code.

### Listing 6. 35. main.js

No comments.

### Listing 6. 36. domController.test.js

No comments.

### Listing 6. 37. main.test.js

No comments.

### Listing 6. 38. main.test.js

No comments.

### ~~Listing 6. 39. main.test.js~~ The code is present in domController.js so it should be Listing 6. 39. domController.js

No comments.

### Listing 6. 40. index.html

No comments.

### Page 42 - Change needed in file path

Should it be chapter6/3_handling_events/1_handling_raw_events ?

### Listing 6. 41. main.js

No comments.

### Listing 6. 42. main.test.js

No comments.

### Listing 6. 43. domController.js

No comments.

### Listing 6. 44. main.js

No comments.

### Listing 6. 45. main.test.js

No comments.

### Listing 6. 46. main.test.js

No comments.

### Listing 6. 47. domController.js

No comments. Executed code and relevant tests. Ensured that it is getting stored in local storage as expected.

### Listing 6. 48. main.js

No comments.

### Listing 6. 49. domController.test.js

No comments.

### Listing 6. 50. main.test.js

No comments.

### Listing 6. 51. domController.js

No comments. The reason behind the decision to clone `{ …data.inventory }` was well explained. Thanks.

### Listing 6. 52. domController.js

No comments.

### Listing 6. 53. domController.js

No comments.

### Listing 6. 54. index.html

No comments.

### Listing 6. 55. main.js

No comments. App and tests work as expected.

### Listing 6. 56. domController.test.js

No comments.

### Listing 6. 57. domController.test.js

No comments.

### Listing 6. 58. domController.test.js

No comments.

### Listing 6. 59. domController.test.js

No comments.

### Listing 6. 60. domController.test.js

No comments. Should we add numbering (❶) to this listing ?

### Listing 6. 61. testUtils.js

No comments.

### Listing 6. 62. domController.test.js

No comments.

### Listing 6. 63. main.test.js

No comments.

### Listing 6. 64. main.test.js

No comments.

### Listing 6. 65. testUtils.js

No comments.

### Listing 6. 66. domController.test.js

No comments.

### Listing 6. 67. main.test.js

No comments.

### Page 76 Note - Chapter number correction

Should it be chapter6 > 5_web_sockets_and_http_requests...? It is mentioned as chapter5. Request you to check this all across the book. I understand that as we write we move the chapters across. Just a cosmetic thing!

### Listing 6. 68. inventoryController.js

No comments.

### Listing 6. 69. setupGlobalFetch.js

No comments.

### Listing 6. 70. jest.config.js

No comments.

### Listing 6. 71. inventoryController.test.js

No comments.

### Listing 6. 72. inventoryController.test.js

No comments.

### Listing 6. 73. main.js

No comments.

### Listing 6. 74. main.test.js

No comments.

### Listing 6. 75. main.test.js

No comments.

### Section 6.5.2

The chapter number needs a correction in the text! chapter6 instead of chapter5.

> Because this is a book about tests, I’ve already implemented this functionality in the backend.
If you don’t want to implement it yourself, you can use the server which you can
find within the ~~`chapter5`~~ `chapter6` folder in this book’s GitHub repository at [https://github.com/](https://github.com/)
lucasfcosta/testing-javascript-applications.

### Listing 6. 76. socket.js

No comments.

### Listing 6. 77. main.js

No comments.

### Listing 6. 78. server.js

No comments.

### Listing 6. 79. inventoryController.js

No comments.

### Listing 6. 80. socket.js

No comments.

### Listing 6. 81. socket.js

No comments.

### Listing 6. 82. socket.test.js

No comments.

### Listing 6. 83. testSocketServer.js

No comments.

### Listing 6. 84. testSocketServer.js

No comments.

### Listing 6. 85. testSocketServer.js

No comments.

### Listing 6. 86. inventoryController.test.js

No comments.
