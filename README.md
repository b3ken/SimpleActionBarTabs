I wrote a tutorial to accompany this project. [Check it out!](http://www.recursiverobot.com/post/44510940744/creating-tabs-in-the-actionbar-in-android)

This project uses [ActionBarSherlock](http://actionbarsherlock.com/) for ActionBar compatibility. All this project does is creates an ActionBar, adds tabs to it, and implements a tab listener. As a note, tab scrolling works on ICS, or if the tabs fit into the ActionBar. On phones below (Honeycomb?) if the tabs appear in a separate row, they will not be scrollable. It is apparently a limitation of ActionBarSherlock 3.x, and as I wanted to demo doing this within the ActionBar, it seemed pointless to write a work-around using ViewPagers. I might look into doing that as another demo.

By <a href="plus.google.com/u/0/110693175237378228684?rel=author">E John Feig</a>
