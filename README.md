XQWLight
========

About
-----

This is the XQWLight XiangQi program written by Huang Chen (Morning Yellow) and
modified by H.G. Muller to use the WinBoard protocol.

Status
------

I have made the following changes to the source as
[published](http://home.hccnet.nl/h.g.muller/XQWLight.zip) by H.G. Muller:

 - Remove all Chinese language comments since they're of no use to me.
 - Untabify.
 - Fix inconsistent indentation.
 - Remove Win32 API dependencies by creating typedefs for DWORD et al & using
   `clock()` instead of `GetTickCount()`.

License
-------

According to comments in the original source, the code is licensed under the
GPLv2, so I've included the
[full license text](https://github.com/rmoritz/XQWLight/blob/master/LICENSE) in
this repo.

Further information
-------------------

H.G. Muller has a [page](http://home.hccnet.nl/h.g.muller/XQWLight.html)
dedicated to XQWLight. Below are his original release notes:

	                       XQWLight 0.6_WB release notes
	
	
	XQWLight 0.6_WB is a version of the XQWLight 0.6 XiangQi program written
	by Huang Chen (Morning Yellow). The AI of this program was coupled to
	interface code for the WinBoard protocol by H.G. Muller, and released
	with permision of Morning Yellow on March 14, 2009, under the GPL.
	
	XQWLight 0.6 is a simple 'demo engine' for XiangQi, written in C++. Despite
	the fact that all comments are in Chinese, the variables all have English 
	names, which makes the code fairly easy to understand. XQWLight 0.6 therefore
	has a high educational value, illustrating all basic features found in Chess
	engines. It features
	
	* 16x16 Mailbox board
	* PVS search
	* Iterative deepening
	* (R=2) Null-move pruning
	* depth-preferred hash table
	* killer heuristic
	* history heuristic for move ordering in full-width search
	* MVV/LVA move ordering in QS
	* evaluation by piece-square tables only
	* repetition detection (with perpetual-check detection)
	
	Despite its simplicity, XQWLight 0.6 plays a very tough game of XiangQi,
	due to the excellent tuning of its piece-square tables.
	
	H.G. Muller
	
	LINKS
	
	http://www.elephantbase.net
