# made-in-america-data

# Description
- This repository contains scripts that pull the public field information from the Forms.gov API, and writes it to a JSON files, as well as another script which converts the JSON into a CSV file. The angular code from the madeinamerica.gov site pulls information from the JSON on demand.

# Branches
- This repo contains two branches active, develop and main. Main is the production branch and should not be written to directly except from valid pull requests that have been tested from develop. Developers should work in the develop branch (or make their own and make PRs to develop)

# CircleCI
- The Develop and Main branches have respective independant CircleCI branches. The one for develop must be "approved" in cicrleCI to run (in a an effort to save run mins), the main branch runs on a schedule, 6am and Noon.