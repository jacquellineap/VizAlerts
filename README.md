## What is it?

VizAlerts is a data-driven email notification and bursting platform for Tableau Server. It allows any user to author dashboards that will send email alerts to any audience based on any criteria you can define in your viz. Once VizAlerts is installed and running, all of the work to build and manage your alerts happens in Tableau--no scripting required, and no separate interface necessary.

## Got any documentation?

Do we ever! There are two files included in the root folder, install_guide.docx and user_guide.docx, intended for Tableau Server administrators and for alert authors, respectively. They're the best way to learn about what VizAlerts can do.

## How do I set it up?

Please see install_guide.docx for installation instructions. Only the Tableau Server administrator needs to set it up. Once working, any user on Tableau Server who can publish may use VizAlerts.

## What versions of Tableau are supported?

Tableau Server version 8.2.5 and higher is required (ideally version 9--if you're using version 8, some things won't work as well). Tableau Online is not currently supported, though we are looking at ways we might be able to achieve that.

## How is it licensed?

Please see the LICENSE file in the root path for details.

## Is VizAlerts supported?

VizAlerts is made available AS-IS. While Tableau's Professional Services team may be engaged to assist with the deployment and usage of this tool, VizAlerts is not officially supported by Tableau Software: It is a community-built and community-supported tool.

For general questions or issues, please bring them to the [VizAlerts Group](http://community.tableau.com/vizalerts) created on the Tableau Community site.

Bugs discovered, and feature aspirations will be tracked via GitHub's [issue tracker](https://github.com/tableau/VizAlerts/issues).

## How can I contribute?

If you're interested in contributing to VizAlerts, please [email Matt](http://tinymailto.com/a65f) about what you're interested in doing. We've found it's the easiest way for us to coordinate planned changes amongst ourselves.

## What's the longer-term vision for this tool?

Initially, VizAlerts was born out of a hackathon we held at Tableau, and it was conceived of as a proof-of-concept of how data analyzed through Tableau could be used as a programming language of sorts to drive automation of various tasks. The most critical and simplest task to tackle first was email automation, so that's what has been focused on to date. But in the future, we're interested in finding other ways that VizAlerts can be used to drive automation of other types of tasks, such as sending text messages, exporting data to file shares, making changes to other content on Tableau Server, and generally hooking into APIs exposed by various other third-party services.
