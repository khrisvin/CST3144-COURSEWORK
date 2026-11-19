# CST3144 Coursework: After-School Lesson Shop

[Open the live lesson shop](https://khrisvin.github.io/CST3144-COURSEWORK/)

Students can browse 10 after-school lessons, sort them by subject, location, price or available spaces, and add lessons to a cart. At checkout, the backend saves the order in MongoDB and updates the remaining spaces.

## Project links

- [Frontend source code](https://github.com/khrisvin/CST3144-COURSEWORK)
- [Backend source code](https://github.com/khrisvin/CST3144-backend)
- [Live lessons API (JSON)](https://m01003462-after-school.onrender.com/lessons)

## How it works

The Vue frontend is hosted on GitHub Pages. It uses fetch to communicate with the Node.js and Express API hosted on Render. The API reads lessons from MongoDB Atlas and saves orders there.
