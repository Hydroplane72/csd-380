# Weekly Coursework Value Stream Summary 
Glossary:
- VA: Value-Added Time (time spent on activities that directly contribute to learning outcomes)
- NVA: Non-Value-Added Time (time spent on activities that do not directly contribute to learning outcomes, such as waiting or administrative tasks)

## 1. Major Workflow Stages and Average Time Spent

Assignment Work  
- Average Time: 3.0 hours  
- VA/NVA Mix: Mostly VA, some NVA  

Discussion Post  
- Average Time: 1.5 hours  
- VA/NVA Mix: Mostly VA, posting is NVA  

Peer Replies  
- Average Time: 3.25 hours  
- VA/NVA Mix: Mix of VA and NVA  

---

## 2. Total Weekly Time

Total Time Spent: 7.75 hours  
Value-Added Time (VA): 390 minutes  
Non-Value-Added Time (NVA): 75 minutes  
Flow Efficiency: 84%  
Formula: Flow Efficiency = VA / (VA + NVA)

---

# 3. Flow Chart

``` Mermaid
flowchart LR

    %% SUBGRAPH FOR ASSIGNMENT
    subgraph A_Sub["Assignment"]
        direction TB
        A1["Wait until kids' bedtime (NVA)"]
        A2["Log into computer (NVA)"]
        A4["Read this week's assignment (VA)"]
        A5["Review what is being asked (VA)"]
        A6["Make bullet list of tasks (VA)"]
        A7["Expand bullet list as needed (VA)"]
        A8["Polish assignment for errors (VA)"]
        A9["Review result vs. assignment details (VA)"]
        A10["Upload assignment as complete (NVA)"]

        A1 --> A2
        A2 --> A4
        A4 --> A5
        A5 --> A6
        A6 --> A7
        A7 --> A8
        A8 --> A9
        A9 --> A10
    end

    %% SUBGRAPH FOR DISCUSSION POST
    subgraph C_Sub["Discussion Post"]
        direction TB
        C1["Read discussion prompt (VA)"]
        C2["Debate if real-life experience can substitute for researching an article (VA)"]
        C3["Write bullet points needed for the post (VA)"]
        C4["Expand bullet points to meet word count goal (VA)"]
        C5["Find an online article supporting real-life experience (VA)"]
        C6["Clean and polish post to be college-worthy (VA)"]
        C7["Post discussion entry (NVA)"]

        C1 --> C2
        C2 --> C3
        C3 --> C4
        C4 --> C5
        C5 --> C6
        C6 --> C7
    end

    %% SUBGRAPH FOR PEER REPLIES
    subgraph E_Sub["Discussion Post Peer Replies"]
        direction TB
        E1["Wait for 3 student posts (2–3 days) (NVA)"]
        E2["Read each post (VA)"]
        E3["Determine if any posts are too similar to review (VA)"]
        E4["Create a list of likes and disagreements (VA)"]
        E5["Fill out reply with likes (VA)"]
        E6["Add disagreements if needed to meet word count (VA)"]
        E7["Review for constructive criticism (VA)"]
        E8["Polish reply (VA)"]
        E9["Post reply (NVA)"]
        E10["Repeat process 3 times (NVA)"]

        E1 --> E2 --> E3 --> E4 --> E5 --> E6 --> E7 --> E8 --> E9 --> E10
    end

    %% LEAN METRICS
    subgraph subGraph1["Lean Metrics"]
        M1["Total Cycle Time: ~7.75 hrs"]
        M2["Value-Added Time: 390 min"]
        M3["Non-Value-Added Time: 75 min"]
        M4["Flow Efficiency: 84%"]
    end

    %% MAIN FLOW CONNECTIONS
    A_Sub --> C_Sub
    C_Sub --> E_Sub
    E_Sub --> n1["Homework for week is complete"]

    %% CLASS DEFINITIONS
    classDef value fill:#8fd3fe,stroke:#036fa6,stroke-width:1px,color:#000
    classDef wait fill:#ffe08a,stroke:#a67c00,stroke-width:1px,color:#000
    classDef support fill:#d3d3d3,stroke:#555,stroke-width:1px,color:#000



``` 

# 4. Optimization Opportunities

## Reduce Non-Value-Added Time

Waiting for Peer Posts
- Check replies only at scheduled times (At least 2 days after posting, but before the deadline) or wait till later in week to do first post, then check for replies in one block of time 
- Pre-draft reply templates to reduce turnaround time  

Startup Overhead  
- Create a “Course Start Checklist”  
- Review all weekly assignments in one planning block  


## Improve Assignment and Discussion Writing Efficiency

Standardize Templates  
- Assignment template  
- Discussion post template  
- Peer reply template  

Batch Similar Tasks  
- Read all materials together  
- Write all content together  
- Polish all content together  

## Automate or Systematize Repetitive Work
- Use Grammarly or Word Editor for polishing  
- Use Google Calendar reminders for discussion deadlines  
- Use Copilot to review accuracy of assignment and discussion content before posting

## Future-State Goal
Reduce weekly NVA time from 75 minutes to 30 minutes, increasing flow efficiency from 84% to 92%.


## References:
Used to help create the value stream map in mermaid syntax:
Microsoft. (2026). Microsoft Copilot [Large language model]. Microsoft. https://www.microsoft.com/copilot