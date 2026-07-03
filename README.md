# hospital-inventory-intelligence
A healthcare data analytics project that helps hospitals monitor medical supply inventory across multiple branches. The system compares current inventory with historical usage patterns to identify supplies that are running low, overstocked, or at healthy levels. It also uses AI to generate simple restocking recommendations, making it easier for supply chain teams to make informed decisions.

Why I Built This ?

Managing hospital inventory is a balancing act. Running out of essential medical supplies can affect patient care, while ordering too much increases storage costs and the risk of supplies expiring.

I built this project to explore how data analytics and AI can help hospitals make better inventory decisions by turning raw inventory and usage data into clear, actionable insights.
**
What the Project Does ?

The system:

-> Tracks inventory for 20 commonly used medical supplies across four hospital branches
-> Analyzes 12 weeks of usage history to understand consumption patterns
-> Estimates how many weeks each product will last based on current stock levels
-> Flags products as Critical, Understocked, Overstocked, or Healthy
-> Uses an AI model to generate easy-to-understand restocking recommendations
-> Displays inventory status through an interactive dashboard

Tech Stack:

-> Python (pandas) for data cleaning and analysis
-> MySQL for storing inventory and usage data
-> Groq API (Llama 3.1) for generating AI recommendations
-> Claude Desktop + MCP Server for querying the database using natural language
-> Jupyter Notebook for analysis and experimentation
-> HTML, CSS, JavaScript for building the dashboard

Project Structure
├── data/                  # Raw and cleaned datasets
├── notebook/              # Data cleaning, analysis, and AI notebooks
├── reports/               # Dashboard, charts, and recommendation files
├── .gitignore
└── README.md
What I Found

After analyzing inventory across four hospital branches, a few patterns stood out:

-> 12 products had less than one week of supply remaining and required immediate attention.
-> Every product category included items that were below the recommended inventory level.
-> The West Branch showed the greatest inventory imbalance, with both high overstock and frequent shortages.
-> The North Branch had less than one week of stock remaining for N95 respirators, highlighting a potential risk for patient care if demand increased.
