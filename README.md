Example of using the Regtest CI workflow to
start a local Zebra and Zaino on Regtest.
The workflow mines a few hundred ZEC
and shields 10 blocks worth of reward to a destination
wallet address (~62 ZEC).

The workflow requires:
- `MINER_SEED`: the seed phrase of the address that receives
the mining rewards
- `MINER_ADDRESS`: its associated transparent address
- `SEED`: the seed phrase of the destination (shielded coins)
- `DESTINATION_ADDRESS`: the associated address (must be
shielded)

Example:

```
    MINER_SEED: "burger voice warrior danger satoshi you solid atom elite alcohol category layer able debate culture talk tissue language hip surge fiction paddle stove voyage"
    MINER_ADDRESS: "tmQ1BiNRfsvT6eMkJ5n7nMZsbz1PGwCs1Zs"
    SEED: "invite couch cloud pave stuff cabbage usual rigid dragon warm cable price fame warfare next swallow worth opera suggest flame patch undo position arctic"
    DESTINATION_ADDRESS: uregtest1ur83jamvhc5pwe8xzlu9d8ur4mxmny385mhlurxh5z00e6vhcf9zk0dncar334n0ucskdya9ytdrvzucprqjrhy7hd6rkklp0q6eyxp5
```

