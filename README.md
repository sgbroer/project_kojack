## Project 5 MVP Proposal

### Domain
For Project 5 I plan to examine US non-profit organizations. When it comes do deciding where to donate money and time, what organizations are doing good work, and what organizations are inefficient? Although NGOs are required to submit tax information for public record, it is not always obvious where to get this information or how it compares with other organizations. There are several resources out there for rating charities, including Guide Star, Charity Navigator, and the Better Business Bureau. I have recently done several deep dives into each of these resources and find the information there extremely helpful. There are so many non-profit organizations out there (over 3 million), and I would like to look into the larger patterns of how the non-profit landscape in the US.

### Data
I intend to use data from the propublica [non-profit api](https://projects.propublica.org/nonprofits/api). Here's some of the data that ought to be available for all organizations that I'd like to incorporate: 

Variable | Type
--------|--------
Filing Year | int
Total Revenue| int
Total Expenses | int
Total Assets | int
Total Liabilities | int
% Expenses for Employee Compensation | float
Name | String
Address | String
NTEE Code| String -- National Taxonomy of Exempt Organizations denoting organization type

Further information will be provided for some types or organizations but not others. To start, I plan and focusing on 501(c)(3)s which also include the following:

Variable | Type
--------|--------
Gross Fundraising | int
Fundraising Expenses | int
Compensation of Current Officers, Directors, etc | int
Other Compensation | int

There are some other breakdowns (mostly financial) that I may explore as well. 

### Known Unknowns
The ProPublica API seems fairly simple to work with, so I don't anticipate having to much trouble gathering data, although if I want to get information on all 3 million organizations it may take a while. I don't imagine clustering will be too difficult as it's similar to what I did for NLP but with more interperatable data. I'd like to put together some good (hopefully interactive) visuals for this project so I and others can get a good sense of what's going on, but I haven't done much with any of the tools we've seen so far so that's likely to be a time sink.
