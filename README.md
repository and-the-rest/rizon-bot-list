The file botlist.txt contains an eternally incomplete list of known bots on the Rizon IRC network.

If you are making a bot to run on this network, you should

1. Let us know so we can add it to this list
2. Have your bot ignore everything on this list

Bots ignoring each other is simple, good policy. If this doesn't happen and multiple bots are gathered in a channel, they might trigger off each other's lines and cause a flood of messages that disrupt normal conversation. Occasionally, particularly naive bots might even get stuck in a botloop: an endless stream of messages that perpetuates itself and only ends when one of the bots involved is kicked. So be a good developer, and have your bot ignore all bots you can find. This list should be a good start.
