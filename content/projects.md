+++
title = "My Projects"
description = "My Projects"
weight = 1
+++

# [RynBot](https://github.com/LaughLax/RynBot) (Python)

I created and maintained **RynBot** (link to be added), a bot application for Discord using the [discord.py](https://github.com/Rapptz/discord.py) library. Its technical features included:

- Modular design for updates to be deployed without downtime
- **MySQL** database for persistent data storage
- Database structure deployed using [Alembic](https://pypi.org/project/alembic/)
- **Redis** cache to reduce calls to database
- Multithreading and multiprocessing to offload CPU-intensive tasks and keep application responsive
- Self-hosted on a Raspberry Pi 3 running **Debian** Linux

Here are a couple other things I learned about while building it:

- How to use `async` and `await`.
- How to use and create decorator functions (including one to convert synchronous database calls into asynchronous functions).
- Preparing and using a **test environment** to aid smooth deployment

# [Advent of Code](https://github.com/LaughLax/Advent-of-Code) (Python)

Since 2018, I've participated in the annual [Advent of Code](https://adventofcode.com/) (AoC) event created by Eric Wastl. AoC is a set of 25 two-part coding challenges, presented one per day December 1 through Christmas. In 2019 and 2020, I was among the **first 1,000 people** to complete many of the challenges. Several times, I was among the first 100. My completion time and rank for each problem can be viewed at my code repository (linked above).

Here are some skills I used, improved, or learned while completing these problems:

- Selecting the right **data structures** for the problem, such as maps, linked lists, or trees.
- Balancing the need for quick results with writing solid code.
- Preparing a project environment for **rapid development and debugging**.

# [Icarus](https://github.com/gaiwecoor/icarus4) (JavaScript)

I am an active contributor to **Icarus**, a bot application for Discord built on the [discord.js](https://discord.js.org/) library. Icarus provides moderation support and other custom-designed community engagement features. My contributions include:

- Portions of a **major migration/rewrite** from discord.js v12 to v13 (currently in progress).
- Handlers for API events related to uncached objects
- Utility functions used throughout the project
- **Bug hunting** and other polish

While contributing, I also learned about collaborative **Git** workflow tasks such as forking, feature branches, and code review through pull requests.

# [EIA-930-charts](https://github.com/LaughLax/EIA-930-charts) (Python)

I made this collection of scripts to make charts (both interactive and static) from a particular public dataset from the U.S. Energy Information Administration. Here are a few examples of generated charts:

- [Demand in Southwest Power Pool](/SWPP_EIA_930_Demand_Heatmap.png)
- [Generation by source in ERCOT](/ERCO_EIA_930_Generation_Sources.html)
- [Demand ramp in CAISO](/CISO_EIA_930_Demand_Ramp_Heatmap.png)
- [Generation in MISO](/MISO_EIA_930_Generation_Heatmap.png)

# (More projects go here)

(more info goes here)