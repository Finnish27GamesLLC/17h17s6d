# Application Output

The Blackjack Repository contains the source code for a set of software applications. The set of software applications consists of an ULTIMA282 software application, an ULTIMA283 software application, an ULTIMA293 software application, and a BJ282software application.

This repository contains a set of text files. A set of software applications saved the set of text files. The set of software applications consists of the ULTIMA282 software application, the ULTIMA283 software application, and the ULTIMA293 software application. The following is a description of the data contained in the set of text files.

The set of text files contain data. The data provides the results of math analyses. The math analyses were math analyses of card games. The card games belong to the Blackjack family. Each of the card games is subject to a predetermined set of game rules. In each case, the predetermined set of game rules included the particular subset of game rules. 

The particular subset of game rules does the following. Specifies the step of requiring the dealer to play the dealer's hand in accordance with a predetermined strategy that specifies a target-numerical sum of seventeen for the play of the dealer's hard hands, and a target-numerical sum of seventeen for the play of the dealer's soft hands. Specifies the step of providing six decks of cards. For that reason, the repository is named 17h17s6d.

The ULTIMA282 software application enables the user to program their computer to conduct abbreviated-combinatorial analyses of card games belonging to the Blackjack family of table-card games.

The BJ282 software application enables the user to program their computer to conduct complete-combinatorial analyses of card games belonging to the Blackjack family of table-card games.

ASSEMBLY OF A SET OF COMBINATION-DEPENDENT-PLAYING-STRATEGY TABLES

Both the ULTIMA282 software application and the BJ282 software application prompt the user to input a user-defined set of game rules for a card game belonging to the Blackjack family. Given the user-defined set of game rules, both of the above-described set of software applications assemble a set of combination-dependent-playing-strategy tables. A combination-dependent-playing-strategy table displays the best strategy for the play of the player's hand for each combination of point values that could be assigned to the set of cards consisting of the cards in the player's initial hand and the card dealt face up in the dealer's initial hand.

If the user-defined set of game rules does not give the option to split to the player, then the set of combination-dependent-playing-strategy tables consists of one combination-dependent-playing-strategy table found for the set of hands consisting of the player's primary-initial hand and the dealer's initial hand. If the user-defined set of game rules does give the option to split to the player, then the set of combination-dependent-playing-strategy tables consists of one combination-dependent-playing-strategy table found for the set of hands consisting of the player's primary-initial hand and the dealer's initial hand, and two combination-dependent-playing-strategy tables found for the set of hands consisting of the player's post-split-initial hand and the dealer's initial hand. 

Both of the above-described software application assembles a combination-dependent-expected-value table. A combination-dependent-expected-value table displays the expected value of the best strategy for the play of the player's hand given for each combination of point values that could be assigned to the set of cards consisting of the cards in the player's primary-initial hand and the card(s) dealt face up in the dealer's initial hand.  The combination-dependent-expected-value table displays the expected value of the game.

Both of the above-described software applications save data to a set of files. The data consists of data about the above-described set of strategy tables and data about the predetermined set of game rules. The set of files consists of a set of data files and a set of text files.  The set of text files enables the user to examine the data in written form. The set of data files enables other software applications to load data into program memory. 

ASSEMBLY OF A TOTAL-DEPENDENT-BASIC-STRATEGY TABLE

The ULTIMA293 software application enables the user to load the data into program memory. The software application uses the data to assemble a total-dependent-basic-strategy table for the game. A total-dependent-basic strategy is the best option for the play of the player's hand given the user-defined set of game rules, and given a set of hand totals consisting of the player's hand total and the dealer's hand total. A total-dependent-basic-strategy table provides a total-dependent-basic strategy for each set of hand totals that is possible for the set of hands consisting of the player's hand and the dealer's hand. In a single-exposure game, the set of hand totals that are possible for the dealer's hand consists of all hand totals that are possible for the dealer's up card. In a double-exposure game, the set of hand totals that are possible for the dealer's hand consists of all hard totals that are possible for the dealer's initial hand and all soft totals that are possible for the dealer's initial hand. The set of hand totals that are possible for the player's hand consists of all non-pair-hard totals that are possible for the player's hand, all non-pair-soft totals that are possible for the player's hand, and all pair-hand totals that are possible for the player's hand. 

