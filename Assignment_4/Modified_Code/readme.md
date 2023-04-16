These are the modified code needed to get the Hiive and gym working. 

The mdp modifies the code to allow for outputing of various stats for modified PI, as the original PI doesnt allow for epsilon to be varied.

For the frozenlake, it is for changing the rewards for the problem, to impose a penalty of falling into the hole and for walking on surface.

To modify the files, you need to find your python library directory first and then go to the relevant folders as described:

For the mdptoolbox, simply add the mdp file to ./Lib/site-packages/hiive/mdptoolbox

For the frozenlake, simply add the frozenlake file to ./Lib/site-packages/gym/envs/toy_text
