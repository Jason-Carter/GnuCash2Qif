# GnuCash2Qif
Convert GnuCash Sqlite database to QIF format

I've used GnuCash for a number of years and am generally happy with it, although of late I have experienced some frustrations. I would like to update my accounts from an iPad rather than on a full desktop PC, yet there are no good GnuCash iPad applications that I could find, and the closed-garden model of Apple seems to discourage any official port to iOS. Also, from my experience with using other accounts packages, I like the search bar function that filters the transactions in real-time allowing you to focus in on a specific category or type of transaction. The search facilities in GnuCash feel out-dated in comparison, infact the user interface in general is starting to feel a little dated.

With these in mind I thought I would try some other personal finance package to see if they meet my requirements, but was surprised to find a lack of export options, particular for the de-facto QIF standard. 

## To Do

 - Add Unity / DI and Unit Tests (would normally have done this first if it wasn't experimental)
 - Consider a WPF UI (now that MS are supporting it going forward)

## Longer-term Possibilities
These ideas interest me so I might explore them later once this project is mature enough.

 - Is it possible to do this in pure SQL? Was nearly there at the start of this project but merging the double entries proved difficult.
 - Add [journal](https://hledger.org/journal.html) as an output format, so I can explore [Plain Text Accounting](https://plaintextaccounting.org/)
 - Rewrite in functional language (Haskell or Erlang are the ones's I know and would like to learn deeper)
