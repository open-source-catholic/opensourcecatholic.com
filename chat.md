---
layout: page
title: "Chat"
permalink: /chat/
redirect_from:
  - /irc/
  - /catholic-irc-chat-channel/
---

**We're building a community of Catholic developers.** Come join us! You can find us on Slack and on IRC.

## Slack

The <a href="https://catholicdevs.slack.com"><i class="fab fa-slack"></i> <span class="username">catholicdevs</span></a> Slack Workspace is a place to engage with other Catholic developers across the globe and grow together by getting to know each other, sharing our faith, and collaborating on projects.

To join CatholicDevs on Slack, you must request an invitation.

<div class="slack-invitation">
  <div id="CommunityInviter"></div>
</div>
<div class="slack-help-link">
  <a href="https://slack.com/help/articles/115004071768-What-is-Slack-">What is Slack?</a>
</div>


## IRC

Below, you can login to the public Catholic chat channel on the [Libera.Chat](https://libera.chat/) IRC (Internet Relay Chat) system. Simply type in a nickname and click the "Connect" button.

Scroll down for more details, and to find out other ways to connect.

<iframe src="https://web.libera.chat/##catholic" width="675" height="490"></iframe>

### What is IRC?

_From [Wikipedia](https://en.wikipedia.org/wiki/Internet_Relay_Chat)_: Internet Relay Chat (IRC) is a form of real-time Internet text messaging (chat) or synchronous conferencing. It is mainly designed for group communication in discussion forums, called channels, but also allows one-to-one communication via private message as well as chat and data transfers via Direct Client-to-Client.

The [Libera.Chat Documentation](https://libera.chat/guides/basics) is a good place to start if you want to learn more.

### How do I join the ##catholic channel?

Connect to the `irc.libera.chat` server and type in `/join ##catholic` from within any IRC client. Soon you'll be speaking with many others like you, who are interested in spreading the Catholic faith through technology.

### Alternate Ways to Access IRC

There are many ways to join a channel in IRC:

  - Use the web client (either above, or at <https://web.libera.chat/##catholic>).
  - Use an IRC client for your Mac or PC (a good list of [IRC clients](https://en.wikipedia.org/wiki/Comparison_of_Internet_Relay_Chat_clients) on Wikipedia).

### Some Cool IRC Tricks

**Private Messaging**: have something you want to discuss with someone privately, outside the public ##catholic channel? Just type in `/msg username` (replacing `username` with the username of the person you want to talk to).

**Changing Names**: if you'd like to change your username (say, to inform someone you're on the channel, but need to run for a minute), type in `/nick new_username` (example: if you're running to lunch, type in `/nick username_lunch`).

**Directed Messages**: To 'ping' someone inside the channel, simply type in his username and hit enter, or add his username anywhere in your message. Bonus shortcut: just type in the first couple letters of a username and press tab - the program will fill in the rest of the username!


<script>
  window.CommunityInviterAsyncInit = function () {
    CommunityInviter.init({
      app_url:'open-source-catholic',
      team_id:'catholicdevs'
   })
  };

  (function(d, s, id){
    var js, fjs = d.getElementsByTagName(s)[0];
    if (d.getElementById(id)) {return;}
    js = d.createElement(s); js.id = id;
    js.src = "https://communityinviter.com/js/communityinviter.js";
    fjs.parentNode.insertBefore(js, fjs);
  }(document, 'script', 'Community_Inviter'));
</script>