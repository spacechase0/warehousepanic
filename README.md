> [!NOTE]
> Much of this readme has been taken from the now-defunct `warehousepanic.com`, though with some additional details added from memory.

# Warehouse Panic

Warehouse Panic is an arcade-style time management puzzle game made for the GP2x and Wiz hand-held consoles. It is a game that challenges your attention span between key points as you sort the hordes of oncoming crates.

The game takes place inside a warehouse. Here, crates are delivered from shipping trucks to be sorted. You are working in this warehouse and your task is to guide all crates to their correct destination based on their color. You can do this by controlling the conveyor belt switches to change the path of the crates to guide them toward the correct gates. When you have sorted all crates, you will advance to the next level. If you send crates to the wrong gates, you will get a penalty. If you botch up and get five penalties, you will get fired and have to start over.
Points are awarded for the distance a crate has to travel, so it is important that you concentrate on those crates who have traveled the greatest distance.
Features
* Addictive gameplay
* Easy and intuitive interface using touch screen and stylus
* Supports GP2x F100 joystick play
* Isometric graphics
* Highscore list (with your mom on it)
* Built in keyboard
* Volume control

<img width="320" height="240" alt="warehouse_panic_1" src="https://github.com/user-attachments/assets/f548611f-4eee-421d-b91d-d17bdc747390" />
<img width="320" height="240" alt="warehouse_panic_2" src="https://github.com/user-attachments/assets/4e4063ac-d5ae-4db8-861a-c71be9389f49" />
<img width="320" height="240" alt="warehouse_panic_3" src="https://github.com/user-attachments/assets/a88dd8bc-29f1-4f41-a97e-fb16f6f3ff73" />
<img width="320" height="240" alt="warehouse_panic_4" src="https://github.com/user-attachments/assets/851ee6bf-7de2-4e7a-b2ac-d8b423a209e3" />

## Download
* [Windows](https://spacechase0.com/games/warehouse-panic)
* [GP2x Wiz](https://dl.openhandhelds.org/cgi-bin/wiz.cgi?0,0,0,0,25,403)
* [GP2x F100 and F200](http://dl.openhandhelds.org/cgi-bin/gp2x.cgi?0,0,0,0,25,2853)
* [Caanoo](http://dl.openhandhelds.org/cgi-bin/caanoo.cgi?0,0,0,0,25,492)
* [Dingoo](http://dl.openhandhelds.org/cgi-bin/dingoo.cgi?0,0,0,0,25,423)

## History and Credits

Originally made for the Pandora Angst Coding Competition in 2010. We collaborated on making this game on Game Design Novice (at `cpp.wikicomplete.info`), which has since been lost to the sands of time.
While it seems thread we made for the project itself wasn't archived, our thread on the competition itself can be found [here](https://web.archive.org/web/20101006023029/http://cpp.wikicomplete.info/forum/t-4938/coding-competition).

Most (all?) of the graphical assets were made by `clankercrusher`, but were committed by other authors back then.

## Development

We originally made this using C++, with GCC and Code::Blocks. The initial prototype was made with SFML on Windows, but later ported to SDL so it could run on the main target platforms (including a makefile later on).

You can find the initial SFML -> SDL transition in commit `db30d5d6a9db5eb58b17bd7d115454f9694cc6c8`.

Some of the later commits might not have ever been committed - mainly some of the ports, but also including joystick support.

## Links
> [!NOTE]
> Most of these links are now dead, and don't have an archived version either. They are still listed here (but not as clickable links) because they were on the original `warehousepanic.com`.

### Competition
Warehouse Panic was entered into the Pandora Angst Coding Competition (PACC 2010). More info can be read on the relative pages.
* \[DEAD\] Call for games in GP32x community (`http://www.gp32x.com/board/index.php?/topic/51639-gp32gp2xwizdingoo-coding-competition/`)
* \[DEAD\] PACC entries and result page (`http://pacc2010.xiik.net/`)
* \[DEAD\] Coverage on openxile (`http://openxile.co.uk/2010/02/08/the-pandora-angst-coding-competition/`)
* [Coverage on Pandora Press](https://web.archive.org/web/20101221160108/http://pandorapress.net/2010/02/08/the-2010-pandora-angst-coding-competition/)
* [Results discussion on Dingoonity](https://web.archive.org/web/20131130003030/http://boards.dingoonity.org/dingoonity-news/pandora-angst-coding-competition-results/)

### Reviews and Other Appearances
* [Release 1.0 on GP32x.com](https://web.archive.org/web/20120105023039/http://www.gp32x.com/board/index.php?/topic/53479-warehouse-panic/)
* \[DEAD\] Release 1.0 on gp2x.de (`http://forum.gp2x.de/viewtopic.php?f=38&amp;t=9656`)
* \[DEAD\] Feedback from judge (Orion4874) (`http://www.gp32x.com/board/index.php?/topic/51639-gp32gp2xwizdingoo-coding-competition/page__view__findpost__p__860310`)
* \[DEAD\] Mentioned regarding upcoming GP2x Caanoo (`http://www.gp32x.com/board/index.php?/topic/53776-caanoo-the-new-gph-console/page__view__findpost__p__861548`)
* \[DEAD\] Mentioned regarding upcoming GP2x Caanoo (`http://www.gp32x.com/board/index.php?/topic/53776-caanoo-the-new-gph-console/page__view__findpost__p__866239`)
* [Recommended along side such great titles as Drillwiz Xtreme and Giana's Return](https://web.archive.org/web/20230928111449/https://www.elotrolado.net/hilo_recomendaciones-de-juegos-para-la-wiz_1469702#p1721257073)
