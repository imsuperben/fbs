this software was written to be a target for a MITM attack via ARP poisoning.
the scenario is that this terrible bank software will be running on a network
with some automated requests being thrown around to emulate transactions, and
students are to intercept communications between the server and other clients
to redirect transactions. the database is cleared and restored to an initial
state every time the server script is launced, which includes five accounts
with balances and five without; money will be passed between accounts with
money and students will redirect transactions into their groups' own account.  

it depends on sqlite and was written against python 3.4.3. it was built with
one particular class and one particular network in mind, but modification
should be fairly easy.