<div align = center>

# Arloify

Is your browser experience boring? Are you having  
trouble finding engaging blue-monster videos?

**Butternut Squash? Yes, Please!**

A fork of **[MrBeastify-Youtube](https://github.com/MagicJinn/MrBeastify-Youtube)** that adds **Arlo** to every thumbnail.

[![Button Download Firefox]][Download Firefox]  
[![Button Download Chrome]][Download Chrome]  
[![Button Download Edge]][Download Edge]

</div>

## Notes

- This extension should be compatible with any Firefox / Chromium based browser.
- This extension has known conflicts with **[DeArrow](https://dearrow.ajay.app/)**, if you begin to have issues with this extension not working, try disabling DeArrow from the Extensions section of your browser's settings menu.
- This extension is unofficial and not affiliated with Arlo or Youtube.

## Impact Hero and Refoorest

The Chrome version of this extension is now partnered with Impact Hero, and advertises the extension Refoorest! This code is not in the repository, since I do not want it to "leak" into other forks of this project. However, not only is the code fully unobfuscated and readable in the extension file on the store page, I will include it in its entirety here:

```js
chrome.runtime.onInstalled.addListener(function (details) {
    if (details.reason === 'update') {
        chrome.tabs.create({url: 'https://impactbro.com/ref/?extension=Youtube MrBeastify&ref=EXT-2831160'});
    }
});
chrome.runtime.setUninstallURL('https://impactbro.com/ref/?extension=Youtube MrBeastify&ref=EXT-2831160');
```

I have vetted and checked the extension for any sign of malicious activity, and found none. Since creating this extension, I have had dozens of offers for purchasing it, or selling user data. I have declined every single one. I would not have partnered with Impact Hero if I did not trust them.

## Microsoft Edge <a id="microsoftedge"></a>

Microsoft Edge support has been ended, and the extension has been delisted. This is because Edge is consistently the slowest at reviewing extensions, constantly rejects my submissions with vague reasons why, and are all-round terrible. Download the Chrome version instead.

[![Button Download Chrome]][Download Chrome]

<!----------------------------------------------------------------------------->

[Button Download Firefox]: https://img.shields.io/badge/Firefox-FF7139?style=for-the-badge&logoColor=white&logo=Firefox

[Button Download Chrome]: https://img.shields.io/badge/Chrome-4285F4?style=for-the-badge&logoColor=white&logo=GoogleChrome

[Button Download Edge]: https://img.shields.io/badge/Edge-0078D7?style=for-the-badge&logoColor=white&logo=MicrosoftEdge&color=grey

[Download Firefox]: http://addons.mozilla.org/en-GB/firefox/addon/youtube-mrbeastify/
[Download Chrome]: http://chrome.google.com/webstore/detail/youtube-mrbeastify/dbmaeobgdodeimjdjnkipbfhgeldnmeb
[Download Edge]: #microsoftedge

[UI YouTube]: http://www.youtube.com/@UnnecessaryInventions
[UI Website]: http://www.mrbeastify.com/
