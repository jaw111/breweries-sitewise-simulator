# **Brewery Simulator – Main Decision Logic**

Summary of What's Represented.

## **Fermenter → Bright Tank logic**

* Conditions to begin allocation
* Sequential search through Bright Tank 301–305
* Timer‑based release
* Material shipping to allocated tank
* Completion logic

## **Bright Tank → Bottling Line logic**

* Conditions to begin allocation
* Search for available Bottling Lines
* Material shipping with completion

## **Brew Trains 100 & 200**

* Roaster → Mash
* Mash → Boil
* Boil → Fermenter
* Transfer of ProductionID, ItemIDs, Lots, and PV values
