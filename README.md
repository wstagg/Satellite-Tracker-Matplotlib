## Python packages required
- matplotlib
- cartopy
- scipy
- certifi

 ## How to use
Requires OrbitFetcher with python bindings.

Copy and the OrbitFetcher.dll/OrbitFetcher.so, (all other required .dlls from OrbitFetcher build dir if on Windows) and orbitFetcherConfig.txt.

This is a simple satellite tracker. It calls the N2YOs "whats above" API to get up to 80 satellites above the observer location (depending on search radius) allong with the ISS.
