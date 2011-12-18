<A name="toc1-0" title="What's This?" />
# What's This?

Ever not know what to work on?  Not anymore; this script will choose you an issue or 3 randomly that's open on one of your repositories at GitHub.

<A name="toc1-5" title="How do I use it?" />
# How do I use it?

You can get one issue...

  eastein@horus ~/dev/githubroulette :) $ ./githubroulette eastein
  https://github.com/eastein/githubroulette/issues/1  handle 404s
  eastein@horus ~/dev/githubroulette :) $ 

Or 3...

  eastein@horus ~/dev/githubroulette :) $ ./githubroulette eastein 3
  https://github.com/eastein/zmstream/issues/5  handle other connection failures
  https://github.com/eastein/psyched/issues/4   When timezone changes, times/dates don't change in GUI
  https://github.com/eastein/floyd/issues/3     work with some masks
  eastein@horus ~/dev/githubroulette :) $ 

Or if you're really lucky, you'll have fixed everything.  Either you don't understand how to use GitHub, or you're really good and fix things faster than you find problems.  Congratulations.

  eastein@horus ~/dev/githubroulette :) $ ./githubroulette eastein
  congratulations, you are free of issues. go outside.
  eastein@horus ~/dev/githubroulette :) $ 
