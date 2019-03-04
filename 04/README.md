# Intro to Web Design &amp; Computer Principles | NYU | Spring 2019
## Assignment 4
This assignment is broken down into two parts. The first requires that the index page in the root of your i6 account contains a navigation that links to all your current projects. The second part requires that you build another web site, this time about a cause important to you.

---

### Part 1
Users who visit your home page on the i6 server should be presented with a navigation that allows them to visit all the projects you’ve created for this class thus far. Before you do this, however, you’ll need to first move `index.html` and `css` into a new folder called `assignment-1`, then move `assignment-1` into the `spring-2019/intro-to-web-design/` folder.

You’ll need to do the same for `assignment-2`. And, as a final step, create a folder called `assignment-4` that you‘ll use to place the items required in part 2 of this project, discussed below.

When you’re done, `intro-to-web-design` should contain the following four folders:

* `assignment-1`
* `assignment-2`
* `assignment-3`
* `assignment-4`

You’ll now be ready to create a new `index.html` file at the root of your i6 account (`https://i6.cims.nyu.edu/~netID`) that contains a navigation with links to all your assignments.

---

### Part 2
Choose a cause in which you have a deep interest and create a three-page web site about it. You’ll need to parse your sites content into three topics, dedicating a page to each topic. For example, if I were creating a web site about animal rights, I might create a page about speciesism, another about bodily autonomy, and a last page about animals’ ability to feel pain.

#### Setting Up Your Scaffold
1. Create a folder called `css` and place it inside `assignment-4`.
2. Create a folder called `img` and place it in `assignment-4`.
3. Move `assignment-4` into `intro-to-web-design`.

#### Rules
* All pages must link to the same base style sheet (`style.css`). Styles specific to a page must reside in a second style sheet and be included via a `link` in the `head` of your HTML pages, directly underneath `style.css`.
* All pages must contain responsive images using HTML’s `x-descriptor` and be placed inside the `img` folder.
* All pages must contain a `nav`igation.
* The first page (`index.html`) must include an embedded link to a YouTube or Vimeo video about your cause.
* Your pages must employ two typefaces from Google Fonts.
* You may not use more than two colors—excluding neutrals—in your designs.
* Your HTML must be valid according to the `w3c-validation` Atom plug-in.
* Your CSS must be valid according to the `linter-stylelint` Atom plug-in.
* Folders and files must use lowercase, combined with kebab case. For example, `do-this` or `do-this.html`. Further, no spaces in folder or file names (`not this`); no camel case (`notThis`); and, no snake case (`not_this`).

## Grading
This assignment is worth 10 points and is graded as follows:

| Item                                                    | Points |
|---------------------------------------------------------|:------:|
| *(Part 1) Successful implementation of navigation*      | `1`    |
| *(Part 2) Pages link to `style.css`*                    | `1`    |
| *(Part 2) Images use `x-descriptor`s*                   | `1`    |
| *(Part 2) All pages contain a `nav`igation*             | `1`    |
| *(Part 2) YouTube/Vimeo video embedded in `index.html`* | `1`    |
| *(Part 2) Valid HTML (excluding warnings)*              | `1`    |
| *(Part 2) Valid CSS (excluding warnings)*               | `1`    |
| *(Part 2) Two Google Fonts typefaces used*              | `1`    |
| *(Part 2) Two or fewer colors used*                     | `1`    |
| *(Part 2) Folder and file naming is correct*            | `1`    |

## Due Date
See [NYU Classes](https://newclasses.nyu.edu/).

## Submission
1. Upload all assignment-related files and folders to your i6 account. How you place your files onto the i6 server is up to you (`scp` or [FileZilla](https://github.com/code-warrior/filezilla-and-i6)), as long as this assignment works in any browser.
2. In NYU Classes’ submission text box, add the URL to your i6 account. The URL you submit should look like `https://i6.cims.nyu.edu/~netID/`, where `netID` is your NYU netID.
3. In NYU Classes’ submission text box, also add the URL to your `assignment-4` project. The URL you submit should look like `https://i6.cims.nyu.edu/~netID/spring-2019/intro-to-web-design/assignment-4`, where `netID` is your NYU netID.
3. Create a `.zip` of your `assignment-4` folder, naming it `netID--assignment-4.zip`, where `netID` is your NYU netID.
4. Upload `netID--assignment-4.zip` via NYU Classes.
