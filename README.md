Project name - Real time bidding in online advertising.

This code simulates a simplified real-time bidding auction process. Here's a brief explanation of each class:

Advertiser: Represents an advertiser with a name and budget. The bid method simulates the advertiser's bidding behavior by generating a random bid price.
BidRequest: Represents a bid request with user demographics such as age, gender, and location.
Auction: Conducts the bidding auction among multiple advertisers. The conduct_auction method iterates through each advertiser, collects their bids for the given bid request, and determines the winning advertiser with the highest bid price.
