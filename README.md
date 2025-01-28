# TRAVIAN KINGDOM MANAGER (TKM)

<b>!!! THIS REPOSITORY CONTAINS ONLY A README OF THE PROJECT. THE SOURCE CODE WITH IT'S CURRENT PROGRESS AND DESCRIPTION CAN BE FOUND 
IN THE PUBLIC GITLAB REPOSITORY <i>https://gitlab.com/green-mesa/travian-manager</i> !!!</b>

*Travian Kingdom Manager* is an Open-Source Bot to semi-automatize any Travian Kingdoms Account
(https://www.kingdoms.com/) and to provide a (for now) basic but fully functional responsive UI layout
for desktop and mobile devices.

Feel free to contact me if you want to contribute to this project!

**ATTENTION**: For now this project is in early ALPHA stage and still under heavy development. If you want to test it 
on your local machine, use the latest feature or main branch. For now, it's too early to provide any release branches.

**ATTENTION**: Currently only Chrome browser is supported!

## Run on your local machine
**ATTENTION**: As soon as I am able to provide a functional release branch I will host this application on a free 
accessible cloud host. But for now this application must be run on a local host if you want to test it by yourself.

In order to run this application, you must provide
- JDK (Java version 18) (Backend)
- *Node.js* for all Angular dependencies (Frontend)
- SQL database with database named *travian_manager*. See file *application.properties*

If you need any help to run it on your local machine, contact me directly (see contact details below)

## Available Features
The bot provides for now the following features

### Account
- Auto-login to lobby and any in-game account
- Overview of all you in-game accounts (lobby view)
- Overview of all upcoming game worlds

### Adventures
- Auto-start of short adventures
- Manual start of short & long adventures
- Notification (push & email) on new adventures
- Overview of all adventures

### Robber Villages
- Notification (push & email) on new robber camps & hideouts
- Overview of all robber villages

## Upcoming Features

### Adventures
- Setting to enable/disable auto-adventures
- Timetable to define when auto-adventures should be done

### Robber Villages
- Auto-attack robber camps & hideouts
  - Define set of troops used for attack

### Building Queue
- Auto-build of resource fields
- Manual & auto-use of chargeable instant finish or NPC merchant
- Auto-finish buildings 5 minutes before ending (free instant finish)
- Extended build queue for resource fields & buildings
  - Put buildings in queue even there are not enough resources yet

### Troop Queue
- Auto-build of troops
- Extended troop queue
  - Put troops in queue even there are not enough resources yet

### Research Queue
- Extended research queue
    - Put troops in queue even there are not enough resources yet

### Merchants
- Auto merchant-routes between villages
  - Infinite route (send resources all the time) or configure routes via timetable or pre-defined amount of resources

### Attacks
- Notification (push & email) on incoming attacks on villages or assigned oasis
- Configurable auto-farm lists

## Contact
If you want to contribute (e.g. doing code work, giving feedback or if you have any new ideas) or if you need help 
hosting this app on your local machine, feel free to contact me either via Gitlab or my email *graf.markus10@gmx.at*
