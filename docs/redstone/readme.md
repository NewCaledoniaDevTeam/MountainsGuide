# Redstone Guide

Enhance your redstone knowledge with the help of this guide!

## General Information

### Introduction

#### Welcome to the Redstone Guide!

A Redstone Guide brings you a deeper explanation of how redstone work and how to use it. Every redstone items explain their uses, with the help of this guide it helps you to understand more redstone it has picture to help you understand better. Building redstone mechanism and contraption is done with a step by step tutorial with pictures so you can understand it clearly. It's also have some redstone techniques/tricks, to help you for making your own redstone creation.

#### Work In Progress

This guide is work in progress, that's why some tutorial are still coming soon. Implenting new features/tutorials are gradually added until it reach all features that I plan to implement and also maybe your suggestion will be added too, so expect for more updates. Keep writing your feedback I always listened to anyone's feedback.

### About

#### About this guide

This guide let you teach redstone even if your new player it can help you to understand redstone, the guide provide a picture to let you easily understand it. The guide are categorized into category and section to help Redstone Guide user what are they looking for and providing an organize topic. 

##### Definition category
- This category is just like a "help" section of a guide, it provide an explanation to some words that is related to redstone in case you don't know them.

##### Redstone Components category
- If you are new player and don't know how every redstone components work, then this category help you. The redstone components are divided into different section according to their uses each section explain in their section page what components are listed in this topic and then an explanation to each components.

##### Redstone Tips category
- This category provide a tips to a Redstone Guide user about Redstone it can help you learn and get some tips about redstone.
*NOTE: The Redstone Tips at loading tips message are different from tips in Redstone Tips category.*

There are 3 Major tutorial in this Guide which are Redstone Circuits, Contraption and Mechanism and the following tutorials attempt to categorize that have been useful to the Minecraft community, while this guide describe the specific tutorial of circuits, contraption and mechanism that fall into those categories and sections. And their definition is define in their section.

## Definition

### Circuits

#### What is Circuits?

A redstone circuit is a structure that activates or constrols mechanisms.

Circuits are designed to act in response to player activation or to operate autonomosuly either on a loop, or in response to non-player activity such as mod movement, item drops, plant growth, etc. The mechanisms constrolled by Redstone circuits range from simple devices such as automaic doors and light switches, to complex devices such as elevators, automaic farms, or even in-game computers. Understanding how to controll greatly increases the range of what is possible in Minecraft.

The subject of redstone structures is very broad due to the large variety of Redstone circuits that can be created; this guide provides only an overview of some of the different types of redstone circuits that can be built.

Although the number of ways to construct circuits is endless, certain patterns of construction occur over and over again. The following categories and sections attempt to categorize the circuits that have been useful to the Minecraft community, while this guide describe the specific circuits that fall into those categories.

Some example of circuits in this guide might be used by themselves for simple control of mechanisms, but frequently the player will need to combine theme into more complex circuits to meet the needs of a mechanism.

#### Types of Circuits

* **Transmission Circuit**
    * A transmission circuit is a redstone circuit which allows redstone signals to move from one place to another.
    * Some aspects of signals transmission can be helpful to understand: transmission types, vertical transmission, repeaters, and diodes.
* **Logic Circuit**
    * It's sometimes neccessary to check singals against each other and only output a signal when the inputs meet some criteria. A circuit that performs this function is know as logic gate (a "gate" that only allows signals through if the "logic" is satisfied).
    * There are many different kinds of logic gates, each of which can be implement with many different designs. Each desgin has various advantages and disadvantages, such as size, complexity, speed, maintainace overhead, or cost. The various sections will give many different desgin for each gate type.
* **Clock Circuit**
    * Clock Circuit is a circuit that send an endless signal at specific intervals. It produces a clock signal: a pattern of pluses which repeats itself. The time between the signals can be set by the player, either roughtly or very accurately.
    * Clock circuit is a pluse generator that produces a loop of specific pluses repeatedly. Some are designed to run forever, while others can be stopped and started.
* **Memory Ciruit**
   * Latches and flip-flops are effectively 1-bit memory cells. They allow circuits to store data and deliver it at a later time, rather than acting only on the inputs at the time they are given. As a result of this, they can turn an impluse into a constant signal, **turning a button into a level**.
   * Devices using latches can be built to give different outputs each time a circuit is activated, even if the same inputs are used, and so circuits using them are referred to as **sequential logic**. They allow for the design of counters, long-term clocks, and complex memory systems, which can not be created needs to behave differently depeding on previous inputs.
   * There are several basic cateogires of latches, distinguished by how they are controlled. For all types, the input lines are labeled according to thier purpose (Set, Reset, Toggle, Data, Clock). There are also more arbitarty labels: The ouput is commonly labeled **Q** for historical reasons. Some there is also an **inverse output** labeled as **Qi**, which is always ON when **Q** is OFF and vice versa. If both **Q** and **Qi** are available, we say the circuit has **dual outputs**. Most of the following types can be built as a **latch** that responds to the level of a signal, or as a **flip-flop** triggered by a change in the signal.
      * *NOTE: Actually **inverse output** labled as diabritic maron Q, it is a diacritic character which has line above the letter, we can't use it everyone like here. So lets use **Qi as labeled instead**.

### Properties

#### Size

Size describes ciruit size (the volume of the rectangular solid it occupies) with the notation of the shorter width, longer length and height, including support/floor blocks, but not including inputs/outputs.
