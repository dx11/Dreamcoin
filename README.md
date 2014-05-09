
Dreamcoin development tree

Dreamcoin is a PoW/PoS-based cryptocurrency.

RPC Port: 14553
P2P Port: 14551

Algorithm: X11 POW/POS

Short: DRM

Total coin: ~3.5 Million with PoW

Block reward: Start at 500 and drop to 100 coins per block:

 Reward-----Blocks
 
 500        500
 
 250        1500
 
 350        3500
 
 100        10000 
 
POW last: 10000 ~7 days

POS generate after 8000 block

Block time: 60 seconds

POS Min age: 8 hours

POS Max age: Unlimited

Difficulty Readjusts every block

Confirmations on Transactions: 10

CoinBase Maturity: 50

Stake interest: 15% per year

Development process
===========================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
stable release versions of Dreamcoin.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'.
