# Factory Management System 

A robust desktop application designed to manage industrial production lines, machinery, and personnel assignments. This system acts as a digital supervisor, ensuring that production protocols and safety requirements are met through automated validation logic.

Core Concept

The system bridges the gap between workforce management and machinery operations. It enforces a strict operational hierarchy, meaning no machine can run and no production can be logged unless the required staff (Workers, Engineers, and Managers) are properly assigned and active.

Key Features
1. Smart Operational Logic
Machine Safety Lock: A machine status cannot be changed to "Running" unless the system detects at least one Engineer and one Worker assigned to it.

Production Hierarchy: Logging a production batch requires a complete line supervision team, including a Manager and a Senior Engineer.

Status Control: Real-time management of machine states: Running, Maintenance, or Idle.

2. Live Monitoring Dashboard
Visual Oversight: A real-time monitor showing the status of every production line.

Staff Distribution: Instantly see which personnel are assigned to which machines or lines.

DASHBOARD Analytics: A quick summary of active machines, total staff, and warehouse stock levels.

3. Inventory & Personnel Management
Warehouse Integration: Automated stock updates upon successful production logs.

Personnel Database: Categorized management of Workers, Engineers, Seniors, and Managers with relational mapping to factory assets.
