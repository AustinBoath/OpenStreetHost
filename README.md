# OpenStreetHost
Instantly deploy your own self-hosted OpenStreetMap server, with zero technical knowledge required.
## What is OpenStreetMap?

[OpenStreetMap](https://www.openstreetmap.org/) (OSM) is a collaborative, open-source project to create a free, editable map of the world. Much like Wikipedia, anyone can contribute, edit and improve the map.

It's all well and good if you want to contribute to mapping the real world, but OpenStreetMap is still a website with its own rules and conventions. You can't exactly play around with the software and have your own free sandbox.

Well, you can! You just need to set up your own server, and that's where things get tricky.

**OpenStreetHost makes it easy.**

Simply run the executable and deploy your own OpenStreetMap server. No complicated command-line instructions, no manually configuring databases, no messing around with server infrastructure. Just configure everything graphically and get mapping.

Currently, OpenStreetHost is Windows-only. Mac and Linux support are coming. I know, it sucks, but this project was originally packaged just for myself to run on my fast PC.

## Why would I want my own OpenStreetMap server?

OpenGeoFiction went through the process of setting up its own OpenStreetMap server to create a fictional world where contributors could build their own geography.

I also created AlternateGeoFiction for alternative mapping of the real world.

But what if you have your own idea for a map?

What if you want to create a fictional country, an entirely new planet, an alternative version of Earth, or just have your own private mapping environment where **YOU make the rules?**

Now you can!

OpenStreetHost lets you deploy your own mapping infrastructure without needing to know how to configure and administer a server.

## Features

- Deploy your own OpenStreetMap-based mapping environment.
- Graphical configuration instead of complicated command-line setup.
- Create fictional worlds, alternative maps, private countries or whatever else you can imagine.
- Host your own independent mapping community.
- Manage your own server and decide how your mapping environment operates.

## How does it work?

Currently, OpenStreetHost relies on Docker to deploy and manage the underlying software stack.

The goal is to make the entire process as seamless as possible. Ideally, someone with absolutely zero technical knowledge should be able to download OpenStreetHost, configure their instance graphically, launch their server and start mapping.

I'd also like to sever the project's reliance on Docker as soon as possible, moving towards a standalone, bare-metal installation that can run on something more universal than a Windows executable.

## Roadmap

- [x] Initial Windows executable.
- [x] Graphical deployment and configuration.
- [ ] Simplify the deployment process further.
- [ ] Remove Docker dependency.
- [ ] Native Linux support.
- [ ] Native macOS support.
- [ ] Make deployment accessible to users with zero technical knowledge.

## The idea

OpenStreetMap gave us a free, editable map of the real world.

OpenGeoFiction demonstrated that the same concept could be used to build fictional worlds.

OpenStreetHost is about making that infrastructure accessible to everyone.

**Your map. Your server. Your rules.**
