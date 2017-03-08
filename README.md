# rbkc_da_events
Allow Event content type and events listings to be Domain Access compatible.

Installation
------------

1. Install the rbkc_da_events custom module - this is required to make the events listing work. 

2. This module will require the rbkc_events_domain_access feature that's included inside the module. The feature will install the Event content type, the view for the events main page (/events), and a view for the events listing (/events/%).

3. Create new taxonomy vocab: events_domainname, where domainname should be exactly the domain of the site, eg exhibitinroad or greenerborough. This will contain all the terms to be used with the Event content type. There should be one vocab per domain, e.g. events_exhibitionroad, events_greenerborough, etc.
