# Intro to Web Design &amp; Computer Principles | NYU | Spring 2019
## Assignment 9 (JavaScript)
For this final assignment, you will need to create a single-page web site about an artist, musician, or other creative you find interesting. You’re welcome to take as many design freedoms as like.

What separates this project from all your previous assignments is that you’ll need to implement a level of interaction only available through JavaScript and jQuery.

---

## Rules
1. The scaffold for this assignment must be exactly like that of assignment 8.
2. Use version `3.4.0` of jQuery and include it in your assignment via [jQuery’s CDN](https://code.jquery.com/). **Do not download jQuery locally.** Also, it must be the _minified_, or compressed, version.
3. Load the jQuery library _before_ loading your own JavaScript, and do so with the location of the `script` element as the last direct child of `body`.
4. Today’s date, must be rendered on your web site via JavaScript’s `Date` object. The DOM element inside which the date will be rendered must be referenced using core JavaScript, not jQuery, and must be empty. For example, `<span></span>`.
5. The current year must be rendered alongside the text “Copyright” in the footer of your page using JavaScript’s `Date` object. For example, Copyright 2019. This must also be done via core JavaScript and written into an empty element.
6. Using core JavaScript, create an effect on the page by binding any of [these event listeners](https://developer.mozilla.org/en-US/docs/Web/Events) to a DOM element via `addEventListener`.
7. Using jQuery this time, create another effect on the page that alters the content of any element using any of [these events](https://api.jquery.com/category/events/).

**Note**: Do not use `var` to initialize variables.

---

## Grading
This assignment is worth 10 points and is graded as follows:

| Item                                                   | Points |
|--------------------------------------------------------|:------:|
| *Version `3.4.0` of jQuery used*                       | `1`    |
| *jQuery loaded before user’s `app.js`*                 | `1`    |
| *Today’s date rendered using core JavaScript*          | `2`    |
| *The current year rendered using core JavaScript*      | `2`    |
| *An interaction is created using `addEventListener`*   | `2`    |
| *A second interaction is created using a jQuery event* | `2`    |

---

## Due Date
See [NYU Classes](https://newclasses.nyu.edu/).

---

## Submission
1. Upload `assignment-9` to `spring-2019/intro-to-web-design` in your i6 account.
2. In the top-level navigation of your home page on i6, add a link to your `assignment-9` folder.
3. In NYU Classes’ submission text box, add the URL to your i6 account. The URL you submit should look like `https://i6.cims.nyu.edu/~netID/`, where `netID` is your NYU netID. **Ensure the link works _before_ you submit.**
4. Create a `.zip` of your `assignment-9` folder, naming it `netID--assignment-9.zip`, where `netID` is your NYU netID.
5. Submit `netID--assignment-9.zip` via NYU Classes.

**NOTE**: You’re graded on the submission of your ZIP file, not your site.
