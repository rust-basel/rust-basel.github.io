+++
date = 2023-07-01
title = "Rust Workshop #1"
description = "Let's build a Pokedex with axum. A beginner's workshop writing a REST backend with axum."
authors = ["Yasin Gündüz"]
[taxonomies]
tags = ["Workshop", "Axum", "Backend"]
[extra]
math = true
image = "banner.jpg"
+++

Our first Rust workshop in Basel. The workshop itself was split into two parts. 
Part 1 was about some Rust basics, so participants can read and also write basic Rust programs.
Part 2, in the afternoon, participants could solve a small coding challenge: To create a [CRUD](https://en.wikipedia.org/wiki/Create,_read,_update_and_delete) [Rest](https://en.wikipedia.org/wiki/REST) API simulation a Pokedex, where you can manage your gathered information about your Pokemon discoveries.

## Part 1

The first part of the workshop was about basic Rust topics, including:
- Tooling
- Function & structs
- Branching & Looping
- Traits
- Memory & Lifetimes
- Enums, matches & errors

If you are keen to look into details, we recommend you have a look at the [slides](https://github.com/rust-basel/rust-meetup-8/blob/main/slides.md).

## Part 2 

The second part of the workshop was about creating a small REST API.
Therefore we created a [code skeleton](https://github.com/rust-basel/axum-pokedex-starter), that participants could use.

Goal of the workshop would have been:

 **Create a webserver, offering create, read, update and delete endpoints for Pokémon:**
   - To create Pokémon: `POST /pokemon`
   - To read Pokémon: `GET /pokemon/{id}`
   - To update an existing Pokémon: `PATCH /pokemon/{id}`
   - To delete a Pokémon: `DELELTE /pokemon/{id}`

During the workshop participants got help from us, so they could work into the goal's direction. 

Most of the participants did not finish the challenge, as the challenge itself seemed too much of a scope. Nethertheless we provided a possible [solution](https://github.com/rust-basel/axum-pokedex) for the challenge.

## Conclusion

As this was our first workshop, we also gained a lot of knowledge. First of all - do not expect the participants to know what you already know. Doing Rust for several years vs. someone who just started with their first typed langauge. Obviously that is out of scope.
Some participants also wished the second part would have been more guided. I.e. we show them step by step on how to build such a Rest backend in Rust.

So for our next workshops we will consider those two points.
But in general people liked the workshop and also learned a lot - especially the first part with the basics was considered very good.

So what else to say? I guess we see us in the next workshop.

Best
Roland & Yasin
