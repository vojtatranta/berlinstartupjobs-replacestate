# Replace state implementation for AJAX paging on Berlinstartupjobs.de

Dear Berlinstartupjobs.de,

I really like your site. I read articles there regularly and most of all I read new job post
because I am interested in an opportunity to work abroad (I am from Czech Republic).

But there is one thing that drives me crazy.
We are living in 2015 and you force me on my mobile phone to open every single job post
I want to read on a new tab.
I currently own and android phone and you know how terrible user experience it is?
Because if I just click another post and then go back to list I get back to page 1.
So then I have click on "read more" again and again to go through all the post I read to get where I was second ago
and it is a long road, because u have strange policy of having some featured post on top on every
single page. Uhhh...

## Some solution
Since your paging is very strange by itself; lots of post are repeating for some reason, I just implemented
History.replaceState and it might help you to improve this awkward UX.

So now, if you click on "load more" link the URL changes according to this link
and then if you go back from some post you get to URL where you really was.

### P.S.
Please, please implement something like this, please fix it, I am probably not only one person on the planet
who reads your web on mobile phone.
#### P.P.S
Thank you for your work, your site is great!
