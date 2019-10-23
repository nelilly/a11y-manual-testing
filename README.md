# a11y-manual-testing
An accessibility resource for manual testing, debugging, and defect remediation. 

This README.md file contains a list of resources to set up a manual testing environment. The <a href="https://nelilly.github.io/a11y-manual-testing/">a11y-manual-testing page</a> is an HTML file that contains information and links that are useful while testing your sites and features.

> **Automated testing:** Before attempting manual testing the features should be checked using automated tools and any errors corrected.

## Windows test setup
You should install the following applications for manual testing on Windows:
- [NVDA](https://www.nvaccess.org/) for use with Firefox (default browser)
  - [Axe](https://www.deque.com/axe/) extension
  - [WAVE](https://wave.webaim.org/) extension
- [Narrator](https://support.microsoft.com/en-us/help/22798/windows-10-complete-guide-to-narrator) for use with Edge
- [ChromeVox](https://chrome.google.com/webstore/detail/chromevox-classic-extensi/kgejglhpjiefppelpmljglcjbhoiplfn?hl=en) for use with Chrome 
  - [Axe](https://www.deque.com/axe/) extension
  - [WAVE](https://wave.webaim.org/) extension
- [JAWS](http://www.freedomscientific.com/Products/software/JAWS/) for use with IE11

> It's expedient to bookmark a page with accessibility resources such as [a11y-manual-testing page](https://nelilly.github.io/a11y-manual-testing/). If using a virtual machine environment for testing I've found it handy to set all the browser's home pages to the same link.

## MacOS test setup
MacOS already comes with VoiceOver:
- [VoiceOver](https://help.apple.com/voiceover/mac/10.14/) for use with Safari
  - [a11yTools](http://pauljadam.com/extension.html) extension (Safari)

Consider adding one or more of the following extensions for use in Chrome or Firefox on Mac.
- [Axe](https://www.deque.com/axe/) extension
- [WAVE](https://wave.webaim.org/) extension