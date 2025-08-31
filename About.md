# FloatChat – AI for ARGO Ocean Data

## What is FloatChat?
FloatChat is an **AI-powered conversational tool** that makes huge ARGO ocean datasets (temperature, salinity, currents, etc.) accessible to everyone.  
Instead of coding or parsing NetCDF files, users can simply **ask questions in natural language** and get answers, charts, or insights.

## Why Do We Need It?
- **Ocean data is critical**: for climate change, fisheries, disaster management, and coastal planning.  
- **Currently locked away**: only experts with coding/data skills can use it.  
- **FloatChat democratizes access**: students, policymakers, researchers, NGOs, even citizens can explore data easily.  

## Key Benefits
- Saves **time for researchers** → no need to manually wrangle data.  
- Helps **government & agencies** make faster, informed decisions.  
- Provides **real-world datasets** for students/educators.  
- Boosts **public awareness** on oceans and climate.  

## System Flow (Simplified)

# FloatChat – AI for ARGO Ocean Data 🌊🤖

## System Flow

```mermaid
flowchart TD
    A([🧑 User Query]) --> B([🤖 AI Query Engine])
    B --> C([🌊 ARGO Data / NetCDF])
    C --> D([⚙️ Data Processing & ML])
    D --> E([📊 Visualization + Insights])
    E --> F([💬 Output to User])

    %% Styling
    style A fill:#e3f2fd,stroke:#2196f3,stroke-width:2px
    style B fill:#f3e5f5,stroke:#9c27b0,stroke-width:2px
    style C fill:#e8f5e9,stroke:#4caf50,stroke-width:2px
    style D fill:#fff3e0,stroke:#ff9800,stroke-width:2px
    style E fill:#fce4ec,stroke:#e91e63,stroke-width:2px
    style F fill:#ede7f6,stroke:#673ab7,stroke-width:2px
