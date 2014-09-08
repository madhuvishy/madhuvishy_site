<!-- 
.. title: Second stint at Hacker School - Devlog Week 1
.. slug: second-stint-at-hacker-school-devlog-week-1
.. date: 2014-09-07 21:13:37 UTC-04:00
.. tags: HackerSchool, devlog, code, Geek
.. link: 
.. description: 
.. type: text
.. author: Madhumitha Viswanathan
-->

It's been super exciting returning to Hacker School for another batch. I'd started with Clojure the last time, and this time's goal was to become better at it, and also learn about distributed systems. The first week went pretty well, and here's a summary.

* ####[Yet another Bittorrent client](https://github.com/madhuvishy/yobc)

Writing a Bittorrent client is an oft taken up project in Hacker School, given the array of concepts it covers. To get the feel of building a larger system using Clojure, and understanding how to manage concurrency and communication, I decided to build one too. After a brief walkthrough about the steps involved with Alan, one of our facilitators, I got started with first building a parser for Bencode - the format in which torrent file data is stored. Once I had the encoder/decoder done, I got started on the UDP tracker protocol. I'm still on that, but I can successfully send and receive UDP messages now. 

* ####Work on community.hackerschool.com

The community project is a new internal Hacker School site, as a replacement to the use of mailing lists for communication. It's built with Ruby on the server side and Om/Clojurescript for the frontend - and that's interesting to me, and I've been making tiny contributions - 2 so far, thanks to Zach, who's been so patiently explaining stuff to me and helping me out.

* ####Jobs Friday - [Phonebook](https://github.com/madhuvishy/phonebook)

As part of the friday job prep related activities, this week's task was to spend 2-3 hours building a small command line phonebook app, that can create phonebooks, and do add, delete, update and lookup on it's entries. I built a simple one with clojure using files to persist data - this exercise was a lot of fun!

That's all for this week. Fingers crossed for my Bittorrent client to do wonders by the next ;)
