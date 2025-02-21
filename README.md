# Officiating History

Over the years Lindsay Scott and Dennis Kehoe have done all the hard work and collected together lots of information about world level games. There are a few gaps in the early years but it is a great record. The core information is held in spreadsheets, one for each championship. For some queries you might have spreadsheets are fine but there will be queries that some sort of database approach will make searches across championships much easier.

Officiating History Data - Mens - shared.xlsx
Contains a copy of the master spreadsheets. These include some minor changes from the Lindsay and Dennis originals. These changes are mainly to get consistent names for officials.

I’ve had a go at loading many of the records into WikiData and have written a couple of queries – still early days – rough and ready.
This is very much a trial and I would appreciate any feedback (be nice) on 
- the queries written so far
- the accuracy of the information returned
- what other queries you might find useful

What has been loaded so far

All men's world level games for which we have records
- officials with roles
- teams
- scores
- dates
- admin roles

What has not been loaded yet
- coaching/assessment assignments
- field used
- group or placement for game
- most women's officials or games

So far there are three queries. For now at least it will be best to use a computer or device with a big screen. To run the scripts just click one of the links.

[Official matches](officials_v18.html)

returns all games for a given official – have to get name exactly right or nothing returned
There have been a number of instances where a given official's name has differed between championships - e.g. Rob or Robert
If you search for the games of an official and get nothing back try the officials_at_event query for an event you believe that official took part in. Hopefully you will find the right spelling of their name. In the future we can look to make this a bit more clever if we move beyond a trial.


[Games at event](officials_at_events_v3.html)

returns all officials at a given event using a drop-down list of events. This query can be a little slow, 10 to 15 seconds so please be patient.

[Games at women's event](officials_at_women_events_v1.html)

returns all officials at a given women's event using a drop-down list of events. This query can be a little slow, 10 to 15 seconds so please be patient.

[Games at men's event](officials_at_men_events_v2.html)

returns all officials at a given men's event using a drop-down list of events. This query can be a little slow, 10 to 15 seconds so please be patient.

[Role of official at events](officials_roles_v1.html)

returns a list of the events in which a given official participated. Again, the official's name needs to be exacly right or nothing is returned.

# Master records

Here are the excel workbooks that contain the officiating records collected so far

[Women's world championships](https://grahamblyth.github.io/officiating-history/download/Officiating_History_Data_Womens.xlsx) - this file can be downloaded. Last updated 21 February 2025.

# Advantages and disadvantages of WikiData
[Welcome to Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page)

In addition to making some searches a lot easier WikiData and databases generally allow errors to be corrected or changes to be made with less pain. For example - if Rob Smith wants to be listed as Robert Smith the change only needs to be made in one place and it will (almost) immediately be reflected in the output from any queries.
By its nature the Wikipedia family of tools and the WikiData items in particular are subject to change. Since I started this work for example there have been more that 20 changes to the entry for Iroquois. When I started the associated WikiData item would return Haudenosaunee, today it returns Iroquois. There are several other teams where the associated country label has changed. Although lacrosse officiating is super important it could be problematic to change country labels within WikiData!


