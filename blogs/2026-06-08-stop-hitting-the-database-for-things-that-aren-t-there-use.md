---
title: "Stop hitting the database for things that aren't there: Use a Valkey Bloom Filter"
url: "https://aiven.io/blog/intro-valkey-bloom-filter"
date: "2026-06-08"
author: "Jay Miller"
feed_url: "https://aiven.io/blog/feed.xml"
---
Every time your app asks the database 'does this row exist,' it pays the cost of a database query to get back 'no'.
