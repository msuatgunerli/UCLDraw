# UCLDraw

## Introduction

This notebook was created as part of a project for the course Deterministic Optimization (ISYE 6669) at Georgia Tech. The goal of the project was to create the most competitive groups for the Group Stage of the Champions League by minimizing the sum of variances of Elo ratings across all groups.

## What is the Champions League?

The Champions League is an annual football (soccer) competition organized by the Union of European Football Associations (UEFA). It features the best club teams from Europe and is widely considered the most prestigious club competition in the world.

The competition is divided into two stages: the Group Stage and the Knockout Stage. The Group Stage consists of 32 teams divided into eight groups of four teams each. Each team plays six matches against the other teams in their group, with the top two teams from each group advancing to the Knockout Stage.

## How does the group stage draw work?

The draw for the group stage is conducted using a seeding system based on the performance of each team in their domestic league as well as previous performance in European competitions. The 32 teams are divided into four pots.

The draw begins with one team from each pot being drawn to form a group. This process is repeated until all eight groups have been formed. No two teams from the same country can be drawn in the same group and no two teams from the same pot can be drawn in the same group.

## Optimization approach

In this project, we used an optimization approach to arrive at the most competitive grouping arrangement for the Group Stage of the Champions League. Specifically, we aimed to minimize the sum of variances of Elo ratings across all groups.