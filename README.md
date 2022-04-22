# InstagramAccountTakeover

This tool generates random reset account URLs and check if they still valid for a complete Instagram account takeover.

### USAGE:

`$ git clone https://github.com/CalfCrusher/InstagramAccountTakeover`

`$ cd InstagramAccountTakeover && pip3 install -r requirements.txt`

`$ python3.9 main.py`

### HOW IT WORKS:

When you try to reset your Instagram Password you are prompted for an email or a phone number.

Then you will receive a link like: https://ig.me/TXGiR6ctW0hAO9f

Following this link you have the possibility to reset your password OR just skip and go to your account directly, like many people do. **If this happens the link will remain valid! It doesn't expire neither after 24 hours... that's crazy.**

So, this tool generates infinite URIs, call them and check status code. If 301 then our link is valid -but could be expired!- so if user didn't change his password we could takeover the account. If 302 our link is not valid.

### DISCLAIMER

### Note that a 15 chars string (a-z, A-Z, 0-1 charset) is simply TOO MUCH to brute !
It's like looking for a needle in a haystack! Find a valid link is like playing the lottery!

*if you feel lucky you can let this tool run for weeks, maybe you will find something :-)*

