# linux-gaming-kb
My personal Linux Gaming Knowledge Base
- Steam
- Bottles single games
- Bottles/battle.net
- Bottles/wargaming

## WIP

general gaming info

i play on wayland now, used to be x11 long

i have intel core ultra integrated stats
always disable e cores
limit turbo for sustained performance (2.5 - 3 is sustained. a little more heat for not more performance? same performance at 2.5? leave a little headroom at 2.5)

if you x11 disable compositor by hotkey.
if you have a distro / de that disables it automatically (kde) dont trust it. it will have delay. it will fuck up during high load and alt tab. manually shut it off once and leave it off for best performance.
shameless plug: link to my compositor widget

protonge via flatpak single even updates with kde discover and other software repo managers that deal with flatpak (software center?)






wayland gaming awesome on hidpi

awesome hack crisp at half resolution / whatever you scale to
with xwaylandbridge

since proton 10
 PROTON_ENABLE_WAYLAND=1
 but then you back to real resolution. if you have the power in this game do it, it's better and native
 if not, stick to the xwayland hack and enjoy "native" crispness of text ui at whatever your scaling to



fix grey icon on grey taskbar in light mode desktop system tray

https://github.com/ValveSoftware/steam-for-linux/issues/4281
`cp /home/robert/.var/app/com.valvesoftware.Steam/.steam/steam/public/steam_tray_posix.tga /home/robert/.local/share/icons/steam_tray_mono.png`



 use flatpak auto ge for games you always want to run with newest shit. (moving target, only if games are very stable and reliable)

everything else peg to specific version

todo: what's special about 706 and ge826? seems around these versions were generational leaps that prevent older games from running on anything released after. is this intel specific?