The ULTIMA293 software application saves data to a set of files. The data consists of data about the above-described set of strategy tables and data about the predetermined set of game rules. The set of files consists of a set of data files and a set of text files.  The set of text files enables the user to examine the data. The set of data files enables other software applications to load data into program memory. 

DESCRIPTION OF TEXT FILES

This repository contains text files saved by the above-described set of software applications. All of the above described set of software applications save text files with a name ending in "i.txt" and text files with a name ending in "o.txt". Both the ULTIMA282 software application and the BJ282 software application save text files with a name ending in "ev.txt". The ULTIMA293 software application saves text files with a name ending in "c.txt".

Text files with a name ending in "i.txt" contain a record of application input. The record of application input includes a record of the prompts for user input made by the software application and a record of user responses to those prompts. 

Text files with a name ending in "o.txt" contain application output. In the case of a software application selected from a group consisting of the ULTIMA282 software application and the BJ282 software application, text files with a name ending in "o.txt" contain a set of tables consisting of a set of combination-dependent-playing-strategy tables and a combination-dependent-expected-value table. In the case of the ULTIMA293 software application, the text file with a name ending in "o.txt" contains a set of combination-dependent-playing-strategy tables. The ULTIMA 293 software application assembles the set of combination-dependent-playing-strategy tables using data about the total-dependent-basic-strategy table. 

Text files with a name ending in "ev.txt" contain a set of tables. The set of tables consists of a table for each combination of point values that could be assigned to a set of cards consisting of the two cards in the player's initial hand and the card dealt face up in the dealer's initial hand. In each of the set of tables, the software application does the following.  Gives the point values assigned the two cards in the player's initial hand.  Gives the point value assigned to the card dealt face up in the dealer's initial hand. Gives the dealer finish probabilities. Gives the percentage of all hands that were accounted for by the complete-combinatorial analysis. Identifies the best strategy for the player's use of the hit option. Gives the expected value of the best strategy for the player's use of the hit option. Gives the expected values of all other options for the play of the player's hand that are permitted by the predetermined set of game rules. Identifies the best strategy for the play of the player's hand.

Text files with a name ending in "c.txt" contain a total-dependent-basic-strategy table. 

DESCRIPTION OF COMPLETE-COMBINATORIAL ANALYSIS

The BJ282  software application performs the task of conducting a complete-combinatorial analysis of a card game belonging to the Blackjack family. Given a predetermined set of game rules; given the combination of point values assigned to a set of cards consisting of the cards in the player's initial hand, and the card(s) dealt face up in the dealer's initial hand; given a strategy for the play of the player's hand; and given a strategy for the play of the dealer's hand; the software application cycles through all combinations of point values that could be assigned to the cards dealt to form a set of hands consisting of the player's complete hand and the dealer's complete hand. For each combination of point values, the software application calculates the product of the probability of the occurrence of that combination of point values multiplied by the resulting return on the game wager. The software application calculates the sum of all products. The sum of all products is the expected value of the strategy for the play of the player's hand. 

The software application cycles through all strategies for the play of the player's hand that have at least a chance of being optimal.  Afterward, the software application compares the expected value of each strategy for the play of the player's hand. The software application uses the comparison to identify the strategy for the play of the player's hand that has the highest expected value. That strategy is the best strategy for the play of the player's hand.

The software application cycles through all possible combinations of point values that could be assigned to a set of cards consisting of the cards in the player's initial hand and the card(s) dealt face up in the dealer's initial hand. For each combination of point values, the software application finds the best strategy for the play of the player's hand; and calculates the product of the probability of the occurrence of the combination of point values multiplied by the expected value of the best strategy for the play of the player's hand. The expected value of the game is equal to the sum of all products. The estimated house edge of the game is equal to the product of the expected value of the game multiplied by negative one.

DESCRIPTION OF ABBREVIATED-COMBINATORIAL ANALYSIS

