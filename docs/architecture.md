# Smart Disaster Response System Architecture

## Components

### Database Layer
- DBConnection
- DatabaseService

### Graph Engine
- Graph
- Edge
- Node
- RouteEngine

### Decision Layer
- DecisionEngine
- AllocationEngine

### User Interface
- ControlPanel
- DashboardPanel
- MapPanel
- RoutesPanel

### Export Layer
- ExportService

## Routing

Shortest path computation uses Dijkstra's Algorithm.

## Allocation

Population is allocated greedily based on shelter capacity and route distance.

## Persistence

MySQL stores:
- disasters
- shelters
- routes
- reports
