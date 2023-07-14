# ruleset

0.0 blockspace : extrapolate block data into spatial analogues
0.1 e=mc2 : energy (e) is equal to the velocity (c) of mass (m) exchange squared
0.2 equivalence : each bitcoin parameter should find its natural equal spatial analogue
0.3 blockstep : we observe and resolve commands each block according to ruleset
0.4 resolution : the resolution of each blockstep can be derived by the same ruleset

1.0 district = bitmap block based upon blockheight
1.0.0 district claim command = blockheight.bitmap 
1.0.1 404.bitmap = command to claim district at block height:404
1.1 district claim validation = include only (filter 1.1)
1.1.0 regex =  ^(?:0|[1-9][0-9]*)\.bitmap$
1.1.1 district claim ≤ district claim inscription blockheight
1.2. district owner verification resolution = include only (filter 1.2)
1.2.1 first is first = lowest inscription number of valid claims