A strategy for the player's use of the hit option specifies a set of target-numerical sums consisting of a target-numerical sum for the play of the player's soft hands and a target-numerical sum for the play of the player's hard hands. To use any given strategy for the player's use of the hit option, the player does the following. If the player's hand total is less than the target-numerical sum specified for the type of hand the player has, then the player hits. If the player's hand total is at least equal to the target-numerical sum specified for the type of hand the player has, then the player stands. 

The ULTIMA282 software application performs the task of conducting an abbreviated-combinatorial analysis of a card game belonging to the Blackjack family. Given a subset of game rules consisting of; a rule specifying the composition of each deck of cards; a rule specifying the point values assigned to each card; and a rule specifying the number of decks used to play the game; given the combination of point values assign to the set of cards consisting of the cards in the player's initial hand, and the card(s) dealt face up in the dealer's initial hand; and given a strategy for the player's use of the hit option, the software application cycles through all combinations of point values that could be assigned to the cards dealt to form the player's complete hand. For each of the possible combinations of point values that could be assigned to the cards dealt to form the player's complete hand, the software application sorts the combination of point values into a category of player's complete hand; calculates the probability of the occurrence of the combination of point values; and adds said probability to an aggregate total of all probabilities calculated for all combinations of point values that fall into said category of player's complete hand. After the software application cycles through all possible combinations of point values that could be assigned to the cards dealt to form the player's complete hand, the aggregate total of all probabilities calculated for all combinations of point values that fall into said category of player's complete hand is equal to the probability of the occurrence of a combination of point values that falls into said category of player's complete hand. 

Two ways of sorting combinations of point values are by hand total of the player's complete hand and by combination of point values in the player's complete hand. The software application sorts most combinations of point values by hand total of the player's complete hand. The software application sorts the remaining combinations of point values by the combination of point values in the player's complete hand. Sorting some of the combinations of point values by the combination of point values in the player's complete hand makes it possible to calculate the expected value of the game wager should the yet to be completed set of game rules make bonus payouts on any of these combinations of point values available to players. Sorting some of the combinations of point values by the combination of point values in the player's complete hand also makes it possible to calculate the expected value of the game wager should the yet to be completed set of game rules make any of these combinations of point values a predetermined-winning-complete hand.

“Player finish” is the phrase I use to refer to a category of player's complete hand. “Player-finish probability” is the phrase I use to refer to the probability of the occurrence of a particular player finish.  A subset of player-finish-probabilities consists of a player-finish probability for each of a set of player finishes that are possible for the player's complete hand.

The software application cycles through all strategies for the player's use of the hit option that have at least a chance of being optimal. A set of player-finish probabilities consists of a subset of player-finish probabilities for each of a set of strategies for the player's use of the hit option that have at least a chance of being optimal.

The software application cycles through all possible combinations of point values that could be assigned to a set of cards consisting of the cards in the player's initial hand and the card(s) dealt face up in the dealer's initial hand. A database of player-finish probabilities consists of the set of player-finish probabilities for each of the combinations of point values that could be assigned to a set of cards consisting of the cards in the player's initial hand and the card(s) dealt face up in the dealer's initial hand.

A set of databases of player-finish probabilities consists of three databases. The first database is built for the set of hands consisting of the player's primary-initial hand and the dealer's initial hand. The second and third databases are built for the set of hands consisting of the player's post-split-initial hand and the dealer's initial hand. 

A strategy for the dealer's use of the hit option specifies a set of target-numerical sums consisting of a target-numerical sum for the play of the dealer's soft hands and a target-numerical sum for the play of the dealer's hard hands. To use any given strategy for the dealer's use of the hit option, the dealer does the following. If the dealer's hand total is less than the target-numerical sum specified for the type of hand the dealer has, then the dealer hits. If the dealer's hand total is at least equal to the target-numerical sum specified for the type of hand the dealer has, then the dealer stands. 

