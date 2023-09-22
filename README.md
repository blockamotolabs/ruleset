# ruleset

- 0.0 blocktime = blockspace
- 0.1 e=mc2 : energy (e) is equal to the velocity (c) of mass (m) exchange squared
- 0.2 equivalence : each bitcoin parameter should find its natural equal spatial analogue
- 0.3 blockstep : we observe and resolve commands each block according to ruleset
- 0.4 resolution : the resolution of each blockstep can be derived by the same ruleset

- 1.0 district = bitmap block based upon blockheight
- 1.1 district claim command = blockheight.bitmap
- 1.2 404.bitmap = example command to claim district at block height:404
- 1.3 regex validation =  `^(?:0|[1-9][0-9]*)\.bitmap$`
- 1.4 district claim < district claim inscription blockheight
- 1.5 first is first = first valid inscription transaction on block

- 2.0 parcel# = index number of transaction to be inscribed as parcel, starting at 0
- 2.1 parcel claim command = parcel#.blockheight.bitmap
- 2.2 0.404.bitmap = example command to claim the parcel for transaction 0 at blockheight : 404
- 2.3 regex = `^(?:0|[1-9][0-9]*)\.(?:0|[1-9][0-9]*)\.bitmap$`
- 2.4 parcel# >= 0 and < total transactions in parent block
- 2.5 district holder address = parcel inscriber address (initiates staking of district)
- 2.6 tapping = send to self
- 2.7 tap district to resolve all confirmed parcel inscriptions as valid/invalid (ends staking)
- 2.8 if the parent district is sent to another wallet before tapping to confirm, any parcels created will not be verified (interrupted staking)
- 2.9.0 tap = send district to self to confirm previously inscribed parcels
- 2.9.1 parcel inscriptions remain unverified until the user taps

# phases

- 0 the bit bang
- 1  zero to blockout
- 2 the parcelling
- 3 ?
