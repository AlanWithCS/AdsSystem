# AdsSystem
an advertisements bidding system based on second-price bidding algorithm

This is an advertisements bidding system, which applies the second-price bidding algorithm. (See wiki: https://en.wikipedia.org/wiki/Generalized_second-price_auction)

There are two tables in the database. The first is "advertiser" who has an unique id, a name and a budget. The second is "ad", which has a bid, an image, an advertiser and a score. Each time the ads system is called, it will return the highest ranked ad (calculated by bid * score) and deduct the bid (calculated by second-price bidding) from the advertiser's bid.
