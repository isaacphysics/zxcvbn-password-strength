```
_________________________________________________/\/\___________________
_/\/\/\/\/\__/\/\__/\/\____/\/\/\/\__/\/\__/\/\__/\/\________/\/\/\/\___
_____/\/\______/\/\/\____/\/\________/\/\__/\/\__/\/\/\/\____/\/\__/\/\_
___/\/\________/\/\/\____/\/\__________/\/\/\____/\/\__/\/\__/\/\__/\/\_
_/\/\/\/\/\__/\/\__/\/\____/\/\/\/\______/\______/\/\/\/\____/\/\__/\/\_
________________________________________________________________________
```

`zxcvbn` is a password strength estimator inspired by password crackers, [developed by Dropbox](https://github.com/dropbox/zxcvbn).

This fork is for use by [Isaac Computer Science](https://isaaccomputerscience.org/) and [Isaac Physics](https://isaacphysics.org/). 
It makes some modifications to the library; it [uses a different password corpus](https://www.ncsc.gov.uk/blog-post/passwords-passwords-everywhere), and makes some decisions about library size and obfuscation that may not suit other use-cases. 

You probably want to [use the original Dropbox version](https://github.com/dropbox/zxcvbn) in your own code.
