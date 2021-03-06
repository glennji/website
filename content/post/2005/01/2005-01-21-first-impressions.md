---
title: First Impressions
author: glennji
type: post
date: 2005-01-21T04:15:53+00:00
#url: /?p=16732
featured_image: /wp-content/uploads/2018/01/57981160_6458b4b9df_b.jpg
categories:
  - Technology
tags:
  - chronofiles
  - Linux

---
Finally took the plunge &#8212; I&#8217;ve blown away my SUSE install and put <a href="https://web.archive.org/web/20050213162057/http://www.yoper.com/">Yoper</a> on in it&#8217;s place! &#8220;How excitement!&#8221;

The installer was interesting, in a good way &#8212; no packages to select (or dselect, for those of a <a href="https://web.archive.org/web/20050213162057/http://www.debian.org/">Debian</a> persuasion), not even any updates whilst the packages were being installed, just a simple black screen with the golden advice, &#8220;Please be patient&#8221;. It surprised me, but was at the same time refreshing. (I always end up installing anything and everything that looks vaguely interesting anyway, at least on the first install. And to this day I don&#8217;t think I&#8217;ve ever used <code>'lsof'</code> to list my open files &#8230; install it every time, however, just in case.)

Some of the dialogs had some interesting wording, too &#8212; perhaps a translation effect?

The graphical disk partitioner was pretty good, but it was weird going from a console to a VESA console, to ncurses, to the framebuffer disk partitioner, back to <a href="https://web.archive.org/web/20050213162057/http://invisible-island.net/ncurses/">ncurses</a> and finally back to the console. I was also confused when it came to assigning partitions and disks to appropriate mount points &#8212; I was offered a separate /home, but no /boot (so now I&#8217;ve got a 100Mb ext2 partition inside the first 1024 cylinder, if anyone wants to lease it out &#8212; a legacy of the &#8220;good&#8221; old days when the BIOS couldn&#8217;t jump beyond 1024 for it&#8217;s initial OS boot, and whilst 100Mb is probably more than just a little overkill, I harbour dreams of kernel hacking and ultimately want at least 15 different kernels at any one time.)

The GUI is KDE on XFree86 4.3, which isn&#8217;t exactly inline with my particular ideals &#8212; I&#8217;m a Gnome man, and have been from day 1 (day 1 for me was Gnome 2.2, I believe, on Redhat Linux 5.2 &#8212; ah yes, those were the days! When men were men and the command line was something to be revered as much as feared). On the other hand, that&#8217;s one of the major reasons I&#8217;m trying Yoper &#8212; to improve the Gnome support. I&#8217;m a gnome-utils maintainer, even if I&#8217;ve done very little but triage some bugs (mostly duplicates); as I said I&#8217;ve been using Gnome forever. I&#8217;m also a coder, Java and some .NET now with work, so I really should be able to help make Yoper Gnome one of the best Gnome distros. I use Garnome, I&#8217;m subscribed to gnome-love (and other lists), and I&#8217;ve got a shiny, shiny head (okay, not at the moment &#8212; hair grows). Besides, who wants to contribute to a well-established and stable project? (Where is the glory? Where are the ladies?) If hackers-to-be were to eschew personally glory, why, we&#8217;d all be <a href="https://web.archive.org/web/20050213162057/http://two-wugs.net/emacs/mode-tutorial.html">writing niche (but cool!) emacs modes</a>.

Anyway, my first impression of Yoper is that it&#8217;s a cool, if young, distribution/project just ripe for participation. If anyone is out there, looking for something to sink their teeth into, I&#8217;d say take the plunge and try Yoper.

(Kendrick, if you&#8217;re out there, that means you. Start hacking, boyo.)
