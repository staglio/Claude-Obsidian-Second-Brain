was playing with the lr in the course notebook

lr 1.0 -> loss goes crazy, NaN after a few steps
lr 0.0001 -> loss barely moves after 1000 steps
0.01 was fine

idea from the course forum: start big and shrink it over time = "learning rate schedule" / decay

also: when I forgot to scale the features even 0.01 blew up. scaling fixed it. so lr and feature scaling are connected!
