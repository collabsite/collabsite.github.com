# collabsite

collabsite is a website that **anyone can edit**. The website itself is a git repository that is hosted on GitHub pages. This means that the website has a full history log, and can be updated by many people easily. I encourage everyone to contribute, let's build something cool!

## How to Contribute

I encourage everyone to contribute! Contributing is easy and follows GitHub's normal fork-modify-pull request workflow.

1. On GitHub, fork this repository using your account.

2. Using either the git CLI or GitHub's web interface, modify your repository and commit the changes.
    * For more information on using GitHub's web interface: [Creating new files](https://github.com/blog/1327-creating-files-on-github) | [Modifying existing files](https://github.com/blog/905-edit-like-an-ace)
	* If you use the GitHub web interface for your changes, GitHub automatically commits the changes.
	
3. Once you have committed your changes, file a pull request on this repository. ([Direct link to file pull requests](https://github.com/collabsite/collabsite.github.com/pull/new/master).)
    * In your pull request, include a helpful title, and use the description to describe your changes.
	
There is a bot that scans the open pull requests, and it will automatically merge your request within 5 minutes. When your pull request is merged, GitHub Pages will update, and the changes will be viewable at [collabsite.github.com](http://collabsite.github.com).

## Permissions

If everyone was allowed to change everything, chaos would ensue. In an effort to maintain order while allowing creativity to flow, the bot has a few rules.

1. Only administrators are able to change the top-level directory and the p/ directory.
2. Users can only modify their own directory in the u/ directory.
3. Anyone can modify anything in the s/ directory.

*Please note that the u/ directory (User-Specific Space) isn't implemented yet, so the bot will reject any pull requests that attempt to modify it.*

When the bot detects a pull request violates these permissions, it will close the pull request. In instances where the bot has details on why it rejected the pull request, it will modify the pull request description to contain the cause for rejection.

## Be Social!

I hope that this project will become a community effort, and am happy to recieve any feedback or suggestions. If you have feedback or suggestions, open an issue on GitHub and I will do my best to incorporate the feedback.