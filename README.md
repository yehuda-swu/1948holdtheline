# 1948: Hold the Line

Version 7. Educational strategy game for StandWithUs UK Explore.

## What has changed

1. Added a worked example on the welcome screen and inside How to Play. The player sees how defence, threat, supply cost and the battle result relate to one another.
2. Added an original subtle suspenseful music loop. It is embedded inside `index.html`, plays continuously across the game, and has a visible mute control.
3. Added small historical national flags, including the distinctive 1948 flags of Egypt, Syria and Iraq. Flags appear on the map after the May 1948 invasion and in relevant battle reports.
4. Added buttons to access the worked example from the welcome screen and from the command panel.
5. Preserved all eight historical chapters, the battle reports, Student and Classroom modes, and the two organisation logos.

## Publishing on GitHub Pages

1. Extract this ZIP file.
2. Open your existing `yehuda-swu/1948holdtheline` repository.
3. Choose Add file, then Upload files.
4. Upload `index.html`, replacing the existing file of that name. Do not upload the HTML with a different filename.
5. Commit the change and check GitHub Actions if the site is slow to update.

Suggested commit message:

    Add worked example continuous soundtrack and 1948 flags

With Git installed locally:

    git add index.html
    git commit -m "Add worked example continuous soundtrack and 1948 flags"
    git push origin main

## Audio compatibility

Audio is requested from the welcome screen. Browsers may block audible autoplay until the user clicks or taps the page. If blocked, the music begins on the first permitted interaction. The user can mute it at any point. The music is original and generated for this game. No external audio hosting is needed.

## Historical accuracy and teaching notes

Flags identify states and are not precise army locations or troop strengths. Before the May 1948 invasion, the game does not use national army flags to represent local Palestinian Arab and volunteer forces. The military significance and extent of each state's participation varied; the Lebanon flag is not a claim that Lebanon fought on every northern front.

Defence ratings, manpower, weapons and supplies represent simplified gameplay counters. They are not actual historical inventories, casualty figures or historical outcomes. The chapter dates and events are drawn from the historical record.

References:

* US Department of State, The Arab Israeli War of 1948: https://history.state.gov/milestones/1945-1952/arab-israeli-war
* Egyptian Presidency, Egypt's flag during the monarchy: https://www.presidency.eg/en/مصر/معلومات-أساسية/العلم-الوطنى/العلم-المصرى-في-العهد-الملكى/
* Flags of the World, Syrian historical flags: https://www.crwflags.com/fotw/flags/sy-his2.html
* Hashemite flags, Kingdom of Iraq: https://hmkajo2022.dev2.dot.jo/en/node/50253
* Royal Hashemite Court, Jordanian flag: https://hmkajo2022.dev2.dot.jo/en/page/about-jordan/flag
* MDN Web Docs, media autoplay policies: https://developer.mozilla.org/en-US/docs/Web/Media/Guides/Autoplay
