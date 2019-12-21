# TeleFred
An Alfred Workflow to Talk to Telegram

t - write to a user

th - show history with user and send message


it requires that you install telegram-cli, which - if you have brew installed - is a mere "brew install telegram" away.


Before you can use it, you have to start telegram-cli once in the command line to log in.


= Releases =

0.0.1: Initial Release with commands: t, th -


= Wish List =

- tg - Talk to Groups - currently limited because telegram-cli segfaults on the dialog_list command (known bug: https://github.com/vysheng/tg/issues/1580 ) - so we don't know what groups there are.

- tl - show 5 last conversations (likely victim to same bug)

- tr - Quick reply to last user

- tc - Call user

- tclip - Send clipboard to user

- tss - Send last screenshot to user

- Show media in the history


= If you want to help, that's very welcome! You can also talk to me on Telegram: t.me/raf_ael = 
