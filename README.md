# Desktop 

This desktop client protocol is currently being incubated. 


## Purposes 
**Verify ownership of apps (game/software).** A user should be able to generate a signed message with their existing wallet. An app should be able to read the signed message, and the public key associated with it. The game should also be able to request a new signature, and the desktop client should handle prompting the user. 

**Listen to `setListingUri` updates and auto-update if the files have changed**. 
