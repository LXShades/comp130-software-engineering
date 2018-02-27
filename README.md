# comp130-software-engineering

## Which compression techniques for large-scale player synchronisation are ideal for improving speed and reducing bandwidth?  
## How can static meshes be speed-optimised for realtime destruction and morphing?  
## 

Challenge area, system area, application area.

# Proposal
The exponential bandwidth consumption resulting by distributing player data in large-scale multi-player games is a significant challenge to game developers. Server maintenance costs are high as a consequence of high bandwidth use. Furthermore, a high percentage of UK homes run on a broadband speed at around 15Mbps, which roughly translates.  

This study is interested in finding new ways, in many places drawing inspiration from the recent and highly successful temporal video compression techniques achieved as a reaction to the growth of streaming services such as YouTube.  

To identify potential costs, this study will first aim to discover the presently known costs of game server maintenance. This will help us understand how much could be gained or lost from a reduction in network packet traffic, and thus how much time, money and effort a company may invest in combating the issue.  

Following this, the study will attempt to uncover present weaknesses in common practices. This will share technical insight into the most significant bottlenecks common in today's online games. A particular genre of interest is the MMO genre, as well as the growing `battle royale', genre both of which can enjoy masses of players synchronised in a single world. These games are particularly vulnerable to exponential bandwidth congestion due to the player traffic sent from each player to each other player.  

Finally, it will propose techniques to reduce packet consumption. This may include existing game networking techniques, image compression, and video compression or streaming strategies.  

Video compression is a particular area of interest, owing to its temporal nature: frames are compressed not in absolute terms, but relative to the previous frame. This is not unlike the changes in player states as they progress through a game, although the specific types of data are quite different. Whether or not image data compression can be transferred to player data for any specific technique will be carefully considered throughout the essay.  

The rapid advancement of the video compression domains could expose new opportunities in the game industry to efficiently compress and distribute update packets in previously unexplored ways. Should this happen, it may reveal the possibility for larger-scale persistent multi-player games to be created at a reasonable and sustainable cost for the interested game developer.  