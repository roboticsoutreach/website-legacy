---
title: 'SourceBots 2018'
published: false
date: '25-04-2018 15:40'
publish_date: '18-09-2019 15:40'
metadata:
    author: 'Dan Trickey'
---

<p>{{&lt; figure src=&ldquo;/img/posts/sb2018/sblogo.svg&rdquo; width=&ldquo;50%&rdquo; caption=&ldquo;SourceBots Logo&rdquo;&gt;}}</p>
<p>Many months of hard work came to fruition last weekend, as we hosted the <a href="https://sourcebots.org">SourceBots</a> 2018 robotics competition at The University of Southampton.</p>
<p>Eight teams of sixth form students from surrounding colleges gathered at The Cube to compete their robot designs against each other. One way that I often like to describe SourceBots is like <a href="https://en.wikipedia.org/wiki/Robot_Wars_(TV_series)">Robot Wars</a>, but less violent and completely autonomous.</p>
<h2 id="the-game">The Game</h2>
<p>{{&lt; figure src=&ldquo;/img/posts/sb2018/arena.svg&rdquo; width=&ldquo;50%&rdquo; caption=&ldquo;Layout Diagram of the Arena&rdquo;&gt;}}</p>
<p>The game, as always with this style of robotics competition, involved moving cubes around an arena. The objective this year was to place cubes in the large zones marked by the colour of the corresponding robot&rsquo;s corner. The scoring was as follows:</p>
<ul>
<li>+3 points for each token of your colour in your zone.</li>
<li>-1 points for any other colour in your zone.</li>
<li>+1 points for moving out of the starting area.</li>
</ul>
<p>As the arena is setup with 5 opponent tokens in your zone, each team begins with -5 points at the start of each round. This led to all teams having an overall negative game score, but this was not an issue as we score positionally.</p>
<p>{{&lt; figure src=&ldquo;/img/posts/sb2018/photo.jpg&rdquo; width=&ldquo;50%&rdquo; caption=&ldquo;The Arena, with beautiful rotationally symmetric tokens&rdquo;&gt;}}</p>
<p>One issue that we came across when designing the competition is that if placed randomly, some robots could have an advantage compared to others in the same game. The solution to this was to place the markers rotationally symmetrically around the centre. I wrote a rather <a href="https://github.com/sourcebots/sb2018-zone-layout-generator">nice python script</a> to generate layout diagrams to assist the volunteers in laying out the arena between matches.</p>
<p>The full rules for the 2018 game can be found in the <a href="https://github.com/sourcebots/sb2018-rules">rules repository</a> on the SourceBots GitHub.</p>
<h2 id="the-kit">The Kit</h2>
<p>We supplied the teams with a base kit centred around a <a href="http://raspberrypi.org">Raspberry Pi 3</a>, with a board to regulate power, a motor board, a servo board and a webcam. The hardware was based on the <a href="https://studentrobotics.org/">Student Robotics</a> v4 kit. However, the software on the pi has been completely re-written by the SourceBots (see <a href="https://github.com/sourcebots/">our GitHub</a>). Improved features compared to the SR kit include full support for Python 3, a new <a href="https://en.wikipedia.org/wiki/Fiducial_marker">Fiducial marker</a> system based on the <a href="https://april.eecs.umich.edu/software/apriltag.html">April Tags</a> system developed at the University of Michigan and a fully automated image build system. The kit is still in development after the competition and we have many more exciting ideas planned for the future. More information can be found on the <a href="https://docs.bsourcebots.org">SourceBots docs</a> if you are interested.</p>
<h2 id="the-livestream">The Livestream</h2>
<p>The competition finals were broadcast live by <a href="https://www.facebook.com/SUSUtv/">SUSUtv</a>, the student television society here at Southampton.</p>
<p><iframe style="border: none; overflow: hidden;" src="https://www.facebook.com/plugins/video.php?href=https%3A%2F%2Fwww.facebook.com%2FSUSUtv%2Fvideos%2F1891818877517292%2F&amp;show_text=0&amp;width=560" width="560" height="315" frameborder="0" scrolling="no" allowfullscreen="allowfullscreen"></iframe></p>
<p>&nbsp;</p>
<p>!!!! This post was originally written by Dan Trickey, and has been reposted with permission. Original Article</p>