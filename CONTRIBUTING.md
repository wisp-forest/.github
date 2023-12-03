## Wisp Forest Contribution Guidelines

Hi! We're excited that you want to contribute to one of our projects - but before you get started, here are a few basic guidelines to make sure your changes have the best chance of getting accepted

First of all, the best and fastest way to contact us is through the Wisp Forest Discord server over at https://wispforest.io/discord. We're always happy to discuss and, of course, help you with your problems!

### Before Contributing
- **Issues**<br>
  If you've discovered a problem and want to tell us about it - great! Just go right ahead and open an issue (although, do take a quick peek to make sure the problem isn't already known - the existing issue will often also have the solution on it!)
  
  When reporting issues on one of our mods, please **always** (and I cannot stress this enough) include your game's `latest.log` file - it has all the basic information (like game, loader and mod versions) you'd otherwise need to include manually and more. If your problem involves a crash, feel free to include the crash report as well - but the log is always the most important piece of information to give us (if you don't know where to find it, [this tutorial on the Fabric Wiki](https://fabricmc.net/wiki/player:tutorials:logs_ml:windows) will get you up to speed)

- **Pull Requests**<br>
  If you've discovered a bug and implemented a fix, go right ahead and submit that PR - we'll be more than happy to merge it. On the other hand, if you'd like to implement a new feature or expand on something which already exists, contact us beforehand (either with an issue or by talking to us directly on Discord). This way we can discuss implementation details and, perhaps more importantly, whether your proposed changes are even something we want in the project - this can save you a bunch of time implementing something we're unlikely to merge
  
  Generally, always describe which changes you made, why you made them and how you chose to implement them (if the implementation is not trivial)

### Contributing Code
When writing code for our projects, there are only a few things we ask you to do. Those are, in no particular order:
- Follow the code style conventions used in whichever project you're contributing to (this includes things like brace placement, using inferred types over explicit ones or vice-versa, naming, spaces around operators and so on)
- If the project has a test suite (or a testmod, like is the case for owo-lib) and your changes are not entirely trivial, add one or two test cases so we (and you!) can verify that your contribution works as expected
- When the project follows a certain style of authoring commit messages (eg. in owo-lib we preface commits to owo-ui with `[ui]` or ones to endec with `[endec]`) - use it for your own changes too
- If your implementation deviates from the obvious path to solve a given problem, throw in a quick comment to explain how you arrived at this solution - this helps prevent future regressions from somebody refactoring your "weird" solution to follow the more obvious approach
