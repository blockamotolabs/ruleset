# ruleset

- 0.0 blockspace : extrapolate block data into spatial analogues
- 0.1 e=mc2 : energy (e) is equal to the velocity (c) of mass (m) exchange squared
- 0.2 equivalence : each bitcoin parameter should find its natural equal spatial analogue
- 0.3 blockstep : we observe and resolve commands each block according to ruleset
- 0.4 resolution : the resolution of each blockstep can be derived by the same ruleset

- 1.0 district = bitmap block based upon blockheight
- 1.0.0 district claim command = blockheight.bitmap 
- 1.0.1 404.bitmap = command to claim district at block height:404
- 1.1 district claim validation = include only (filter 1.1)
- 1.1.0 regex =  ^(?:0|[1-9][0-9]*)\.bitmap$
- 1.1.1 district claim ≤ district claim inscription blockheight
- 1.2. district owner verification resolution = include only (filter 1.2)
- 1.2.1 first is first = lowest inscription number of valid claims

2.0 parcel claim command = parcel height.district height.bitmap
2.0.0 parcel height = order transaction appears within block (starting at 0)
2.0.1 0.404.bitmap = command to claim the parcel for transaction 0 at block height : 404
2.1.0 regex = ^(?:0|[1-9][0-9]*)\.^(?:0|[1-9][0-9]*)\.bitmap$
2.1.1 parcel height ≤ total number of transactions within block at district height
2.1.2 district holder address = parcel inscriber address
2.2 tap district to resolve all valid confirmed parcel inscriptions
2.2.0 if the parent district is sent to another wallet before tapping to confirm, any parcels created will not be verified
2.2.1 tap = send district to self to confirm previously inscribed parcels
2.2.2 parcel inscriptions remain unverified until the user taps

# phases

0 the bit bang
1  zero to blockout
2 the parcelling
3 ?
