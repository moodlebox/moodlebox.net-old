---
title: How to access to the command line interface?
author: Nicolas Martignoni
type: kb
date: 2017-04-20T16:49:52+00:00
slug: command-line-connection
categories:
  - Maintenance
  - Usage

---
As a normal user, you should not need to connect into the command line interface of the MoodleBox. Anyway, you may access it if necessary via SSH, using the address **moodlebox.home**, using its default credentials:

  * username: **moodlebox**
  * password: **Moodlebox4$**

### With PuTTY (under Windows)

Open a new connection, type the address **moodlebox.home** under _Host Name_, then click _Open_. Input the password **Moodlebox4$**.

<img class="alignnone size-full wp-image-444" src="https://moodlebox.net/fr/wp-content/uploads/sites/4/2017/04/PuTTY-moodlebox.png" alt="" width="516" height="498" />

### In a classical terminal interface

In your favorite terminal interface, type

`ssh moodlebox@moodlebox.home`

then type the password **Moodlebox4$**.