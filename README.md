# isbadWord

Simple PHP function to check for bad words.  Handy for checking usernames on signups and registrations.

Really simple to use:

<code> if(isBadWord(word)) <-or-> if(!isBadWord(word)) </code>  
  
The badWords array is the standard set of bad words.  If using for a registration form and you don't want people to use site specific words like admin, administrator, moderator, sysop, etc, then add these to the customWords array at the top of the function.  It's sepearted to keep it neat.

I do keep adding words to this every now and again, so if you see anything that can be added, please comment and I'll expand on the collection.
