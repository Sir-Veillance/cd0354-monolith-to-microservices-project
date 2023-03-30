Travis CI has some huge bug that I see all over their forums where many users are incapable of using it at any tier of payment.
Travis support was not particularly helpful, so I included a screenshot of my builds failing (They were successfully auto-triggered by pushes though since I hooked up my repository)
All this to say, I also included my .travis.yml file in a screenshot. I am confident it would have functioned, but
Travis has a bug with some users that I imagine requires some escalation before builds can go through.
Because of this I ended up pushing images manually to DockerHub while standing up my cluster.
