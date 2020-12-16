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
      * *NOTE: Actually **inverse output** labled as diabritic maron Q, it is a diacritic character which has line above the letter, we can't use it everyone like here. So lets use **Qi as labeled instead**.*

### Properties

#### Size

Size describes ciruit size (the volume of the rectangular solid it occupies) with the notation of the shorter width, longer length and height, including support/floor blocks, but not including inputs/outputs.

Another method used for describing ciruit size in the Minecraft commmunity is to ignore non-redstone blocks simply used for support (for example, blocks under redstone dust or repeaters). However, this method is unable to distingush between flat and 1-high circuits, as well as some other circuits differences. But in this guide it describe the size of which includes suppport blocks.

Sometimes it is convenient to compare ciruits simply by the area of their footprint (e.g., 3X4 for a circuit three block wide by four blocks long), or by a single dimension important in a particular context (e.g., length in a sequence of sub-circuits, height in a confined space, etc.).

#### 1-High

A structure is 1-high (aka "1-tall") if its vertical dimension is one high (meaning it can not have any redstone componets that require support blocks below them, such as redstone dust or repeaters). Also see flat.

#### Flat

A structure is flat if it generally can be laid out on the ground with no components above another (support blocks under redstone components are okay). Flat structures are often easier for beginners to understand and build, and fit nicely under floors or on top of roofs. Also see 1-high.

#### Hipster

