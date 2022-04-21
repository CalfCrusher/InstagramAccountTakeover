# InstagramAccountTakeover

This tool generates random reset URLs and check if still valid for account takeover.

### USAGE:

`$ git clone https://github.com/CalfCrusher/InstagramAccountTakeover`

`$ cd InstagramAccountTakeover && pip3 install -r requirements.txt`

`$ python3.9 main.py`

### HOW IT WORKS:

This tool generates infinite URIs, call them and check status code. If 301 then our link is valid -but could be expired- so we could takeover an account. If 302 our link is not valid.

When you try to reset your Instagram Password you are prompted for an email or a phone number.

Then you will receive a link like: *https://ig.me/TXGiR6ctW0hAO9f*

Following this link you prompted to reset your password or just skip it and go to your account directly without changing password, like many people do.

### DISCLAIMER

### Note that a 15 chars string (a-z, A-Z, 0-1 charset) is simply TOO MUCH to brute !
It's like looking for a needle in a haystack! Find a valid link is like playing the lottery!

*if you feel lucky you can let this tool run for weeks, maybe you will find something :-)*
