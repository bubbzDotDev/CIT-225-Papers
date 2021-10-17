# Week 5 Paper

By Chris Blount

10/16/2021

## Final Project Design & Development (cont.)

I had 10 tables planned but needed to think of two more. After some thought, having three separate tables for `template`, `announcement`, and `recurring` seemed inefficient. Instead, I decided to make an ENUM of `embed_type` inside the `embed` table with `template`, `announcement`, and `recurring` as its values.

I then had to think of five more tables to get to 12. I started thinking of future potential features I'd like the bot to have. So I added tables for `message`, `reaction_role`, `reaction`, and `role`. 

Then I had a talk with a friend who's working on most of the backend code for the side project and had him review my ERD so I could get help finding my 12th table. He asked if there was anything that could potentially grow that I could break out on its own. The answer there was creating a `type` table from the `ENUM` I created earlier. That way items for the `type` table can be added in the future and we're not locked in to the three I thought of for the ENUM.

My 12 tables:
1. `user`
1. `user_has_server` (linking table)
1. `server`
1. `channel`
1. `message`
1. `user_level`
1. `embed`
1. `field`
1. `reaction_role`
1. `reaction`
1. `role`
1. `type`

![Image of ERD](https://bubbzdotdev.github.io/CIT-225-Papers/images/erd_image_v3.PNG)