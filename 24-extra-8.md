# Extra Practice 8

You might have noticed that we haven't really worked with the `sleep` variable. Health tracker apps often ask you to round your estimated amount of sleep (even if they don't, we often round anyway). This has an interesting effect on our layered graphs.
Try layering a scatterplot of `sleep` over a boxplot, like we did before.
[DC]
Weird--this data set has almost 30 days' worth of data, but we only see five points on our scatterplot. Are we missing some data?
Actually, because we rounded to the nearest quarter hour, there are only a limited range of possible values for `sleep`. If we slept 8 hours on 10 different days, those points would overlap on our graph, so that we can't see all the points at once.
In order to see all the points at once, coders "jitter", or randomly move, the points on the graph. If a scatterplot was created by someone carefully placing the points where they are supposed to be, a jitterplot is what happens when we come along and shake it up.
Let's recreate our layered `sleep` graph, using 'gf_jitter()' instead of `gf_point()`.
[DC]
Another option we could use to reveal points that are hidden behind each other is to use more arguments. Remember how we used the `bins` to adjust our histograms? `bins` is only for histograms, but all graphs can be adjusted using additional arguments called **aesthetics**. `alpha` ranges from 0 to 1 and controls transparency. `size` controls the size of the points.
Try using a combination of these to improve our first scatterplot + boxplot graph. Why is this a better representation of our data?
[DC]

<iframe data-type="datacamp" id="extra-8-3" height="350" src="https://uclatall.github.io/mtucker-coding-study/data-camp/dc-extra-8-3.html"></iframe>