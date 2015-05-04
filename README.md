#Mutt Configuration

My configuration has the following features:

- Configured for using [Gmail](http://mail.google.com/) 
- Support for [GnuPG](https://www.gnupg.org)
- Intelligent use of colour for highlighting email headers and URLs etc

I've used [The Mutt E-Mail Client](http://dev.mutt.org/doc/manual.html) since 1996 and it is by-far the greatest
email client ever written.  After recently using it to easily transfer several thousands old emails into gmail
this is the setup I used - you'll have to change this to your details but it serves as a good example.

##Forward local mail to Gmail
If you have a local SMTP server setup you can create a file in your home
directory to forward all email to another account, e.g.

<pre>
~/ $ cat > .forward
vijay.mahrra@gmail.com
</pre>

##installing mutt
###MacOS X
`brew install mutt`

###Debian/Ubuntu/Linux Mint
`apt-get install mutt`

