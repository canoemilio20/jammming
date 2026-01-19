# jammming
Codecademy Full-Stack Career Path project: Jammming

---

## Planning
Project objective: a React web app that connects to Spotify's API to interact with its music library.

Requisites:
- It has to be a React web app.
- Implement Git/GitHub version control.
- Use a company's API to implement functionality.
- Deploy the app.
- Create a README.md file that contains the purpose, technologies used, features and future work for this project.

---

## Scope

### Purpose
Due to Spotify's API being currently unavailable, I will develop a Gmail spam email check tool that allows a user to check and decide what to do with spam emails.

### Tech stack
- HTML
- CSS
- JavaScript
- React
- NextJS
- GitHub
- GitHub pages
- Google Cloud's Gmail API

### Features
- Authentication: log into your Gmail account for authentication, in order to use the rest of this web app's features.
- Spam emails display: cycle through your spam emails and read them in order to decide either to skip, delete or tag them.
    - Skip: this does nothing to the emails, you'll see them again as you cycle through.
    - Delete: mark a specific email for deletion, you can unmark them if you need to.
    - Tag: mark a specific email for review, you can unmark them if you need to. This is intended for you to not loose track of those you want to skip and those you haven't decided what to do with.
- Decision lists: as you skip or mark spam emails, you'll see lists emerge that keep track of those emails that have skipped or been marked either for deletion or tagged. If the lists are empty, they aren't visible.
- Confirm your choices: cycle through the spam emails that have been skipped, marked for deletion, tagged or all of them together, before confirming your choices and deleting those that have been marked for that.

### Future work
Were this project to be continued later, additional features could include:
- Search bar: a search bar to filter emails and look for a specific one.
- Email tag switch: implement the same functionality for the other email tags (inbox, trash) and maybe even extend the functionality according to each email tag.