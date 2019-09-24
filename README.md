# Problem Set 1a

It's time to put your skills to the test. This problem set focuses on creating your first website from scratch using HTML.

## Getting Started

To get started, create a [GitHub](https://github.com/) repository to store your code. When you're finished, clone my skeleton to get all of the starter code and instructions. Setup a remote to push your code to your repository instead of mine.

### Setup

1. Login to your GitHub account and create a new repository named `pset-1a`.
2. In the terminal, navigate to your `APCSP` directory on the `Desktop`.
```
$ cd ~/Desktop/APCSP
```
3. Clone my skeleton repository into a directory named `pset-1a`.
```
$ git clone git@github.com:ap-principles-ucvts/pset-1a-skeleton.git pset-1a
```
4. Change into your newly created `pset-1a` directory.
```
$ cd pset-1a
```
5. Overwrite the remote, which originally points at my skeleton repository.
```
$ git remote rename origin upstream
```
6. Add a new remote that points at your `pset-1a` repository. Replace `YOUR-USERNAME` with your actual username.
```
$ git remote add origin git@github.com:YOUR-USERNAME/pset-1a.git
```
7. Open up the `index.html` file in the text editor of your choice.

Not much to see here...yet. Just the bare-bones structure of what will become your home page. You'll need to add content to it, as well as create other pages entirely.

## Requirements

Build a website about a topic of your choosing (provided it is school-appropriate). You don't need to worry about CSS or any of the styling concerns just yet. We'll get into that in the next problem set. Your website must meet the following minimum requirements, but you're always welcome to go further.

### Page Structure

Your website must be structured in accordance with the following specifications.

* All HTML files should be stored in the root directory.
* All image files should be stored in a folder called `images`.
* Your website must include at least 5 unique pages.

Each page must be structured consistently.

* A consistent header, which serves as your navigation bar, allowing users to navigate between pages.
   - Google some examples of what this might look like. Don't worry if yours doesn't look cool and fancy yet. We'll work on this when we learn more about CSS.
* A consistent footer, which includes the copyright (i.e., &copy; 2019-2020), a link to the UCVTS district page, and a link to the AIT school page.
   - The footer links do count towards the link requirement outlined below.

### Elements

Across each of your pages, your website must include the following.

* Headings
   - At least 1 unique `h1` element.
   - At least 1 unique `h2` element.
   - At least 1 more unique heading element (`h3`, `h4`, `h5` or `h6`). 
* Paragraphs
   - At least 5 `p` elements.
* Lists
   - At least 1 `ol` element.
   - At least 1 `ul` element.
* Links
   - At least 7 internal `a` elements (i.e., links that direct to other pages or sections of your website).
   - At least 7 external `a` elements (i.e., links that direct to another website that is not your own).
* Images
   - At least 7 `img` elements.
   - At least 1 of the `img` elements  must act as a link (this does not count towards the link requirement).
* Tables
   - At least one `table` element.

### Usability

It is your job to test your code. All images need to load. All links need to work. Open up the developer tools as you navigate to each of your pages. There should be no error messages showing up here. No exceptions.

## Deadline

Please read very carefully. Historically, most students lose points on problem sets for simply failing to read the instructions and requirements.

* September 25, 2019, at 11:59pm.

If you submit your problem set at midnight (i.e., September 26, 2019, at 12:00am), it is considered **late**!

### Submission Requirements

* Your code **must** be error-free. Code that fails to meet this minimum requirement will not be accepted.
* There must be **at least** 5 unique commits to your repository.
* Your code must meet each requirement outlined in the *Requirements* section.
* Your code must adhere to the course style guidelines.

Happy coding!
