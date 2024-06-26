---
tags: todo, api, json
language: ruby
resources: 3
---

# Spotify's Chart API Todo

## Objective

Get more familiar with using APIs and their JSON contents in Ruby.

## Introduction

Scraping sites is one way to get data but many times, companies will expose more data through their application programming interfaces, or APIs. For this todo, we're going to focus on [Spotify's chart API](http://charts.spotify.com/docs).

Before taking a look at an API, install a JSON Formatter extension into your browser. [JSONView Extension for Chrome](https://chrome.google.com/webstore/detail/jsonview/chklaanhfefbnpoihckbnefhakgolnmc?hl=en) is a popular one.

Now that a JSON browser formatter plugin is installed, make a guess about what the most streamed song on Spotify is. Keep that song in mind then click on the link below. This link should takes you to Spotify's open API for the most streamed tracks in the US over the past week.

  * [http://charts.spotify.com/api/tracks/most_streamed/us/weekly/latest](http://charts.spotify.com/api/tracks/most_streamed/us/weekly/latest). 

Did your guess match the first track listed? Were you right? Do you think the top streamed song in the US is the same as the top streamed song in Mexico? Take a look at [Mexico's top streamed tracks](http://charts.spotify.com/api/tracks/most_streamed/mx/weekly/latest). Is the most popular song the same?

## Instructions

* Now that you've played around with an API a bit, it's time to write some code that will allow you to interact with these API sites in Ruby.
* This is a test-driven lab so just get those specs to pass. Remember to start with the first specs then move to the later ones as they build on each other.

## Help

* If you get stuck, refer to the [docs](http://charts.spotify.com/docs), the resources below, and take a look at these urls and try to pattern match: 
  * [http://charts.spotify.com/api/tracks/most_streamed/](http://charts.spotify.com/api/tracks/most_streamed/)
  * [http://charts.spotify.com/api/tracks/most_streamed/us/](http://charts.spotify.com/api/tracks/most_streamed/us/)
  * [http://charts.spotify.com/api/tracks/most_streamed/us/weekly/latest](http://charts.spotify.com/api/tracks/most_streamed/us/weekly/latest)

## Resources
* [StackOverflow](http://stackoverflow.com/) - [JSON.load](http://stackoverflow.com/questions/18581792/ruby-on-rails-and-json-parser-from-url?answertab=votes#tab-top)
* [RubyDocs](http://www.ruby-doc.org/) - [JSON Load Method](http://www.ruby-doc.org/stdlib-2.0.0/libdoc/json/rdoc/JSON.html#method-i-load)
* [Spotify](https://developer.spotify.com/) - [Chart Documentation](http://charts.spotify.com/docs)
