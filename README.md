# Develop a Form Designer with jQuery
## Business Requirement:
You need to write a form designer, which has these features:
* Select field type and add a field
* Remove field
* Preview

### Select field type and add a field
There should have an 'Add' button on the page. When you click on it, it will pop up a dialog for choosing the field type.

![](./mockups/1.jpg)

In the 'Choose Type' dialog, there are two types of field: Text and Date. You can choose your favarite type and click 'Add' button to add it on the design form or click 'Close' to close this dialog.

![](./mockups/2.jpg)

After you add a field type, the dialog will keep opening so that you can continue to choose and add more fields to the form.

### Remove field
There should have a 'Remove' button on the right of each field. When you click it, the field will be removed from the form.

### Preview
There should have a 'Preview' button on the page. When you click it, the button caption will change to 'Edit' so we can toggle between edit mode and preview mode. In the preview mode, you can either add a new field or remove a field.

![](./mockups/3.jpg)

## Practice Challenges:
* Use basic selectors such as id and class name selector
* Use attribute selector
* Understand and use the event mechanism
* Understand and use method chaining
* Use jQuery UI dialog widget for field type selection

## Practice Requirements:
* DON'T use DOM APIs such as `document.getElementById()`
* Do tasking and break tasks in appropriate small units and commit code after completing each task
* Commit frequently with readable comment
* Coding with shortcuts

## Practice Output:
HTML and JavaScript (CSS is optional).

## Environment:
* HTML 5
* JavaScript ES6
* jQuery 3.2.1
* jQuery UI 1.12.1

## How to Begin:
Open your terminal, change into any path and clone this repository:
```
git clone repo_of_this_template
```
Install dependencies:
```
npm install
```

Open the project in your favorite editor, write JavaScript in `src/js/main.js` and HTML in `src/main.html`. Once completed, use `git` command below to set the `origin` of this repository:
```
 git remote set-url origin my_url
```
Then push your code into your own remote repository.

## Learning Resources:
1. [JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
2. [JavaScript Code Camp](https://www.freecodecamp.org/challenges/comment-your-javascript-code)
3. [JavaScript Objects](https://www.w3schools.com/js/js_objects.asp)
4. [ECMAScript 6 Features](http://es6.ruanyifeng.com/)
5. [Install Node](https://github.com/creationix/nvm)
6. [Install NPM](https://github.com/npm/npm)
8. [Git Reference](https://git-scm.com/docs)
7. [jQuery Tutorial](http://www.w3school.com.cn/jquery/)
