# Algorithms

## Dijkstra's Algorithm

Used by RouteEngine to compute shortest evacuation routes.

Complexity:
O((V + E) log V)

## Allocation Algorithm

Greedy shelter assignment based on available capacity.

## Decision Engine

Scores shelters using:

score = distance + (1000 / capacity) * 10

Lower score = better shelter.