A structure is hipster if no redstone components are visble both before and after it completes its task (but it's okay if some are visible during operation). Also see flush and seamless.

#### Instant

A structure is instant if its output responds immediatley to its input (a circuit delay of 0 ticks).

#### Seamless

A structure is seamless if it is initially hidden behind a flat wall, floor, or ceiling and can still provide utility to the other side. Seamless is a desirable design goal for piston-extenders, piston door, etc. Also see flush and hipster.

#### Stackable

A structure is stackable if it can be placed directly next to other copies of itself, and they all controlled as a single unit. Also see tileable.

#### Tileable

A structure is tileable if it can be placed directly next to other copies of itself, and each copy can still be controlled indepently. Also see stackable.

Structures might be described as "2- wide titleable" (tileable every two spaces in one dimenosion), or "2X4 tileable" (tile in two directions), etc. Some structures might be describe as **alternating tileable**, meaning they can be placeed next to each other if every other one is flipped or a slightly different design.

#### Other

Other design goals may include reducing the delay a sub-ciruit adds to a larger circuit, reducing the use of resource-expensive components (redstone, nether quartz, etc.), and re-arranging or redesigning a ciruit to make it small as possbile.

### Redstone

#### Redstone Components

Redstone Components are the blocks used to build redstone structures, such as Transmission Components, Power Componets, Mechanism Compnents including Mobile Components and Miscellaneous Components, these are every items/blocks use in redstone structure.

#### Redstone Contraption

These are the basic, modular parts which can be combined to form any complex mechanism, these are already redstone structure but it's just some part of the mechanism, for example is circuit it doesn't do anything yet combining it into another redstone structures.

#### Redstone Mechanism

Mechanisms are complex system of blocks used to perform certain tasks, such as opening a door from afar or revealing a hidden staircase. These systems are built from simple components and normall involve some kind of user input, such as breaking a torch, which generates some kind of result, like a door being revealed. Mechanisms can range from simple switches that open and close doors from a safe distance, to complex devices such as combination locks that prevent intruders from entering your fort.

### Block Label

This section gives a basic overview of the new style of redstone schematics. These schematics represent a block uses in tutorial. Contraption represented in different blocks, allowing you to easily understand it.

Most blocks in a redstone ciruit are **generic**, in that any of serveral solid blocks will do. Therefore, they are shown as blocks chosen for visibility, rather than what you'd normally choose to build a constraption.

#### Block Label

IMAGE

- **Block of Quartz** is the ground of constrapation, here where contraption is placed.
- **Block of Gold** represents as generic opaque block which are required by the contraption. It can be replaced by any opaque block which are required by the contraption. It can be replaced by any opaque blocks except falling blocks and/or non-movable blocks.
   - Translucent Block of Gold shows what's beneath or what's beyond in this block.
- The colored blocks except for light blue shows the input and output location of the contraption.
- **Red** is for Input, **Pink** for secondary Input, and **Lime** is for Output. These maybe labelled differently if there is more than one input or output.
   - The secondary Input (Pink) may had had a different purpose depending on the ciruit, what will be mentioned in that section.
- A components with arrow shows it's direction where this block is facing at, a hopper with arrow shows where it is connected, if they are already visible where they are facing or already obvious if doesn't need to have an arrow anymore.
- **Blue** Block is the border of contraption, it doesn't need in contraption, just showing it's dimension. It doesn't need to replace with any block or require to be there.

## Redstone Components

### Tranmission Components

Transmission components propagate signals and pluses from power components to mechanism components. Complex effects can also be produced by allowing a signal to affect itself or its ciruit.

#### Redstone Dust

The easy way to understand how redstone dust work is simply just like as wire in real life. From the source wire is need to connect to bulb to turn it on. Redstone dust works exactly like this, from the source of redstone signals (see Power Components section), you will need to connect signals from power components to mechanism components to make them act or toggle..

Redstone are came from redstone ore when mined and it called redstone dust (also known as redstone wire) when it placed on the ground. So the redstone is item and redstone dust is a block.

Redstone signal can reach up to 15 blocks long from the source, while it's farer from source, signal, or power of redstone is lower or weaker.

#### Redstone Repeater

Redstone Repeaters can extend the current of a redstone dust beyond the 15 blocks limit, this makes a weaker signal turn into a strongest signal. It can also use to delay, the minium is 1 tick and maximum of 4 ticks. The more ticks the more delay is, 1 ticks is equal to 0.1 second delay.

See the picture below the model of repeater.

IMAGE

Redstone Repeater has secondary function which you can lock the repeater, can be done using two repeaters. If you place a repeater facing at side input repeater will locked. A locked repeater can not change its state. See picture below.

IMAGE

In picture A the input is ON and it's work as normal, when its side input is turn ON the repeater will lock as you can see in picture B the repeater has dark line that replace the adjustable small torch in it symbolizes that repeater is locked. So now it is lock the states of a repeater can not be change, in picture C you can see its input is already OFF but the output stays ON. In picture D both side input are OFF and when you ON its side input first (see picture E) it's output will stay OFF and when you ON its side Input is ON or not. As you can see in Picture F the output is OFF even its input is ON because repeater is off when it was lock.

*Note: On the side input of Redstone Repeater can only accept is the power of Redstone Repeater only to lock it*

#### Redstone Comparator

A redstone comparator is the most complicated redstone components, it has four uses. The use of it are to maintain signal strength, to compare signal strength, to subtract signal strength, and to measure certain block states (primarily the fullness of containers).

The redstone comparator has a front and a back, the arrow on the top of the comparator points to the front. When placed, the comparator will face away from the player. The comparator has two little redstone torches at the back (input) and one at the front (output). The front torch has two states which can be toggled to switch between states.

IMAGE

First State: If redstone torch is off, redstone comparator is in "Comparison Mode".

Second State: If redstone torch is on, redston comparator is in "Substraction Mode".

##### Maintain Signal Strength

A redstone comparator with no powered side inputs will simply, output the same signal strength as its rear input. If weak signal that was sent to the rear of redstone comparator it's output is also weak as same strength as its input.

##### Compare Signal Strength

If torch in front is off, a redstone comparator is in comparison mode. Redstone Cimprartor in comparison mode will compare rear input to its two side inputs. If comparator output turns off. If neither side input is greater than the rear input, the comparator simply outputs the same strength as its rear input. (see image below)

IMAGE

- In the First Sample: B redstone signal is stronger than A therefore there is no output, C is off.
- In the Second Sample: B redstone signal is weaker than A therefore there is output, C is on. It's output is the same strength to it's rear input

##### Subtracting signal strength

If torch is front is on, a redstone comparator is in substraction mode. Redstone Comparator in subtraction mode will subtract the signal strength of the highest side input from the signal strength of the rear input (minimum 0 signal strength).

The signal strength in input minus from signal strength in side input, the answer is the amount of signal strength of output.

##### Measure Blocks State

A redstone comparator will treat certain blocks behind it as power sources and output a signal strength proportional to the block's state. The comparator may be separated from the measure block by an opaque block.

**Containers** - A redstone comparator used to measure the state of a container outputs a signal strength in proportion to how full the container is. The more items inside the strongest the output signal is.

**Cauldron** - A cauldron outputs different signal strengths depending on how muchh water is inside. From completely empty to completely full, the outputs values are 0, 1, 2, and 3. If fill with lava output is level 3, though the lava in cauldron is always full can't partially taken unlike water.

**Cake** - A cake outputs a signal strength relatice to the amount of cake remainging. Each slice is worth 2 signal strength, with 7 total slices, for an output of 14 for a full cake.

**Jukebox** - A jukebook outputs a signals strength which indicates which record is currently playing. For whioc records produces which signal strengths. Each disc has an equivalent of different signal strength.

**End Portal Frame** - An end portal frame outputs a full signal of 15 if it contains an eye of ender and zero otherwise.

**Item Frame** - A comparartor can measure the state of an item frame's contents. In order for a comparator to measure an item frame's contents, it must be placed behind the block the item frame. An item frame comparator will output 0 if the item frame is empty. 1 to 8 for any item depending on its rotation (1 at initial placement, plus 1 for each rotation to a maximum of 8, then wrapping back to 1).

**Command Block** - If a last command successfully execute at command block then the comparator will turn on, that gives signal.

### Power Components

Power components create redstone signals, either permanently or in response to player, mob, and environmental activity.

#### Lever

A lever is a switch which you can use to power any adjacent redstone dust (including beneath the lever) to power level 15, it powers any adjacent redstone comparator or redstone repeater facing away from the lever (must be place on input) to power level 15. Strongly powers its attachment block is a full solide opaque block (see miscellaneous components section). Activates any adjacent mechanism components, including above or below, such as piston, redstone lamps, etc/

While the lever is on, it keeps redstone components active until you turn it off.

#### Button

A button can be used as a monostable power source, it will automatically deactivate shortly after being activated. It has 2 kind of button, wooden (any wooden button) and stone button.

Wooden can activate by fired arrow while arrow is stucked at button, it keeps push it keeps active redstone components. Unlike stone button it can't able to push by fired arrows.

#### Pressure Plates

A pressure plate send a redstone signals when an entity is on top of it, it keeps power redstone components while there is an entity on top of it and when entity gone, it stop to power redstone. There are four variant of it. Wooden, stone, light weighted (gold) and heavy weighted (iron).

**Wooden Pressure Plate** - Can detect all entities (includes drop items & fired arrow), giving out a maximum signal strength.

**Stone Pressure Plate** - Can only detect players and mobs, giving out a maximum signal strength.

**Light Weighted Pressure** Plate - Can detect all entities. The signal strength increases as more entities are added.

**Heavy Weighted Pressure Plate** - Similar to a light weighted pressure plate but requires much higher quantities to be activated.

#### Redstone Torch

A redstone torch powers circuits (horizontally and vertically), and can invert signals.

A redstone torch turns OFF when its attachment block receives power from another source and turn back on when the block loses power.

While activated, a redstone torch and any opaque block above it both power adjacent redstone dust (including beneath the redstone torch, or on top of the block), and all adjacent mechanism components (including those above or below it). They also activate all adjacent redstone comparators or redstone repeaters facing away from it.

A redstone torch does not affect the block it is attached to, even if it is a mechanism component.

#### Observer

Observer can place in any direction, it emits a redstone signal when an adjacent block (output) is updated such as placing blocks, breaking blocks, growth of crops, door, trap door & fence gate that will open/close, when redstone dust powered/unpowered or changes it's power level, when adjusting repeater or powering/unpowering repeater, It's also send signal when push or pull by pistons or it's detect the arm of pistons, etc.

#### Daylight Sensor

Daylight sensors are used to detect time of day in Minecraft by measuring the level of daylight, then emitting a redstone current equal to the strength of the light. It can also be toggled to switch to night sensor (night mode). So of course if its on night mode the night time will it detects, it will emmits signal current equal to the strength of night.

#### Tripwire Hook

A tripwire hook is used to detect mobs, items, and other entities in an area where tripwire line is placed.

A tripwire hook can attached to the side  of blocks. In order to function correctly, a tripwire hook must be part of a "tripwire circuit": a two tripwire hook place facing each other with a tripwire line between them.

While activated, a tripwire hook and its attachment block both power any adjacent redstone dust (including below the tripwire hook, or beneath or above the block), and all adjacent mechanism components (including those above or below it). They also activate all adjacent redstone comparators or redstone repeaters facing away from it.

IMAGE

#### Block of Redstone

A block of redstone provides constant power. It can be moved by pistons.

A block of redstone powers adjacent mechanism components (including those above or below) and adjacent redstone dust. It also powers adjacent redstone comparators or redstone repeaters facing away from it and turns off redstone torch attached to it.

A block of redstone has no effect on adjacent opaque blocks.

#### Jukebox

A jukebox is a block used to play music discs.

While disc is playing in jukebox, it powers any adjacent mechanism components (including above or below) and adjacent redstone dust. It's also powers redstone repeater or redstone comparator facing away from it and turns off redstone torch attached to it.

A jukebox has no effect on adjacent opaque blocks.

#### Detector Rail

A detector rail is used to detect the passage of a minecart

A detector rail turns ON when a minecart passes over it, and turns OFF when it leaves.

While activated, a detector rail and its attachment block (unless attached to a slab or stairs) both power adjacent redstone dust (including beneath the block), and all adjacent redstone comparators or redstone repeaters facing away. They also activate all adjacent mechanism components (including those above or below).

#### Trapped Chest

A trapped chest can be used to detect when a player tries to take from it or open it.

While trapped chest is open, a trapped chest and any opaque block beneath it both power adjacent redstone dust (including beneath the block), and all adjacent mechanism components (including those above or below it). They also activate all adjacent redstone comparators or redstone repeaters facing away from it, at a power level equal to the number of players simultaneously accessing its contents (maximum 15).

### Mechanism Components

Mechanism components are blocks which react to redstone power by affecting the environment; by moving themselves or other entities, by producing light, sound, or explosions, etc.

#### Door and Trap Door

A door & trap doors can be used as a switchable barrier to entity movements. There are two types of door & trap doors a wooden door & wooden trap door (all wood types) and iron door & iron trap door.

A wooden door/trap door can be opened and closed by redstone power or by a player and villager, while an iron door can only be opened and closed by redstone power.

#### Pistons

A piston is a block capable of pushing movable blocks when given a redstone signal, it can also pushed any entities.
- Pistons are always placed facing towards the player. When powered, the piston's wooden surface (head) will start extending immediately, and push at most 12 blocks.
- When a piston loses power, it will retract by simply pulling its head back.

There are two types of pistons: Piston (normal piston) and Sticky Piston.
- **PISTON:** A normal piston can pushed a blocks when powered by a redstone but cannot pull the block.
- **STICKY PISTON:** When powered it pushes a blocks and when unpowered it pulls the block.

#### Dropper

Dropper can be used as a container and can be used as redstone contraption, it used to drop or to eject item inside it, it can also be used to move items inside it into another container where it facing at. Every redstone pulse it's receive it eject one item. It doesn't continue ejecting while it's activated.

If you want to make dropper continues ejecting items you should need to power it by a clock circuit.

#### Dispenser

Dispenser can be used as a container and as a redstone contraption which dispense an item when activated, with results varying on the item dispensed. Every redstone pulse it's receive it dispense one item. It doesn't continue dipensing while it's activated.

If you want dispenser continues dispensing items you should need to power it by a clock circuit.

Dispenser can dispense the following items:

- Armors, Elytra, Heads
   - Equips on a player or armor stand within the block the dispenser is facing with empty appropriate armor slot
- Carved Pumpkin, Wither Skull
   - Placed as blocks. If placement completes the construction of an iron golem, snow golem, or wither, the entity will be created as if constructed by a player.
- Arrow, Tipped Arrow
   - Fired in the direction where the dispenser is facing.
- Battle o' chanting, egg, snow ball, splash potion, lingering potion
   - Thrown in the direction where the dispenser is facing, as like as how player throw it.
- Bone meal
   - Uses bone meal (as fertilizer) on the block the dispenser is facing, if possible. If the block faced does not react to bonemeal, no bone meal is used
- Fire Ball
   - Launches fireball (as if produced by a blaze) in the direction the dispenser is facing.
- Flint and Steel
   - It place a fire in front of dispenser and reduce the durability of the flint and steel, If there is TNT it will ignites the tnt.
- Firework Rocket
   - Launches in the direction the dispenser is facing. Can be used to inflict damage if it was crafted with stars.
- All types of Minecart
   - Placed as entity in the block the dispenser is facing, if the dispenser is facing a type of rails, otherwise dropped.
- Boat
   - Placed as entity in the block the dispenser is facing, if the dispenser is facing water or an empty block above water, otherwise dropped.
- Spawn Egg
   - Summons a mob in front of the dispenser
- TNT
   - Places and ignites TNT in the block the dispenser is facing.
- Trident
   - Thrown in the direction the dispenser is facing.
- Water Bucket, Lava Bucket
   - Places lava or water in the block in which the dispenser is facing (replacing the lava or water bucket in the dispenser with an empty bucket), if the dispenser is facing at block it dropped.
- Cod, Salmon, Tropical & Puffer Fish Bucket
   - Places a water and summon a fish in the block in which the dispenser is facing, leaving an empty bucket in dispenser.
- Empty Bucket
   - Collects lava or water source block in which the dispenser is facing, adding the newly filled bucket to an empty slot in the dispenser's inventory.

Other items should only drop

#### Hopper

A hopper is used to move items to and from containers (including other hoppers).

A hopper can be placed so that its output (small tube at the end) faces in any direction except up.
- While it's not activated, a hopper pulls items from a container above it (or drop items in top of it) into its own slots and pushes items from its own slots into a container it is facing.
- While activated, a hopper does not pull items from above or push them out, but may receive items from other mechanism components such as droppers, and may have its items removed by another hopper beneath it.

#### Redstone Lamp

Redstone lamp emit lights when powered by a redstone. It simply can be use for switch light that can control to turn on and off, can make a lamp post that will automatically open when night using daylight sensor and more.

#### TNT

TNT is a block that can be used by the player to initiate a controlled explosion. If TNT received a redstone signal it will ignites. In addition, TNT can also be activated by fire and explosions, as well as flaming arrows. This is considered as redstone components because it can react to a redstone.

#### Noteblock

A note block is used to produce a player's chosen sound.

After being placed, a note block's pitch can be adjusted over a two-octave range, and its "instrument" can be adjusted by placing different blocks beneath it.

When activated, a note block produces a sound. A note block must have air above it to activate.

#### Rail

A Rail in Minecraft can be powered too, this makes a curved rail to changed it's direction, you can switch between the two way. Activating a rail in another configuration has no effect.

#### Powered Rail

A powered rail is used to propel a minecart. While activated, a powered rail boosts the speed of a minecart passing over it, or starts a minecart moving away from an adjacent solid block it is in contact with. While not activated, it will acts as a "brake", reduces the speed or even stop a minecart passing over it.

In addition a powered rail can also be activated by other adjacent activated powered rails. A powered rail can transmit activation up to 9 rails (the first originally-powered powered rail, and up to eight additional activated rails). Activation transmitted in this way cannot power any redstone components except powered rails.

#### Activator Rail

An activator rail is used to activate a minecart. An activator rail affects certain minecarts passing over it. The effects vary with the type of minecart activated:

**Normal Minecart** - Minecarts with an entity riding it (mob or player) will eject that entity if the activator rail is active.

**Minecart with Hopper** - It will deactivate by an activated activator rail (it will stop sucking up items in its path, or transferring items to containers as it passes them), and re-activated by an unactivated activator rail.

**Minecart with TNT** - It will ignite the TNT by an activator rail.

**Minecart with Command Block** - It will execute its command every 2 redstone ticks.

#### Command Block

A command block executes its defined command once. To make a command block constantly execute its command, it must be run on a clock circuit or set it to repeating command block.

Like other mechanism components, an already-activated command block will not respond to other redstone signals. To make a command block execute its defined command more than once it must be deactivated and re-activated repetitively. Or can be activated repetitively by setting the command block to always active.

