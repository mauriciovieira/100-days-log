<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Round 3](#round-3)
  - [2018-08-10 day 11](#2018-08-10-day-11)
  - [2018-08-06 day 10](#2018-08-06-day-10)
  - [2018-07-30 day 9](#2018-07-30-day-9)
  - [2018-07-29 day 8](#2018-07-29-day-8)
  - [2018-07-28 day 7](#2018-07-28-day-7)
  - [2018-07-27 day 6](#2018-07-27-day-6)
  - [2018-07-26 day 5](#2018-07-26-day-5)
  - [2018-07-25 day 4](#2018-07-25-day-4)
  - [2018-07-24 day 3](#2018-07-24-day-3)
  - [2018-07-23 day 2](#2018-07-23-day-2)
  - [2018-07-22 day 1](#2018-07-22-day-1)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


## Round 3

Yet another restart :smiley:

### 2018-08-10 day 11

For the last two days I've been working on a [csv2ofx mapping](https://github.com/mauriciovieira/csv2ofx/commits/leupay) for leupay bank.

![20180810-r3day11](https://user-images.githubusercontent.com/95258/43941328-5b23593e-9c7c-11e8-8c56-e2f9a9c6d067.png)

### 2018-08-06 day 10

After a few days not feeling well and a long weekend, I am continuing to work on my public repositories. I gave up on trying to run tests in docker so I setup chromedriver in travis-ci and now [supersales is green](https://travis-ci.org/mauriciovieira/supersales/builds/412496482?utm_source=github_status&utm_medium=notification).

![20180806-r3day10](https://user-images.githubusercontent.com/95258/43699174-54c1bd34-9956-11e8-98af-310fe32536d8.png)

### 2018-07-30 day 9

Worked on [supersales project](https://github.com/mauriciovieira/supersales/). I am trying to fix the red build. It is some Capybara configuration that I didn't figure out. The short time it was green was because it wasn't really testing the page. Lots of time and not much progress.

![20180729-r3day9](https://user-images.githubusercontent.com/95258/43423095-1adbf03c-9454-11e8-83fb-0dc1b700b72b.png)

### 2018-07-29 day 8

Worked on [my homepage](https://github.com/mauriciovieira/mauriciovieira.net/). Added a paypal donation button.
I also decided to create a [nvm playbook](https://github.com/mauriciovieira/eiitp/commit/3005d8a7f50e281853c06d5dbfa97878ca1994fe) for my local ansible installation: [eiitp - everybody is in the place?!](https://github.com/mauriciovieira/eiitp). I couldn't make it to install the latest nvm repo, so currently it is hardcoded to [v0.33.11](https://github.com/creationix/nvm/releases).

![20180729-r3day8](https://user-images.githubusercontent.com/95258/43370117-f1a61aee-9381-11e8-968f-14df1a94857a.png)

### 2018-07-28 day 7

Worked on [supersales project](https://github.com/mauriciovieira/supersales/). Added a few test cases for the [characterization test](https://amzn.to/2OpR997) and also improved the documentation.

![20180728-r3day7](https://user-images.githubusercontent.com/95258/43360519-38bb098a-92bf-11e8-9119-5a1044fe0521.png)

### 2018-07-27 day 6

Worked on [supersales project](https://github.com/mauriciovieira/supersales/). Added [devise-bootstrapped](https://github.com/king601/devise-bootstrapped) gem.

![20180727-r3day6](https://user-images.githubusercontent.com/95258/43343532-37b133f0-91ef-11e8-81bd-472501258e80.png)

### 2018-07-26 day 5

Finally closed [supersales#3](https://github.com/mauriciovieira/supersales/pull/3/commits). [Green build](https://travis-ci.org/mauriciovieira/supersales).

![20180726-r3day5](https://user-images.githubusercontent.com/95258/43279775-ac9bffd4-9117-11e8-8cf8-03a99669ca2c.png)

### 2018-07-25 day 4

Worked on [supersales project](https://github.com/mauriciovieira/supersales/pull/3/commits). Still struggling to make system tests to run inside docker (same as yesterday). Found an [article](https://www.alfredo.motta.name/dockerized-rails-capybara-tests-on-top-of-selenium/) and I am trying to follow [ledermann/docker-rails](https://github.com/ledermann/docker-rails/commit/02b6d80c5a0aba03f4ec553224ada11361162c66) example but something is still missing. All documentation and code I find is based on rspec, but I just want to use _vanilla_ rails 5.

![20180725-r3day4](https://user-images.githubusercontent.com/95258/43224758-dbf32c66-905f-11e8-9a28-0c128b15b134.png)


### 2018-07-24 day 3

Worked on [supersales project](https://github.com/mauriciovieira/supersales/pull/3/commits). Still struggling to make system tests to run inside docker.

![20180724-r3day3](https://user-images.githubusercontent.com/95258/43162271-301bf52a-8f93-11e8-9a9d-cca6aaaf7b1a.png)

### 2018-07-23 day 2

Worked on [supersales project](https://github.com/mauriciovieira/supersales/pull/3/commits). Decided to use [travis-ci](https://travis-ci.org/mauriciovieira/supersales), instead of cirrus-ci.

![20180723-r3day2](https://user-images.githubusercontent.com/95258/43099395-bbe71446-8eca-11e8-9753-7beed72bec62.png)

### 2018-07-22 day 1

Worked on [supersales project](https://github.com/mauriciovieira/supersales/pull/3/commits). Decided to use [cirrus-ci](https://cirrus-ci.com/github/mauriciovieira/supersales).

![20180722-r3day1](https://user-images.githubusercontent.com/95258/43049773-0323b4b0-8e06-11e8-9d5c-47f71d557b62.png)