Given a subset of game rules consisting of; a rule specifying the composition of each deck of cards; a rule specifying the point values assigned to each card; and a rule specifying the number of decks used to play the game; given the combination of point values assign to the set of cards consisting of the cards in the player's initial hand, and the card(s) dealt face up in the dealer's initial hand; and given a strategy for the dealer's use of the hit option, the software application cycles through all combinations of point values that could be assigned to the cards dealt to form the dealer's complete hand. For each of the possible combinations of point values that could be assigned to the cards  dealt to form the dealer's complete hand, the software application sorts the combination of point values into a category of dealer's complete hand; calculates the probability of the occurrence of the combination of point values; and adds said probability to an aggregate total of all probabilities calculated for all combinations of point values that fall into said category of dealer's complete hand. After the software application cycles through all possible combinations of point values that could be assigned to the cards dealt to form the dealer's complete hand,  the aggregate total of all probabilities calculated for all combinations of point values that fall into said category of dealer's complete hand is equal to the probability of the occurrence of a combination of point values that falls into said category of dealer's complete hand. 

Two ways of sorting combinations of point values are by hand total of the dealer's complete hand and by combination of point values in the dealer's complete hand. The software application sorts most combinations of point values by hand total of the dealer's complete hand. The software application sorts the remaining combinations of point values by the combination of point values in the dealer's complete hand. Sorting some of the combinations of point values by the combination of point values in the dealer's complete hand makes it possible to calculate the expected value of the game wager should the yet to be completed set of game rules make any of these combinations of point values a predetermined-winning-complete hand.

“Dealer finish” is the phrase I use to refer to a category of dealer's complete hand. “Dealer-finish probability” is the phrase I use to refer to the probability of the occurrence of a particular dealer finish.  A subset of dealer-finish-probabilities consists of a dealer-finish probability for each of a set of dealer finishes that are possible for the dealer's complete hand.

The software application cycles through all strategies for the dealer's use of the hit option that have at least a chance of being optimal. A set of dealer-finish probabilities consists of a subset of dealer-finish probabilities for each of a set of strategies for the dealer's use of the hit option that have at least a chance of being optimal.

The software application cycles through all possible combinations of point values that could be assigned to a set of cards consisting of the cards in the player's initial hand and the card(s) dealt face up in the dealer's initial hand. A database of dealer-finish probabilities consists of the set of dealer-finish probabilities for each of the combinations of point values that could be assigned to a set of cards consisting of the cards in the player's initial hand and the card(s) dealt face up in the dealer's initial hand

A set of databases of dealer-finish probabilities consists of three databases. The first database is built for the set of hands consisting of the player's primary-initial hand and the dealer's initial hand. The second and third databases are built for the set of hands consisting of the player's post-split-initial hand and the dealer's initial hand. 

After the software application builds a set of databases for each hand, the software application requires the user to complete the predetermined set of game rules. The predetermined set of game rules must include the subset of game rules that was used to build the sets of databases for both hands.  The subset of game rules consists of a rule specifying the composition of each deck of cards, a rule specifying the point values assigned to each card, and a rule specifying the number of decks used to play the card game. The remainder of the predetermined set of game rules can specify any of a nearly limitless number of combinations of game rules. Accordingly, after the software application builds a set of databases for each hand, said sets of databases could be used over and over again to conduct math analyses of a wide variety of card games. 

In a blackjack-like game, the predetermined set of game rules specifies a single strategy for the dealer's use of the hit option. Other rules specify answers to the following questions:  Under what circumstances can the player stand? Under what circumstances can the player hit? Under what circumstances, if any, can the player surrender? Under what circumstances, if any, can the player double down? Under what circumstances, if any, can the player split? Under what circumstances, if any, can the player double down after a split?  

The expected values of strategies selected from a set of strategies consisting of surrender, double down, and double down after a split, are relatively easy to calculate.The difficult expected values to calculate are those involving strategies for the player's use of the hit option. 

Given the predetermined set of game rules; given the combination of point values assign to the set of cards consisting of the cards in the player's initial hand, and the card(s) dealt face up in the dealer's initial hand; given a strategy for the player's use of the hit option, and given the strategy for the dealer's use of the hit option, the software application cycles through all possible combinations of player finish and dealer finish. For each combination of player finish and dealer finish, the software application calculates the product of the probability of the occurrence of the player finish multiplied by the probability of the occurrence of the dealer finish multiplied by the return on the game wager. The software application adds the product to an aggregate total. After the software application has finished cycling through all possible combinations of player finish and dealer finish, the aggregate total is equal to the expected value of the strategy for the player's use of the hit option. 

