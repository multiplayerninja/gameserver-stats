gameserver-stats
===================

Generate and host Linux gameserver stats.

**What does it do?**
   - Automated game statistics generation into HTML/PNG
      - Requires qstat (quakestat), html2ps, imagemagick convert
   - Copy/refresh statistics with index pages
 
**Games Supported**

   - Urban Terror 4.2.023
      * http://urbanterror.info
      * https://en.wikipedia.org/wiki/Urban_Terror
      * http://hobo.house/2015/10/03/play-urban-terror/

   - Enemy Territory 2.60b
      * http://www.splashdamage.com/content/wolfenstein-enemy-territory-barracks
      * https://en.wikipedia.org/wiki/Wolfenstein:_Enemy_Territory
      * http://hobo.house/2015/09/30/play-enemy-territory/

   - Enemy Territory:Legacy 2.74
      * http://www.etlegacy.com
      * https://github.com/etlegacy/etlegacy

**Contents**

   - $game/qstat-$game.sh
      - Parses game statistics and generates HTML and PNG output
      - Examples:
         - http://funcamp.net/w/ut.html 
         - http://funcamp.net/w/ut.png
         - http://funcamp.net/w/et.html
         - http://funcamp.net/w/et.html

```
├── enemyterritory
│   ├── qstat-enemyterritory.sh
├── enemyterritory-legacy
│   ├── qstat-enemyterritory-legacy.sh
└── urbanterror
    ├── qstat-urbanterror.sh
```
