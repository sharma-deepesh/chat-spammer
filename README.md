# Chat-spammer
A simple chat spamming bot that works with Whatsapp Web and FB Messenger.

Chat Spammer is a script that sends a particular string or message given number of times to a specific person. The script can be used by anyone who use Whatsapp Web or FB Messenger. 

Whatsapp Web can be accessed online by going over to <a href="https://web.whatsapp.com">this link</a>.
FB Messenger can be accessed online by going over to <a href="https://messenger.com">this link</a>.

<h3>How It Works?</h3>
The script works in this way that it first takes the spam-string and spam-count as inputs from the user. The user needs to keep their Whatsapp Web or Messenger tab opened in the browser. The script then automates the message sending process using PyAutoGui module which has various keyboard and Mouse operation methods. <br/>

<strong>Note : Regular spammings can cause the user's account to be blocked by Whatsapp and FB moderation. So, use in limits.</strong><br/>
<i>The coordinates that are provided in the source code work for me and must work for most of the users as well. However if not, the user can always change the coordinates in the "spamming.py" file. The cursor coordinates must align with the "Type your Message Here" prompt.</i><br/>

Linux users can check their cursor positions by entering this command in the terminal. <code>xdotool getmouselocation</code>
Windows users can download any of the MouseTracker applications available on the internet.
