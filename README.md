Battle Resolve Simulator is an ASP.NET Core Web API that simulates large-scale medieval battles using a tick-based combat engine.
Inspired by games such as Mount & Blade II: Bannerlord, Total War, Crusader Kings III, and Hearts of Iron IV, the project focuses
on realistic battle resolution through configurable troop statistics, tactical interactions, and state-driven combat mechanics.
Instead of calculating the outcome with a single formula, the engine progresses through the battle tick by tick.
During each simulation step, units engage enemies, apply combat modifiers, suffer casualties, lose morale, reinforce the frontline from reserves, and continue fighting until one army is destroyed or routed.
The simulation supports advanced mechanics including combat width, troop counters, morale, routing, reserve deployment, engagement tracking,
and Total War-inspired charge mechanics such as charge bonus, charge absorption, and charge reflection.
Every battle produces a detailed report containing the winner, casualties, battle duration, and an optional combat log describing the course of the engagement.
The project is designed as both a strategy simulation framework and a portfolio backend application demonstrating object-oriented design,
REST API development, Entity Framework Core, state management, algorithms, and complex business logic.
