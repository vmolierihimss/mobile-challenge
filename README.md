# Example Full-Stack Challenge

We're excited that you're interested in performing the coding challenge.
The purpose of this test is to see how you approach problems as well as to evaluate the quality of your code.

## Challenge description

This challenge imagines that we have a social media platform that is under attack from spam. We have implemented a reporting system for users that lets them report spam to the platform, and our spam protection team.  

The challenge is to create a small mobile application for our spam protection team that consists of a UI in order to manage reported content.

The UI should look something like:

![Reporting listing](https://github.com/morkro/coding-challenge/blob/master/images/wireframe.png?raw=true)

We provide an example listing response ([`data/reports.json`](data/reports.json)) that you can use as the basis of your listing. Please fill the appropriate fields in the wireframe, ignore the "Details" link.

Furthermore we need a way to _block_ the content and _resolve_ those reports. Ideally this will be implemented as a local database. The two buttons in the UI should do a call to your database in order to block the content or to resolve the ticket. You are free to implement the blocking as you want. For bonus points, add a mock for a backend call.


- **`Block`:** Means that the content should no longer be available to users
- **`Resolve`:** Means that the report is considered "resolved", and it is no longer visible to the spam protection team
- **`Details`:** Functionality can be ignored.

## Instructions
- Please don't spend more than **3 hours**.
- Choose whatever frameworks you are comfortable with and that lets you achieve a solution in the given time limit. We prefer React Native as the base for the UI.
- Provide the solution source code either as zip or as a link to the code repository

## What we're looking for:
- Code quality
- Technical choices
- A runnable mobile application
