# Auction-Tracker
This Auction Tracker Excel file manages player auctions for sports leagues, tracking player details, bids, team rosters, and budgets while enforcing auction rules. A Power BI file is also included, featuring interactive graphs for deeper insights and visual analysis, making it ideal for fantasy leagues and strategic team building.

# Problems Solved
Simplifies complex auction tracking with detailed player, team, and owner data. <br>
Ensures teams meet required squad sizes and role balance (batsmen, bowlers, wicketkeepers).<br>
Helps manage limited budget points effectively during player bidding and team formation.<br>
Provides clear records of sold and unsold players with price and role details.

# Strengths
Comprehensive: Includes player categories, roles, specializations, and ownership data.<br>
Budget control: Tracks total points, points used, balance points, and players bought per team.<br>
Team compliance: Monitors minimum and maximum player constraints per team.<br>
Clear auction logs with pricing and status updates for each player.

# Key Points
# 🏏 Auction Tracker - Excel Project

## Problem Statement
Managing a player auction across multiple teams is complex. Each team has a limited budget, a fixed number of slots, and specific role requirements (e.g., batsmen, bowlers, all-rounders, wicket-keepers).  
Without a structured system, tracking bids, ensuring budget compliance, and monitoring balance sheets becomes error-prone and time-consuming.

---

## Solution
The **Auction Tracker** Excel file provides an end-to-end solution to manage and monitor the entire auction process.

### Key Features

1. **Player & Owner List**
   - Master data of all players and team owners.  
   - Used for lookups and validations.  

2. **Auction Log**
   - Tracks each bid with details like player, team, role, and final price.
   - Used for auctioning player live.
   - Prevents duplicate selections through data validation.  

3. **Balance Tracker**
   - Uses formulas like `SUMIFS`, `INDEX-MATCH`, `VXLOOKUP` to dynamically calculate each team’s **remaining budget** and **slots left**.  
   - Conditional Formatting highlights teams overshooting budgets.  

4. **Team List**
   - Automatically updates with players acquired by each team using formulas such as `FILTER`, `UNIQUE`, or `IFERROR(XLOOKUP(...))`.  
   - Helps visualize squad balance across roles.  

5. **Auction Summary**
   - Uses Pivot Tables and Charts to summarize spend per team, role distribution, and average player price.  
   - Provides high-level insights into auction fairness and competitiveness.  

6. **Rules**
   - Maintains transparent guidelines for player acquisition, budget caps, and eligibility.  

---

## Advanced Excel Features Used
- **Dynamic Array Formulas**: `FILTER`, `SORT` for real-time team composition.  
- **Lookup Functions**: `XLOOKUP` / `INDEX-MAT`


# Use Cases
Sports league player auctions management.<br>
Fantasy sports team building with budget and role constraints.<br>
Auction result analysis and team budget tracking.<br>
Player performance and team composition planning.

# Dashboard
A Power BI dashboard has been created to complement this Excel tracker, featuring informative and interactive graphs and buttons. The dashboard provides dynamic visualization of auction progress, team budgets, player distribution, and key metrics for easy, at-a-glance insights and decision-making.

