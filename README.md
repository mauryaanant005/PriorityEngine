1. Dashboard (Main Control Center)
<img width="1920" height="1080" alt="Screenshot 2025-12-28 150341" src="https://github.com/user-attachments/assets/7fedd6c3-65af-4c95-9749-fae55527616f" />

Simple Description:
The Dashboard is your command center for managing Indian Railways operations in real time. It gives you a complete overview of what's happening across the network at a glance.

Key Features:

Header Bar: Shows the Indian Railways emblem, live IST clock (date & time), controller name and role, and logout button

Left Sidebar: Navigation menu with icons for Scheduling, Simulations, Allocations, Disruptions, Analytics, and Settings

Interactive Railway Map: Shows tracks, junctions, and color-coded moving trains (red = express, yellow = freight, blue = local). Trains that are delayed pulse with animations. Hover over any train to see details like Train ID, speed, ETA, and priority

Four KPI Cards (Key Metrics):

Punctuality Rate: Shows percentage with color-coded progress ring (green >90%, yellow 70-90%, red <70%)

Average Delay: Bar chart showing delays over the past hour

Throughput: Line graph showing trains per hour

Resource Utilization: Pie chart showing platform and track usage

Right Sidebar: Top 3 AI recommendations with Accept/Override buttons – these are smart suggestions from the AI to improve operations

Bottom Alert Ticker: Scrolling notifications for disruptions and alerts (e.g., "Weather delay on Track 3")

2. Scheduling & Train Precedence
<img width="1920" height="1080" alt="Screenshot 2025-12-28 150401" src="https://github.com/user-attachments/assets/773ba5c9-907d-443d-ae64-e08f82ad169f" />

Simple Description:
The Scheduling screen is where you manage which trains go first and ensure they don't collide on the same track.

Key Features:

Gantt Timeline View: Displays all tracks vertically with time flowing left to right. Each train is shown as a colored block – red for express, yellow for freight, blue for local

Conflict Detection: When two trains are too close together and violate safety rules, the system highlights the conflict in red and suggests an AI fix with dashed lines

Train Search & Filters: Search by train ID, filter by train type (express/freight/local), priority level, or time range

Train Details Panel (Right): Shows complete info for selected train – schedule, route, constraints, and override options

Precedence List (Bottom): Drag trains up or down to manually change their order. Shows which train goes first

Optimize Button: Click to run AI optimization – the system recalculates the best order for all trains to minimize delays (typically saves 8-15% delay)

Action Buttons: Apply Changes (with confirmation), Reset to Original, or Export Schedule as PDF/CSV

3. What-If Simulations
<img width="1920" height="1080" alt="Screenshot 2025-12-28 150432" src="https://github.com/user-attachments/assets/38750839-1184-49a2-9eab-1028de0b0b2a" />

Simple Description:
The Simulations screen lets you test different scenarios before actually changing the real schedule. "What if this train gets delayed? What if we reroute that train?"

Key Features:

Left Input Panel (Scenario Builder):

Add delay to any train (select train + set minutes)

Reroute trains to alternative paths with live preview

Insert unscheduled emergency trains

Adjust weather severity (affects all train speeds)

Run Simulation button to test your scenario

Central Comparison Area:

Left side: Original schedule (reference)

Right side: Simulated schedule (what happens with your changes)

Color coding: Green bars = trains improve, Red bars = trains worsen, Gray = unchanged

Results Table: Shows scenario name, total delay (in minutes), throughput (trains/hour), resource utilization, and allows rename/delete/export

Right Sidebar:

Impact Analysis: Which trains are affected

Constraint Violations: Safety violations with AI fixes suggested

AI Optimization Log: Shows how the AI solved the scenario

Undo/Redo: Quickly switch between different test scenarios

4. Platform & Resource Allocation
<img width="1920" height="1080" alt="Screenshot 2025-12-28 150447" src="https://github.com/user-attachments/assets/6c951109-9713-4d30-af3a-1ae5f6479c1a" />

Simple Description:
The Allocations screen helps you assign trains to specific platforms and tracks at stations. It's like a parking lot manager – making sure each train gets the right spot.

Key Features:

Back to Dashboard: Quick link to return to main view

Station Selector: Choose which railway division/section to manage (e.g., "Central Zone - Delhi Division")

Real-time Sync: Toggle to sync live platform updates

Interactive Station Diagram: Visual layout showing platforms (green slots), tracks (gray lines), junctions (blue nodes), and current train positions

Drag-and-Drop Placement: Drag train icons onto available platforms – they snap into place. If placement violates rules, a warning modal appears

Platform Allocation Table: Lists each platform with:

Platform ID (P1, P2, P3, P4)

