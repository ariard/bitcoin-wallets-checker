## Fee Siphoning Attack

A fee siphoning attack is known to be a class of bitcoin wallet attack,
where an adversary provoke an artifical inflation of the network feerate
seen by the wallet, with the goal of forcing the issuance of high-fees
transactions by the wallet. Those high-fees transactions can then be
sneaked in by a colluding miner to extract a higher fee reward, than
a wallet would have done.

A known variant of this attack has been known e.g to affect Lightning
wallets, for some exploitations sceniaros of the class of attack known
as "dust outputs inflation attacks". For more see:
- CVE-2021-41591
- CVE-2021-41592
- CVE-2021-41593
