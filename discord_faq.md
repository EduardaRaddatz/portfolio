# Rich Presence FAQ

> The SDK that this documentation references, Discord-RPC, has been deprecated in favor of our new Discord GameSDK. Replacement functionality for the Rich Presence SDK can be found in the Activity Manager of that SDK. This documentation can be referenced for education but does not entirely reflect the new SDK.
Below are answers to some common questions about integrating Rich Presence with your game. If you don't see your question answered here, feel free to reach out to gamedevs@discord.com for more help.

### **1. Absence of Rich Presence data while "Playing MyGame" is running**

If you're having trouble with your Rich Presence data:

1. Verify if you have **two instances** of Discord being executed at the same time,
2. Observe your Discord_Initialize is **working properly**.
    1. Guarantee you have your errored() and disconnected() callbacks hooked up for debugging. 


