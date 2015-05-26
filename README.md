# wikiman
Wikipedia in your terminal! Generates man pages from Wikipedia pages and caches them

Pretty self explanatory, call it with the name of a Wikipedia page and it'll download the page and format it
into a man file which will then be cached and accessed instead of downloading the page again. Should have some kind
of refresh system in the future, but I wrote this in a few hours on too much caffeine so it's not the best quality
right now. But it works!

Oh and it needs the Nokogiri gem for the web scraping, and the Trollop gem for opt parsing so

    gem install nokogiri trollop
