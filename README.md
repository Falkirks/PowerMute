PowerMute
=========
A more effective way to mute users. 

### What does it do?
The initial concept of PowerMute was to make muted users think that everyone was ignoring them. This was accomplished by blocking the message and then sending a private message to the muted user, the goal of this was to prevent them from discovering that they were muted. The key issue was that the chat messages generated by PowerMute didn't account for changes made by other plugins to chat format. PowerMute 1.0 solves this issue by listening directly to outgoing packets and identifying senders using a regex. This ensures that PowerMute always gets the message after all other plugins have handled it. 