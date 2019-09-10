# Loose idea:
* Collect data on, and make an interactive data exploration tool to explore information about farmed fish, and think about welfare possibilities.
* The general problem is that the fish database is awesome but a bit hard to navigate.

* If you were evaluating where to focus on first, in terms of:
    * Research
    * Funding
    * Advocacy

## What would you be interested in?
* Which fish species are currently being farmed in the largest numbers?
* For which fish species are we fairly certain that there are strong welfare considerations?
* What do the terms in the FishEthnoScore mean?
* etc.

### Next steps
1. Scrape data from fishethonase.net/db.
    a. Get a list of all of the fish from the website.
    b. Check if they all have shortprofiles.
    c. Grab shortprofile table from each shortprofile, and grab the title values per shortprofile.
    d. Grab the picture and summary information per species.
2. For each animal, compile information on how many fish per species are farmed per year.
    => Is there a source for this data?