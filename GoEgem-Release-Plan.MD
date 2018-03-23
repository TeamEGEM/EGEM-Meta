Go EGEM Production test runs:
Test run number 1:
PreEra0 	[ ] block reward 9
Era0 		[ ] dev fee transition [ ] miner reward transition [ ] difficulty transition
Era1		[ ] dev fee transition [ ] miner reward transition [ ] difficulty transition
Era1a 		[ ] dev fee transition
Era2 		[ ] dev fee transition [ ] miner reward transition [ ] difficulty transition
Era 2a 		[ ] dev fee transition
Error: i had the 0.25 dev reward in the 0.75 one

Test run number 2:
PreEra0 	[ ] block reward 9
Era0 		[ ] dev fee transition [ ] miner reward transition [ ] difficulty transition
Era1 		[ ] dev fee transition [ ] miner reward transition [ ] difficulty transition
Era1a 		[ ] dev fee transition
Era2 		[ ] dev fee transition [ ] miner reward transition [ ] difficulty transition
Era 2a 		[ ] dev fee transition


GO EGEM Production Code Readiness review:
[ ] diff check block difficulty transition numbers correct
[ ] diff check the genesis block changes
[ ] diff check the port number changes are correct


GO EGEM Compile production executable for release:
[ ] Post release audit of code
[ ] Contingency plan hard fork if errors discovered after release

Opal Wallet Production Test Runs:
[ ] Install instruction set working
	[ ]Windows
	[ ]Mac
	[ ]Linux
Problem Reports and fix testing this release:
PR 1:
a)	[ ] bug fix for delete all wallets leaves delete and export buttons showing
b)	[ ] Items in database still available on export when condition a is triggered

[ ] PR1 Bug fix 
[ ] General Wallet Functions (all below)
---------------------
[ ] Add wallet address and hit account wallet address displays in top area
[ ] Update price of wallet address
[ ] tick the checkbox left of wallet address export/delete buttons show
[ ] untick the box and export/delete buttons hide
[ ] export works
[ ] delete works
[ ] add multiple wallet addresses
-----------------------

