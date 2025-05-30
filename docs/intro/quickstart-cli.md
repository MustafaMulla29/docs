---
title: Quickstart CLI
sidebar_position: 4
---

## Overview

The command line is the best way to use tscircuit. Using the CLI, you can just
run `tsci dev` in a project and see previews of your circuit just like any
other local development tool!

<iframe width="560" height="315" src="https://www.youtube.com/embed/faW4-M91rQQ?si=H2uTflEDGnYummzm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Install the tscircuit CLI

You can install the tscircuit CLI by running `npm install -g @tscircuit/cli`.

## Create a new Project

First, create a new tscircuit project by running `tsci init`. This will create a new directory with all the necessary files to get started:

![tsci init result](../../static/img/tsci-init.png)

## Run the Development Server

Next, start the development server by running `tsci dev`. This will start a local server that automatically rebuilds your circuit when you make changes:

![tsci dev result](../../static/img/tsci-dev.png)

Go to https://localhost:3020. You'll can now see PCB, Schematic and 3D views of your circuit, which update in real-time as you make changes to your code.

![browser](../../static/img/pcb-runframe.png)

## Pushing to the tscircuit Registry

<!-- TODO -->

This section is coming soon!

## Exporting to SVGs, PDF, or Fabrication Files

<!-- TODO -->

This section is coming soon!
