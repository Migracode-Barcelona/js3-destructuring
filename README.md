# Joke Fetcher App

This simple app fetches jokes from an API and displays them. Here are some ways we could improve it:

> ⚠️ **If your assignment has been given to you through GitHub Classroom, this repository *does not need to be forked*: open the created repository using CodeSpaces OR clone the created repository!**

> 💡 Inside a CodeSpace or VS Code, you can also use the shortcut: Control+Alt+N (or ⌃ Control+⌥ Option+N on macOS), or press F1 and then select/type Run Code, the code will run and the output will be shown in the Output window.

### Make sure your code respects the [code style guide](https://syllabus.codeyourfuture.io/guides/code-style-guide) ✍️

> If you are getting an error message when using `git push`, use `git push --force` instead! In general this is bad practice ⛔️ but GitHub Classroom requires it.

## Acceptance criteria

> 1. Given a Joke API
>    When the page first loads
>    Then a random joke will be displayed on the page

> 2. Given a joke has already been fetched and displayed
>    When the user clicks the "Get New Joke" button
>    Then a new random joke will be fetched and replace the existing one

> 3. Given there is a slow network
>    When the page first loads
>    Then a loading message will be displayed...

## 🐛 Debug

❗ Commit after completing each task ❗

1. Separate code into separate files - HTML, JS, CSS
2. Fix functionality for acceptance criterion 1 only

Navigator:

- Describe out loud the current behaviour in the user interface
- Describe what you should expect to see given the acceptance criterion
- Step through the code to make sense of where the bug is coming from

3. Fix functionality for acceptance criterion 2 only

Navigator:

- Describe out loud the current behaviour in the user interface
- Describe what you should expect to see given the acceptance criterion
- Step through the code to make sense of where the bug is coming from

4. Check all acceptance criteria are working ( including 3 )

## Refactor 🧹

1. Refactor `getJokes` to use async/await

## Challenge 💪

1. Try implementing a loading spinner using CSS