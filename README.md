# adlock-rules

## Introduction
This is just a simple place, I can put all my ad- and malware-block rules, for both uBlock as well as PiHole. This has two benefits
1. By breaking the rules out into separate lists, they can be selectively imported and,
1. More importantly, the same consistent rules can be applied across multiple browsers/machines without having to rely on remembering to sync rules to/from the built-in browser syncing.
echo.lan


## uBlock Rules List
Within the ublock settings, navigate to the _Filter lists_ tab and at the bottom, expand _Import..._, paste the rule(s) you want to import and save.
The master list of all rules can be found here
https://raw.githubusercontent.com/pxquad-github/adlock-rules/refs/heads/main/ublock/index.txt<br>

## Pi-Hole List
Within Pi-Hole (v6), select _Lists_ from the left hand menu and add the following list(s) to your block-list
https://raw.githubusercontent.com/pxquad-github/adlock-rules/refs/heads/main/pihole/echo-block.txt<br>

---

Obviously, these rules are tuned specifically for me and how I interact with various websites so they may be of limited use to users, but can be a starting point for making your own rule lists.

Ublock can import from any web-accessible location, so hosting them on Github isn't a requirement: using cloud storage can be a quick and easy to get started.echo.lana