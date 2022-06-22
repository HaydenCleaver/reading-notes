# Class 13

Local storage is important to us because it allows us to retain the state of the website and its data so that it can be used later.

## Local Storage

1. Why would a developer use local storage for a web application?
* It makes reloading a page with multiple assets much faster if the data is cached on the user's computer after their first visit.  It also lets our website retain the state that it was in on the user's last visit.
2. What information should not be stored in local storage?
* User's personal data.
3. Local storage can store what type of data? How would you convert it to that type before storing?
* It can only store strings. You can use `JSON.stringify()` in combination with `localStorage.setItem()` to store a non-string.  Then use `JSON.parse()` with `localStorage.getItem()` to retrieve the info.

### Things I want to know more about

I was a little hazy on the code used in the case samples in the article; so I want to see it in action more.