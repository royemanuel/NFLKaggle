Working Kaggle Notebook
================
Roy Emanuel

Initial Data Plots of the field during a play
=============================================

The first step I took was to look at the tracking data to see if I could plot it. This was pretty straightforward.

Plot of the first play available.

![](kagglenotebook_files/figure-markdown_github/unnamed-chunk-1-1.png)

Let's look at the players involved with the football: football, Matt Ryan, Julio Jones and Malcolm Jenkins.

![](kagglenotebook_files/figure-markdown_github/unnamed-chunk-2-1.png)![](kagglenotebook_files/figure-markdown_github/unnamed-chunk-2-2.png)![](kagglenotebook_files/figure-markdown_github/unnamed-chunk-2-3.png)

NExt, I'm going to plot a vector for each point showing where the player is moving and how fast relatively.

![](kagglenotebook_files/figure-markdown_github/unnamed-chunk-3-1.png)

The above plot doesn't really show much. Of course their direction aligns with their next point in space. That doesn't do much. So let's look where everyone is facing.

The arrow vector shows the direction the player was facing during at each time step.

![](kagglenotebook_files/figure-markdown_github/unnamed-chunk-4-1.png)
