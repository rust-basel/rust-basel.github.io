+++
date = 2023-03-28
title = "Rust Meetup #7"
description = "Interesting Rust Talks @ Endress+Hauser in Reinach (BL)"
authors = ["Yasin Guenduez"]
[taxonomies]
tags = ["Talks", "FFI", "Coding in Web Apps", "Event Streaming"]
[extra]
image = "banner.jpg"
+++

This time we had three interesting talks: from Attila Bujaki, Roland Brand and Yasin Gündüz.
1. Cloud Native Event Streaming (Attila Bujaki)
2. IDE-level coding in Web Apps (Roland Brand)
3. Foreign Function Interfaces (Yasin Gündüz)

## Cloud Native Event Streaming

Attila Bujaki showed us how you can leverage [Oura](https://github.com/txpipe/oura) to create a realtime event-stream from the Cardano Blockchain.

If you are interested, have a look at his [slides](https://drive.google.com/file/d/1upqLGw3vnqFiuWXtfcpB9q04s0H7-TL_/view).

## IDE-level coding in Web Apps

Interested in building a web based IDE? Roland Brand showed us a live prototyp which does exactly this. Leveraging the language server protocol (lsp), served with websockets with [axum](https://github.com/tokio-rs/axum) you got autocompletion in his web editor.

You can also have a sneak peak into his [slides](https://docs.google.com/presentation/d/1BdkUcrBshtd4XkH_NpWh_a0vXNGpGdyJ/edit#slide=id.p1).

## Foreign Function Interfaces

Sadly most of the project you face today in the industry are not greenfield projects, where you can start from scratch. In brownfield projects it's more interesting how you can integrate e.g. a rust written library into already existing projects. Yasin showed us, how you can easily write a rust library, that is consumed in a C++ executable with [CXX](https://cxx.rs) and [Corrosion](https://github.com/corrosion-rs/corrosion).

If you are interested, have a look into:
- [Slides](https://docs.google.com/presentation/d/1h-85FV6myH_K9KIWYPGGgiB8Izp7zx5RUpfd3k2_0Ys/edit#slide=id.g21665984530_0_0)
- [Example Project](https://github.com/yguenduez/cxx-corrosion-ffi)
