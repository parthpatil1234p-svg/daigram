flowchart LR
    subgraph A["Traditional Degree (80% Disconnect)"]
        direction TB
        A1["1.5M+ Annual Graduates"]
        A2["Theoretical Syllabus"]
        A3["Vague Personality Quizzes"]
    end

    subgraph GAP["The Chasm"]
        direction TB
        G1["Analysis Paralysis"]
        G2["Random Tutorials"]
        G3["Zero Personalized Direction"]
    end

    subgraph B["Industry Hiring Reality"]
        direction TB
        B1["Production Frameworks"]
        B2["Practical Git Workflows"]
        B3["₹4.5 - ₹9 LPA Job Bar"]
    end

    subgraph C["CareerPath AI (ED-02 Bridge)"]
        direction TB
        C1["Transparent 60/25/15 Math Engine"]
        C2["Tri-Color Gap Analysis (🟢 🟡 🔴)"]
        C3["Milestone-Driven Weekly Roadmap"]
    end

    A --> GAP
    GAP --> B
    C -.->|"Bridges The Chasm"| GAP