The software application cycles through all strategies for the player's use of the hit option that have at least a chance of being optimal. Afterward, the software application compares the expected value of each strategy for the player's use of the hit option. The software application uses said comparison to identify the strategy for the player's use of the hit option that has the highest expected value. Said strategy is the best strategy for the player's use of the hit option. 

The software application compares the expected value of the best strategy for the player's use of the hit option to the expected values of any other strategies for the play of the player's hand that are permitted by the predetermined set of game rules. The software application uses this comparison to identify the strategy for the play of the player's hand that has the highest expected value. That strategy is the best strategy for the play of the player's hand. 

The software application cycles through all possible combinations of point values that could be assigned to a set of cards consisting of the cards in the player's initial hand and the card dealt face up in the dealer's initial hand. For each combination of point values, the software application finds the best strategy for the play of the player's hand; and calculates the product of the probability of the occurrence of said combination of point values multiplied by the expected value of the best strategy for the play of the player's hand. The software application calculates the sum of all products. The sum of all products is equal to the expected value of the game. The estimated house edge of the game is equal to the product of the expected value of the game multiplied by negative one.

SPEED AND ACCURACY

Both of the BJ282 software application and the ULTIMA282 software  arrive at an estimate of the house edge. The BJ282 software application does so by cycling through all combinations of point values that could be assigned to the cards dealt to form a set of hands consisting of the player's complete hand and the dealer's complete hand. The ULTIMA282 software application does so by cycling through all combinations of point values that could be assigned to the cards dealt to form the player's complete hand, cycling through all combinations of point values that could be assigned to the cards dealt to form the dealer's complete hand, and then cycling through all of the combinations of finishes that are possible for the set of hands consisting of the player's complete hand and the dealer's complete hand. The number of combinations of point values that could be assigned to the cards dealt to form a set of hands consisting of the player's complete hand and the dealer's complete hand; is far larger than; the sum of the number of combinations of point values that could be assigned to the cards dealt to form the player's complete hand; plus the number of combinations of point values that could be assigned to the cards dealt to form the dealer's complete hand; plus the number of  combinations of finishes that are possible for the set of hands consisting of the player's complete hand and the dealer's complete hand. For that reason, using the ULTIMA282 software application to conduct an abbreviated-combinatorial-analysis of a card game belonging to the Blackjack should be faster than using the BJ282 software application to conduct a complete-combinatorial analysis of the same card game. 

However, whenever the ULTIMA282 software application calculates a value for the probability of the occurrence of a combination of point values that could be assigned to the cards dealt to form the dealer's complete hand, it is assumed that the player's initial hand is the player's complete hand. In other words, it is assumed that the best strategy for the player's use of the hit option calls for the player to stand. If the combination of point values assigned to the cards in the player's initial hand is high enough, then the best strategy for the player's use of the hit option will call for the player to stand. However, in most cases, the combination of point values assigned to the cards in the player's initial hand is not high enough. If the combination of point values assigned to the cards in the player's initial hand is not high enough, and if the dealer's initial hand is not a predetermined-winning-complete hand, then the best strategy for the player's use of the hit option will call for the player to form the player's complete hand by drawing at least one additional card to the player's initial hand. Drawing at least one additional card to the player's initial hand removes at least one additional card from those cards remaining to be dealt. Since the player acts before the dealer, the removal of the at least one additional card from the cards remaining to be dealt changes the probability of the occurrence of the combination of point values that could be assigned to the cards dealt to form the dealer's complete hand.  For this reason, some degree of accuracy is sacrificed in exchange for the speed of using the ULTIMA282 software application to conduct an abbreviated-combinatorial analysis of a card game belonging to the Blackjack family. 

So the obvious questions raised are: How much faster is using the ULTIMA282 software application to conduct an abbreviated-combinatorial-analysis of a card game belonging to the Blackjack family?  How much accuracy is sacrificed? How does that sacrifice of accuracy effect the task of identifying the best strategy for the play of the player's hand. How does that sacrifice of accuracy effect the task of estimating the expected value of each of the best strategies for the play of the player's hand. How does the sacrifice of accuracy effect the task of estimating the house edge of the game?

I have answered these questions to my own satisfaction with the help of the data contained in this repository. 


