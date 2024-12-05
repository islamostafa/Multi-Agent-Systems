# Forest Quest Agent

## Overview

This project implements an agent-based solution for a quest in a forest environment using the JASON agent development platform. The main objective is to develop a Hero agent that can navigate through a forest, collect specific items, and return them to Grodor the Goblin.

## Learning Objectives

- Understand the main application areas of agent-based solutions
- Develop a meaningful agent-based system using a contemporary agent development platform (JASON)

## Premise

Grodor the Goblin has stolen some items from the player. To retrieve them, the player must send an agent (the Hero) on a quest to collect three valuable items in the forest: a coin, a vase, and a gem. Once collected, these items must be returned to Grodor the Goblin.

## Project Structure

- `ForestX.java`: Test environments for checking and demonstrating agent functionalities
- `Forest.mas2j`: JASON main file for environment and agent configuration
- `hero.asl`: AgentSpeak file containing the Hero agent implementation
- `goblin.asl`: AgentSpeak file containing the Goblin agent implementation

## Tasks

- Implement the Hero agent in `hero.asl`


## Hero Agent Requirements

- Move systematically through the 8x8 grid environment
- Collect a vase, coin, and gem
- Return to the Goblin's location and drop the items
- Do not visit the Goblin if all three items are not collected

## Environment Details

- 8x8 grid representing the forest
- Items (coin, vase, gem) placed in various locations
- Possible teleporter square (labeled 'T') that moves the Hero to a random location

## Available Percepts and Actions

The README lists various percepts (e.g., agent positions, item locations) and actions (e.g., movement, picking up items) available to the Hero agent.

## Note on Forest Backend

For data protection reasons, the backend code for the Forest environment is not included in this repository.

## Assessment
- Well-commented code to demonstrate understanding


