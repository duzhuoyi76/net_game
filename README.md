【开发环境】PC+Ubuntu  	          	【开发工具】vscode
【运行环境】GEC6818开发板           			【开发语言】C
【项目描述】在大二下学期，为了完成大学众创实验室考核，完成了一个“网络对战游戏集”项目，该项目主要用到如下芯片： GEC6818主控板。我在项目中主要实现了如下功能：
1．开发了一款网络对战斗兽棋游戏。该游戏在PC+Ubuntu环境下进行开发，运行环境为ARM开发板+Linux操作系统。游戏基于TCP传输协议，实现了两块已联网的开发板上的同步对战，并在开发板触摸屏上实现了可视化操作。玩家可以通过点击触摸屏来操控棋子、使用功能，如重新开始、和棋、悔棋、认输等，这些操作通过网络传输在两块开发板上实现实时响应。
2．开发了一款2048小游戏。这款游戏同样在PC+Ubuntu环境下开发，运行环境为ARM开发板+Linux操作系统。游戏在触摸屏上实现了可视化，并能识别开发板触摸屏上的划动点击操作，从而实现相应的游戏功能。 
【项目难点】跨越PC+Ubuntu开发环境与ARM开发板+Linux运行环境之间的差异进行开发，同时实现基于TCP传输协议的网络对战功能。此外，项目还在开发板的触摸屏上设计出直观、易用的交互方式，并确保两块联网的开发板能够实现同步对战，要求有实时性和同步性。最后，考虑到ARM开发板的资源限制，需对代码和资源进行优化，以确保游戏能够在有限的环境下流畅运行。
