# Week 10 Paper

By Chris Blount

11/22/2021

## Final Project Design & Development (cont.)

Looking more closely at the project deliverables, I'm wondering what test case SQL script files are exactly.

I created SQL code for CRUD operations against each table. I'm going to ask for clarification at the next meeting to see what I'm missing.

I finished some mock-ups of user interface forms.

Sign in with Discord will use OAuth2 to authenticate the user, collecting their `user_id`, `user_display_name`, and what servers they have access to add bots to:
![Sign In Mockup](https://bubbzdotdev.github.io/CIT-225-Papers/images/sign_in.PNG)

The next screen will be a list of cards for each server the user has access to add/manage bots in. A green plus sign `+` will appear if the bot is not in that server and a blue info icon will appear if the bot is already in that server:
![Server List Mockup](https://bubbzdotdev.github.io/CIT-225-Papers/images/your_servers.PNG)