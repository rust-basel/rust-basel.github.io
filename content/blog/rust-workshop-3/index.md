+++
date = 2024-11-23
title = "Rust Workshop #3"
description = "Rust + HTMX"
authors = ["Silen Locatelli", "Roland Brandh", "Yasin Gündüz"]
[taxonomies]
tags = ["Workshop", "Axum", "Askama", "Server Side Rendering", "HTMX", "letsboot", "E+H"]
[extra]
math = true
image = "banner.png"
+++

# Topic

Our third Rust workshop in Basel. This time we tackled creating a web application with Rust and using HTMX.

As there exists something like a javascript "fatigue" with ever new emerging JavaScript Frameworks,
the web world seems to go back to server side rendering, which reduces the amount of complexity.
As until now, we had to swap the whole page, when we rendered server side. HTMX fixes this by bringing
reactivity in browser, to only fetch HTML directly from the server endpoints instead of JSON and exchange this HTML snippet in a
defined place in the DOM.

# Resources

The guidebook from this workshop you can find [here](https://rust-basel.ch/https://rust-basel.ch/htmx-workshop-meetup-10/).
If you also want to execute the code snippets we provided, you can also clone/fork the [repository](https://github.com/rust-basel/htmx-workshop-meetup-10) direclty, as everything is
in the same place.

# Outline of the Workshop

First we had a lecture style morning, where Silen, Yasin and Roland talked about the needed components (server, server side rendering, htmx) for the afternoon,
where people were on their own hacking their own htmx application.

Yasin talked about Axum, how you write endpoints in the webserver framework [axum](https://github.com/tokio-rs/axum). Also the participants
learned how to add receive data in an endpoint and how to add, read and mutate state in their application.

Roland tought participants, how they can render server side html with [askama](https://github.com/djc/askama). He showed
how you can compose html templates together to build a bigger template. Or inherit a base layout, which is important if you want
to have e.g. a navigation bar or a footer for your web application.

Silen showed in the end how [htmx](https://htmx.org/) works. How you can simply fetch HTML and insert, or exchange the fetched HTML in the DOM.
Moreover he showed live examples from his work, where he uses HTMX with Kotlin and showed it. He also built
a htmx web application in this year's [baselhack](https://www.baselhack.ch/), that he also showcased.

After a small pizza break, the participants could apply the tought content in a free manner, where they could
build a small application themselves, or just tried out things in the specified parts (Webserver, Rendering, HTMX).

# The meetup itself

We had 6 participants (9 with the organizers), that enjoyed a lecture in the morning, Pizza at [VITO](https://www.vito.ch/) at Aeschenplatz in Basel,
and a "hacking" part in the afternoon. They could either build their own application, or build on top the tought content and
got help from lecturers, if they needed.

Some impressions from this meetup:

<div style="display:flex; justify-content:space-between">
    <img title="some title" alt="Alt text" src="/img/workshop-33.jpg" width="30%" style="margin-right=5px"/>
    <img title="some title" alt="Alt text" src="/img/workshop-31.jpg" width="50%" style="margin-right=5px"/>
</div>

# Sponsors

We are very grateful for Endress+Hauser Digital Solutions for sponsoring the food and drinks for this event.

<div style="text-align: center;">
  <img src="/img/EndressLogo.png" alt="Alt Text" width="50%" style="display: block; margin: 0 auto;" />
</div>

We are also very grateful for [Letsboot.ch](https://www.letsboot.ch/) for sponsoring the location of this event.

<div style="text-align: center;">
  <img src="/img/LetsBoot.png" alt="Alt Text" width="50%" style="display: block; margin: 0 auto;" />
</div>

If you want to scale your software or systems engineering career, make sure to check out one of their courses!

# Next meetup

If you like to attend future meetup meetings you can find the them [here](https://www.meetup.com/rust-basel/).

See you next time! :)

Roland, Silen and Yasin
