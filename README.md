# comp130-software-engineering

# Notes
- Ghinea's research: http://ieeexplore.ieee.org.ezproxy.falmouth.ac.uk/search/searchresult.jsp?searchWithin=%22Authors%22:.QT.Gheorghita%20Ghinea.QT.&newsearch=true
- Boost Asio

# Articles of Interest
http://ieeexplore.ieee.org/document/6772102/?section=abstract  
http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6772102 (direct)
*It was observed that the content genre has an
impact on the viewer’s quality of experience. For
example, the Sintel clip is ideal for young people as it
tells a good story and hence keeps them engaged. The
David and Laura clip is more suitable for professional
people who have work experience. But equally
important is the nature of the scene itself. During the
preparation of the sequences, we noted that it was
difficult to spot oscillations in image quality when
there are frequent scene changes. It takes time for the
mind to adjust to the new scene before really noticing
the quality. This is known as the Weber-Fechner law
[10].* 


# Proposal: Which C++ architecture(s) could best support QoE-oriented map streaming in a player-building-based multiplayer game?
Free-to-play multiplayer games enjoy a high popularity in poorer countries such as China, Brazil and Mexico, yet the lower broadband speeds in these areas can pose a particular challenge to games with persistent player-built worlds. This type of world requires the server to upload level data periodically to players in order for them to enjoy the latest version of an area as they enter it. The game may thus employ several different compression, prioritisation and/or data rate compensation techniques in order to achieve smooth gameplay, even on a reliable network.  

The asset download period is critical for players, as the data they receive determines which parts of the game they can play whilst the rest downloads in the background. Broadband speeds remain notoriously unreliable, especially in developing countries, so in order for games to be accessible to this wider market, they must reduce their bandwidth while still providing enough data to be playable during the download period. This includes reordering the data stream, with a priority on the player's best interests, such as their abilities first, in a concept more broadly known as quality-of-experience (QoE).  

There are many known applications of QoE. However, this essay more specifically explores which applications of fundamental design patterns are most suitable in the context of an online game where players may build the environment, a la Minecraft. It covers three core areas:  

- To gain further insight into the weight of the issue, the significance and impact of low bandwidth on the player's end will be explored and challenged. Grey literature such as developer retrospectives may provide the most information on this topic.  
- To discover potential architectural strengths and flaws, existing methods and architectures used by developers will be identified. As there may be some architectures with a wide potential of uses, traditional single-player system architectures employed by successful games may be explored in addition to those in multiplayer games. Any trend of difference between them is a point of interest.  
- Finally, this essay will compare the most popular architectures in general, and attempt to deduce which may be the most efficient through an analysis of each area's noted flaws and strengths. While the broadness of potential solutions is implied, and perhaps a key part of the appeal of game programming as a whole, the essay will conclude with its own particular proposal for the hypothetical building game.  