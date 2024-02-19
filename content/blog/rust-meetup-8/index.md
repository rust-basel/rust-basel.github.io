+++
date = 2023-12-14
title = "Rust Meetup #8"
description = "All about testing. Meet the maintainers of mockall and proptest-rs"
authors = ["Yasin Guenduez"]
[taxonomies]
tags = ["Talks", "Testing", "Property Testing", "Mocking", "mockall", "proptest-rs"]
[extra]
image = "banner.jpg"
+++

This time we had a remote session with two crate maintainers: Alan Somers from the mockall crate and Tomas Zevanovic from the proptest-rs crate.

1. [Mockall](https://github.com/asomers/mockall): Alan Somers
2. [Proptest-rs](https://github.com/proptest-rs/proptest): Tomas Zevanovic 

## Mockall

Alan Somers presented his crate mockall, where you can easily write mock objects. 

Mocks are powerful, as they can implement the same interfaces like your real objects. Their behaviour is fully controlled by the test code - making upper layers of your dependency chain easily testable.

If you are more interested in his talk, have a look at the [video session](https://drive.google.com/file/d/11wtjU8RGr6PQTft6V8jIn2dP7Cc1O4Kx/view?usp=drive_link) we recorded.

## Proptest-rs

Proptest-rs is a property testing framework. With this you can check that certain properties of the output of your code is fulfilled for every possible input. Tomas Zevanovic showed us some examples on how you can use proptest-rs to test your code.

If you want to have a look into his talk, here is his [recording](https://drive.google.com/file/d/1aTICaGEiaNLHXA-3PkMVgsRpMMnRRPdW/view?usp=drive_link).

