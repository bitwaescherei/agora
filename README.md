# Welcome to the Bitwäscherei Agora!

This [[Agora]] is maintained by the [Bitwäscherei](https://bitwaescherei.ch) community. It is currently running internally at [agora.init5.ch](https://agora.init5.ch) (and eventually accessible from anywhere at [bit.agor.ai](https://bit.agor.ai)).

# Wait, what's an Agora again?

It's a *Knowledge Commons* maintained by a Community of Practice. In this case, this means the Bitwäscherei community, allied hackerspaces, maker collectives, and friends.

You can think of an Agora as a virtual space for knowledge sharing, cross-pollination, and cooperation towards common goals and interests. It links ideas, notes, wikis, and resources across independent gardens and repositories into a shared graph.

# Contents & Repositories

This Agora currently aggregates and interlinks several community wikis, digital gardens, and knowledge bases:

- **[[Bitwäscherei]]** ([Web](https://bitwaescherei.ch) / [GitHub](https://github.com/bitwaescherei/bitwaescherei)): Notes, wiki pages, and documentation from the Bitwäscherei hackerspace collective in Zürich.
- **[[SGMK]]** ([Wiki](https://wiki.sgmk-ssam.ch)): Schweizerische Gesellschaft für Mechatronische Kunst (Swiss Mechatronic Art Society) wiki.
- **[[Hackteria]]** ([Wiki](https://hackteria.org/wiki)): Open Source Biological Art, DIY biology, open hardware, and citizen science wiki.
- **[[Idiot.io]]** ([Archive](https://wiki.idiot.io)): Internet of Things and open hardware community wiki.
- **[[TAMI]]** ([Archive](https://telavivmakers.org)): Tel Aviv Makers / Makerspace wiki archives.
- **[[Flancian]]** ([Garden](https://github.com/flancian/garden) / [Agora](https://anagora.org/@flancian)): Personal digital garden of Flancian.
- **[[Flancia]]** ([Web](https://flancia.org) / [GitHub](https://github.com/flancian/flancia)): Writing and essays from the Flancia collective.
- **[[Agora Doc]]** ([Stoa](https://doc.anagora.org) / [GitHub](https://github.com/flancia-coop/doc.anagora.org)): Shared Agora documentation and collaborative pads.

# Architecture

An Agora's architecture consists of three main components:

- The *Agora root repository*, which you are browsing: [github.com/bitwaescherei/agora](https://github.com/bitwaescherei/agora). 
  - Contains the high-level configuration of the Agora, including the list of integrated wikis, gardens, and websites ([`sources.yaml`](https://github.com/bitwaescherei/agora/blob/main/sources.yaml)), instance settings (`agora.yaml`), and the community agreement ([`CONTRACT.md`](https://github.com/bitwaescherei/agora/blob/main/CONTRACT.md)).
- The *Agora Server*: [github.com/flancian/agora-server](https://github.com/flancian/agora-server).
  - Reference Python / Flask web application and graph engine that integrates and serves content. The reference Agora is live at [anagora.org](https://anagora.org).
- The *Agora Bridge*: [github.com/flancian/agora-bridge](https://github.com/flancian/agora-bridge).
  - Retrieval and ingestion processes that import content (via Git, MediaWiki API, Wayback Machine, etc.) volunteered by participating projects.

# To join & contribute

If you would like to contribute your notes, wiki, or digital garden to the Bitwäscherei Agora:

- Send a PR adding your source to [`sources.yaml`](https://github.com/bitwaescherei/agora/blob/main/sources.yaml).
- Or reach out to the [Bitwäscherei](https://bitwaescherei.ch) community and tell us what you would like to contribute!

# Contract

***If you contribute directly to an Agora you are assumed to be in agreement with its then current contract.*** 

Please refer to the Agora's [contract](/contract), in particular as posted by the system account @agora.
