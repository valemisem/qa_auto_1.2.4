# Description of what happened in the code after using each of these 3 parameters and log files for all these actions

## - <em>first parameter</em>

## If we reset using the second commit id, the third action (adding the third .md file) will be undone. 
<p><strong> LOGS: </strong></p>
hp@DESKTOP-3H44GF4 MINGW64 ~/AQA/Homework1/qa_auto_1.2.4 (main)
$ git log
commit b74994df5092aa9a81c9052ef3d73887ba699cf5 (HEAD -> main)
Author: valemisem <valentina.misem@gmail.com>
Date:   Mon Oct 16 20:14:10 2023 +0200

    added second.md

commit aa10a541094c31f9c43831aa1275beb91bcd3ee5
Author: valemisem <valentina.misem@gmail.com>
Date:   Mon Oct 16 20:13:15 2023 +0200

    added first.md

commit 26b2d85e07d4806af118739beeadfd5e23ba7caa
Author: Oksana M <36515885+Melnioks@users.noreply.github.com>
Date:   Mon Oct 9 09:50:24 2023 +0200

    Update your-task-here.md

commit 93e058d3321dba27a85c21668c2d16de96eb05fe 


## If we reset using the third commit id, we will change back the HEAD to the third commit
<p><strong> LOGS: </strong></p>
hp@DESKTOP-3H44GF4 MINGW64 ~/AQA/Homework1/qa_auto_1.2.4 (main)
$ git log
commit 5a8e1396adb30c4cf231526cfc3bf8ad98bfba4e (HEAD -> main, origin/main, origin/HEAD)
Author: valemisem <valentina.misem@gmail.com>
Date:   Mon Oct 16 20:14:35 2023 +0200

    added third.md

commit b74994df5092aa9a81c9052ef3d73887ba699cf5
Author: valemisem <valentina.misem@gmail.com>
Date:   Mon Oct 16 20:14:10 2023 +0200

    added second.md

commit aa10a541094c31f9c43831aa1275beb91bcd3ee5
Author: valemisem <valentina.misem@gmail.com>
Date:   Mon Oct 16 20:13:15 2023 +0200

    added first.md

commit 26b2d85e07d4806af118739beeadfd5e23ba7caa

## - <em>second parameter</em>

## If we reset using the first commit id, the second and the third action (adding the second and the third .md file) will be undone. 
<p><strong> LOGS: </strong></p>
hp@DESKTOP-3H44GF4 MINGW64 ~/AQA/Homework1/qa_auto_1.2.4 (main)
$ git log
commit aa10a541094c31f9c43831aa1275beb91bcd3ee5 (HEAD -> main)
Author: valemisem <valentina.misem@gmail.com>
Date:   Mon Oct 16 20:13:15 2023 +0200

    added first.md

commit 26b2d85e07d4806af118739beeadfd5e23ba7caa
Author: Oksana M <36515885+Melnioks@users.noreply.github.com>
Date:   Mon Oct 9 09:50:24 2023 +0200

    Update your-task-here.md

commit 93e058d3321dba27a85c21668c2d16de96eb05fe
Author: ommelnikova <115581444+ommelnikova@users.noreply.github.com>
Date:   Thu Oct 20 08:42:47 2022 +0200

    Update your-task-here.md

commit 685ce8d7bbcb6780cc0fcde65ea418bf9c880682
Author: ommelnikova <115581444+ommelnikova@users.noreply.github.com>
Date:   Fri Oct 14 19:37:47 2022 +0200

    Update README.md

commit 047c4668909c27e1be9fe0abb34fcf6370cd366b
Author: ommelnikova <115581444+ommelnikova@users.noreply.github.com>

## If we reset using the second commit id, we will change back the HEAD to the second commit
<p><strong> LOGS: </strong></p>
hp@DESKTOP-3H44GF4 MINGW64 ~/AQA/Homework1/qa_auto_1.2.4 (main)
$ git log
commit b74994df5092aa9a81c9052ef3d73887ba699cf5 (HEAD -> main)
Author: valemisem <valentina.misem@gmail.com>
Date:   Mon Oct 16 20:14:10 2023 +0200

    added second.md

commit aa10a541094c31f9c43831aa1275beb91bcd3ee5
Author: valemisem <valentina.misem@gmail.com>
Date:   Mon Oct 16 20:13:15 2023 +0200

    added first.md

commit 26b2d85e07d4806af118739beeadfd5e23ba7caa
Author: Oksana M <36515885+Melnioks@users.noreply.github.com>
Date:   Mon Oct 9 09:50:24 2023 +0200

    Update your-task-here.md

commit 93e058d3321dba27a85c21668c2d16de96eb05fe 

## - <em>third parameter</em>

## If we reset using the first commit id, the second and the third action (adding the second and the third .md file) will be undone.
<p><strong> LOGS: </strong></p>
hp@DESKTOP-3H44GF4 MINGW64 ~/AQA/Homework1/qa_auto_1.2.4 (main)
$ git log
commit aa10a541094c31f9c43831aa1275beb91bcd3ee5 (HEAD -> main)
Author: valemisem <valentina.misem@gmail.com>
Date:   Mon Oct 16 20:13:15 2023 +0200

    added first.md

commit 26b2d85e07d4806af118739beeadfd5e23ba7caa
Author: Oksana M <36515885+Melnioks@users.noreply.github.com>
Date:   Mon Oct 9 09:50:24 2023 +0200

    Update your-task-here.md

commit 93e058d3321dba27a85c21668c2d16de96eb05fe
Author: ommelnikova <115581444+ommelnikova@users.noreply.github.com>
Date:   Thu Oct 20 08:42:47 2022 +0200

    Update your-task-here.md

commit 685ce8d7bbcb6780cc0fcde65ea418bf9c880682
Author: ommelnikova <115581444+ommelnikova@users.noreply.github.com>
Date:   Fri Oct 14 19:37:47 2022 +0200

    Update README.md

commit 047c4668909c27e1be9fe0abb34fcf6370cd366b
Author: ommelnikova <115581444+ommelnikova@users.noreply.github.com>

## If we reset using the third commit id, we will change back the HEAD to the third commit
<p><strong> LOGS: </strong></p>
hp@DESKTOP-3H44GF4 MINGW64 ~/AQA/Homework1/qa_auto_1.2.4 (main)
$ git log
commit 5a8e1396adb30c4cf231526cfc3bf8ad98bfba4e (HEAD -> main, origin/main, origin/HEAD)
Author: valemisem <valentina.misem@gmail.com>
Date:   Mon Oct 16 20:14:35 2023 +0200

    added third.md

commit b74994df5092aa9a81c9052ef3d73887ba699cf5
Author: valemisem <valentina.misem@gmail.com>
Date:   Mon Oct 16 20:14:10 2023 +0200

    added second.md

commit aa10a541094c31f9c43831aa1275beb91bcd3ee5
Author: valemisem <valentina.misem@gmail.com>
Date:   Mon Oct 16 20:13:15 2023 +0200

    added first.md

commit 26b2d85e07d4806af118739beeadfd5e23ba7caa
