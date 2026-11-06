(I didn't check if it displays well on Github, though it should be good locally with `cat ARCHI.md | less`

```

    1.1

    -----------------
    |               |
    | existing spec |-------------|
    |               |             |
    -----------------             |
                                  |
    1.2                           |
                                  |
    ---------------------         |         2.                                          4.                      5.
    |                   |         |
    | vuln encyclopedia |---------|             ----------------------------             -----------------         --------------
    |                   |         |             |                          |             |               |         |            |
    ---------------------         |             |  specification of        |------------>|  wallet model |-------->|    Rocq    | 
                                  |------------>| an abstract wallet model |      |      |    proofs     |         |  checker   |
    1.3                           |             |                          |      |      |               |         |            |
                                  |             ----------------------------      |      -----------------         --------------
    -----------------------       |                                               |
    |                     |       |                                               |
    | LLM-generated specs |-------|                                      3.       |
    |                     |       |                                        -------------------
    -----------------------       |                                        |                 |
                                  |                                        |  wallets girdle |
    1.4                           |                                        |                 |
                                  |                                        -------------------
    ----------------------        |
    |                    |        |                     
    |   human-authored   |--------|
    | security analysis  |  
    |                    |
    ----------------------

