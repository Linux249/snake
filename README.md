# snake


# ideas
- grid where a player is or not
- zoom out with higher score
- use socket.io for send updates 
-- only send changes to rhe user (not if a snake grows and her tail is stoped)
-- only send players interaktion snd let the client make busines logig
- endless map: the user doesnt see a boarder 
- the snake grows if she hit a piece of food with his head
- there are different kind of foods:
-- smaler/bigger (less/more points/growing)
-- 
- a player dies if the snakes head hit his own body or another snake
- if a layer dies she left a piece of food

- player logs in before playing? facebook/oauth
- different food for the snake
- different style of the game (retro/rainbowcolor/modern)

# QUESTIONS:
- how to sync clients thats all have dame tick?
- where to set middle if the screen
- how the get synch

# TODO
- looking for oauth tutorial


# Architectur: 
- starting: 
- the servers "ping" the client where the snake is 
- If the user hit a arrow key the server get the key and response with the maybe new direction of the snake
