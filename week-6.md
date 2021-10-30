# Week 6 Paper

By Chris Blount

10/29/2021

## Final Project Design & Development (cont.)

With the 12 tables planned, I reached out to the professor to have him review my design. He quickly found that the `user` wasn't linked to `message` or `reaction` which is crucial. 

He also found that I had many relationships with extra primary keys between tables. We removed them and ensured they were foreign keys.

When forward engineering, I ran into a few errors but nothing too terrible. After working through those errors, I was able to successfully forward engineer so I can start adding data.

![Image of ERD](https://bubbzdotdev.github.io/CIT-225-Papers/images/erd_image_v4.PNG)