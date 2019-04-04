## Automated `/register` and `/login`
(a script for the [Macro / Keybind Mod](https://www.liteloader.com/mod/macros))

### Notes
If you are asked to /register, the script will register with a random password

### Install Instructions
- place `onChat.txt` `onJoinGame.txt`, and `onSendChatMessage.txt` into `.minecraft/liteconfig/common/macros`
- configure `onChat` `onJoinGame`, and `onSendChatMessage` events to `$${$$<[eventName].txt>}$$`
- profit?

### Warning!
if you do `/login <password>`, your password will be overwritten! Please keep copies of `.globalvars.xml`

your password is stored, sent, and shown in plaintext!

