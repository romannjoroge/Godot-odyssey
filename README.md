# Godot Tutorial

## Introduction to Godot

I've always wanted to make a game and by a stroke of luck I have a game making unit this year. I want to make something like stick fight where I can have multiple players (2 for now) fight as stick characters using goofy guns. The last stick standing wins! It'll then have multiple rounds where the best of all of the rounds is declared the winner.

Interesing I didn't know you can just straight up make applications with Godot..though ut does make sense.

Godot isn't also just a programming language. It feels more like an IDE that includes many tools for writting code, making animations etc

Godot isn't even a language, the language used is GDScript or C#!

Incase I feel like practicing GDScript I can go [here](https://gdquest.github.io/learn-gdscript/?ref=godot-docs)

## Overview of Godot's key concepts

Everything that you work on will live in a tree made up of nodes. These nodes are the basic building blocks in Godot, so maybe it could be things like shapes or something. We combine these nodes into groups called scenes. A player could be a scene for example where we have a circle node for the head, rectangle node for body etc. These scenes can be reusable like menu items or even entire levels. Scenes in GoDot communicate with each other using signals.

It seems like GoDot follows the observer pattern where you have something creating a stream of signals and other things subscribing to that stream and performing an action when an item is sent to the stream. This is how scenes work together. You can combine scenes together as well. (This forms the scene tree)
