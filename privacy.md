# Privacy Policy

When you visit CyTube, certain information is collected from you.  This document
details what information is collected, how it is stored, and how it is used.

## Use of YouTube API Services

CyTube makes use of YouTube API Services in order to provide YouTube embed
functionality.  Use of YouTube-related features is subject to [Google's Privacy
Policy](http://www.google.com/policies/privacy).

## Account Registration

When you register a user account on CyTube, certain information is recorded and
stored in the database.  This information is visible only to website
administrators, except where otherwise noted.  The database is secured from
external access, and database backups are kept off-site and encrypted with GPG.
In addition to your chosen username, the following information is collected and
stored:

  * Your password is securely hashed using bcrypt, and the resulting hash is
    stored in the database.  This hash is used to verify that you provided the
    correct password when logging in.
  * The IP address associated with your computer is stored to facilitate
    identification of users with multiple accounts.  This is used to enforce a
    limit on the number of accounts a user may register, and to identify
    alternate accounts of users who have violated the rules.
  * If you provide an email address at registration, it will be stored in order
    to send you a recovery link should you ever forget your password.  Email
    addresses are kept private and are not sold or subscribed to any mailing
    list.  Providing an email address is optional, and you can remove it at any
    time by setting it to blank (note that this will make your account
    unrecoverable if you forget the password).
  * If you provide a profile image and/or profile text, it will be stored in the
    database and displayed publicly to any user in the same channel as you.
    Anything in your profile is considered public information, so don't put
    sensitive information in it.  Providing a profile is optional, and you can
    clear out your profile at any time.
  * The date and time that your registration was processed is recorded.

## Cookies

CyTube uses cookies to store certain information in your browser:

  * When you log in, a session ID is stored so that CyTube is able to identify
    you on future visits.
  * Your preferred theme is stored so that pages on CyTube will display using
    that theme.
  * If your browser does not support HTML5 localStorage, cookies are used to
    store your site preferences (such as preferred layout, preferred quality,
    chat settings, etc.).

## Aliases

CyTube keeps a temporary record of any username that logs in from your IP
address, up to a maximum of 5 names over the course of a month.  The purpose of
this is to identify users who are sharing the same connection in case of
moderation issues.  Refer to https://cytu.be/contact to request removal of your aliases.  Aliases are visible to all channel
moderators upon joining a channel.

## Chat Messages

When you participate in the chatroom associated with each channel, the chat
messages that you send are included in the log file for that channel.  Channel
administrators have access to a limited recent history of the log file in
order to oversee moderation of the channel; website administrators have access
to a longer history in order to resolve administrative issues.  Website
adminstrators do not read the log files unless they are suspected to provide
useful information for handling an administrative issue.  Log files are wiped
from the server periodically to conserve disk space and preserve privacy.

It is important to note that when you send a chat message, that chat message is
broadcast to every user in the channel.  Other users could be monitoring or
logging the chat messages separately from CyTube, so be careful what you say and
do not post any personally identifying or private information.

## Private Messages

CyTube also allows users in a channel to message each other privately.  These
messages are not logged to CyTube's server; however, as with chat messages,
recipients of private messages may collect the information independently.

## Channel Data

Channel data, such as configurable settings, chat filters, emotes, moderators,
bans, the video library, and the playlist are stored in the same database as
user accounts.  Some channel data can be limited to certain users by configuring
the permissions appropriately, however there is some channel data that is always
considered public:

  * Any video that is played on the channel at any time.  Note that even if the
    playlist and library are hidden with permissions, the link to the currently
    playing video is always public information, by necessity since users need to
    be able to see the video.
  * The source code to the channel CSS, channel JS, and channel MOTD.
  * The emote list, including emote names and links to emote images.
