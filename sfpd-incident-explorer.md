## Problem statement
The police department gets a lot of ad hoc requests like: send me all of the incidents around this address. Now they have to respond to these internally using mapping tools. However, the data is already on the portal and they could just send people there for some self-service reports, but you can't do radial queries through the interface on the open data portal. The API does support this though. 

## Challenge
Build a basic UI that allows folks to query the crime incident data by radius and possibly polygonal boundary like neighborhood (for bonus points). Go a little further and show some quick stats based on that query.

## Inspiration
* Many of these ad hoc requests come from Universities per the [Clery Act](http://clerycenter.org/summary-jeanne-clery-act).
* There's a [prototype of the basic interaction already](http://jasonlally.com/incident-reporting/) [source code here](https://github.com/jasonlally/incident-reporting)
* If you abstract this, code could easily be reused on other similar geo queries for any dataset on our portal (or others)
