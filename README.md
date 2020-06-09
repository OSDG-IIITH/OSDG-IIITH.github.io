Website of Open Source Developers' Group IIIT Hyderabad
=======================================================

Prerequisites
-----------------
- docker ([Instructions for installation](https://docs.docker.com/engine/install/))
- docker-compose ([Instructions for installation](https://docs.docker.com/compose/install/))
- git

P.S. docker by default requires sudo access. Follow https://docs.docker.com/engine/install/linux-postinstall/ to remove that.

Build Instructions
-------------
- Fork the repository https://github.com/OSDG-IIITH/OSDG-IIITH.github.io.git

- Use the following commands to set up.
    ```
    git clone https://github.com/<username>/OSDG-IIITH.github.io.git
    cd OSDG-IIITH.github.io.git
    git remote add upstream https://github.com/OSDG-IIITH/OSDG-IIITH.github.io.git
    docker-compose up --build
    ```
    These commands will serve the website on ```localhost:4000```

Contributing Guide
-------------------
- Always work on a fork of the repository.
- Make a new branch for the feature you add with a descriptive name and make a PR from that to the upstream repository. DO NOT WORK DIRECTLY ON MASTER.
- Before pushing your commits, pull from upstream master to make sure the local repo is up-to-date with changes. This will help avoid merge conflicts.
- Make sure the commits are descriptive and cleary mention which features have been added in the PR.
- Variable and function names should be self-explanatory and always comment your code.
