# TeleFred
An Alfred Workflow to Talk to Telegram

Discussion: https://www.alfredforum.com/topic/14201-telefred-chat-through-telegram/

t - write to a user or group, see history 

tr - Quick reply to last user

ta - Activate Telegram with user selected

treset - Delete cache files (should have no effect), remove com.apple.quarantine flag from telegram-cli and start telegram-cli in terminal window, so you can 

= To install: = 

Before you can use it, you have to run 'treset' once, to remove the quarantine-flag from telegram-cli and log into telegram! 

In the terminal:
- put your phone number (without the "+")
- confirm the authentication code that you'll receive in your app

Telegram session information is stored in /.telegram-cli and not in the workflow directory.

*UPDATE*: I've switched to delivering a self-compiled version of telegram-cli from a more up-to-date repo, 'treset' should unlock it - but please let me know if it doesn't run. You might have to run "brew install telegram" nonetheless to install all the linked libraries it requires - I can't really test without a second Mac around. If you don't like binary blobs, feel free to build "telegram-cli" yourself from the kenorb-contrib repo and replace it in the workflow's directory.

= Releases =

0.0.1: Initial Release with commands: t, th

0.0.2: Added th, tc 

0.0.4: Major update: own telegram-cli from different repo (https://github.com/kenorb-contrib/tg, vysheng's seems abandoned, and brew installs the one from vysheng), merged th, tc and t, added ta to activate telegram with a certain user selected

= Wish List =

- tc - Call user

- tclip - Send clipboard to user

- tss - Send last screenshot to user

- Show media in the history


= If you want to help, that's very welcome! You can also talk to me on Telegram: t.me/raf_ael = 
