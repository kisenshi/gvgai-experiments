# GVGAI experiments

Code used for the experiments run in the GVGAI framework, duplicated in order to have everything in a same place and do not interfere with the main code of the repository

The original code of the framework used can be found at https://github.com/EssexUniversityMCTS/gvgai It has been duplicated in this repository for clarity purposes; please refer to the original code for detailed information about it and about the GVGAI competition. Note that the repository is now obsolete, as it has been migrated to https://github.com/GAIGResearch/GVGAI.

## Diversifying Heuristics

The experiments are related with heuristic diversification and the original Framework has been enlarged to add methods to be able to run them, as it was necessary to provide a common ground for the comparison of both the algorithms and the heuristics. These functions are based on the ones already available in the Framework, but allowing to provide the heuristic to be used by the agents separately. Also, it has been included the code needed to create heuristic-independant players.

The code added to the Framework can be found at _src/ExperimentValFunction_ folder and new functions included at the end of the _src/tracks/ArcadeMachine_ file

**Note** that the updates at the moment only apply to single-player games and it would be needed to make some updates to be able to use the heuristic differentiation in 2-player games.