Current train assigned

Availability status (occupied/available)

Constraints (train length, electrification type, power supply)

Utilization percentage

AI Optimization Engine (Center):

Click "Run Optimization" to let AI suggest best platform assignments

Shows blue highlights on recommended placements

Acceptance threshold slider (50% low to 100% high) to control how many AI suggestions you accept

Last optimization timestamp and AI model version

Resource Filters (Right): Filter by resource type, availability status, power type

Resource Utilization Chart: Shows which platforms are heavily used and which are free

Overall Efficiency: Display showing 74% optimal allocation

5. Disruption Management
<img width="1920" height="1080" alt="Screenshot 2025-12-28 150501" src="https://github.com/user-attachments/assets/ea2e1739-0b70-40ed-92c6-661406bfca7f" />

Simple Description:
The Disruptions screen is your emergency dashboard for handling unexpected events like signal failures, weather, or track breakdowns.

Key Features:

Top Alert Banner (Red & Urgent):

Shows active disruption with large warning icon

Example: "Active Disruption: Signal Equipment Breakdown – Track 2, Junction A"

Countdown timer: "Est. Resolution: 29 minutes"

Severity badge: BREAKDOWN

Close button to dismiss

Left Panel – Active Incidents:

List of all ongoing problems sorted by severity (HIGH, MEDIUM, LOW)

Example incidents: Signal Equipment Breakdown (HIGH), Heavy Rain Alert (MEDIUM), Track Maintenance (LOW)

Timestamps for each incident

Click to expand for more details

Central Panel – Network Overview:

Interactive railway map showing stations and tracks

Red and orange ripple pins mark affected areas

Shows scale of impact across the network

Zoom and pan to investigate specific areas

Right Panel – Quick Actions:

Quick Notifications: Pre-written alerts to send to Operations Team, Station Masters, Emergency Services via Email or SMS

Incident Logging: Text box to add incident notes, observations, and updates

Add Photo: Upload images of the problem

Log Entry: Record the incident with timestamp

Bottom Section – Mitigation Strategies:

AI-generated action cards showing what you can do

Example: "Reroute via Alternative Track – 85% confidence"

Shows impact: "Reduce delay by 15 minutes"

Accept buttons to implement each strategy

Live Updates: Real-time log showing "Incident Reported – 14:32:15"

6. Performance Analytics
<img width="1920" height="1080" alt="Screenshot 2025-12-28 150520" src="https://github.com/user-attachments/assets/7632b67d-50c1-4949-883b-08011d140256" />

Simple Description:
The Analytics screen shows you detailed performance reports and helps you understand patterns in your railway operations.

Key Features:

Top Toolbar:

Date range picker (e.g., "Last 30 Days")

Export Report button (download as PDF or Excel)

KPI Cards (Top Row):

Punctuality Trends: 87.3% average on-time performance this month, +2.1% improvement from last month

Throughput Analysis: 142 trains per hour at peak times

Resource Utilization: 78.2% of platforms/tracks in use, +3.4% higher than last month

Delay Cause Analysis (Bottom Left):

Horizontal bar chart showing why delays happen:

Weather Conditions: 32%

Signal Issues: 28%

Track Maintenance: 22%

Other: 18%

AI Insights & Predictions (Bottom Right):

Forecasted Peak Hours: Expected 15% traffic increase between 4-6 PM today

Weather Impact Alert: Rain predicted tomorrow – may cause 5-8 minute delays

Optimization Opportunity: Adjusting signal timing could improve throughput by 12%

Custom Query Support: Run advanced SQL-like queries to extract specific insights

7. System Settings
<img width="1920" height="1080" alt="Screenshot 2025-12-28 150548" src="https://github.com/user-attachments/assets/7ca58477-35c6-4ca9-9bc7-26df774a1530" />
Simple Description:
The Settings screen lets you customize how PriorityEngine works for your specific needs and manage integrations with other railway systems.

Key Features:

Tab Navigation (5 tabs):

1. General Preferences:

Auto-refresh dashboard toggle (automatically update data)

Dark mode toggle (already enabled)

Sound alerts toggle (get audio notifications)

Enable animations toggle (smooth visual effects)

2. Integrations (Connect to other systems):

TMS (Train Management System) – green checkmark (connected)

Signals API – green checkmark (connected)

Weather API – orange warning (check status)

Add/Edit/Test buttons for each integration

3. Notifications:

Configure alert methods (email, SMS, in-app pop-ups)

Set notification preferences by alert type

4. Security:

Change password

Enable 2-factor authentication (2FA)

View audit logs (history of all actions taken)

5. Profile:

View and edit your controller profile

Manage permissions and access levels
