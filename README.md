# hhh
flowchart TB
    subgraph Support_Activities [Support Activities]
        KM[Knowledge Management]
        TD[Training & Development]
        II[Innovation Initiatives]
        PM[Performance Monitoring]
    end
    
    subgraph Primary_Activities [Primary Activities]
        REA[Requirements Elicitation and Analysis]
        SDV[Solution Design and Validation]
        CFC[Cross-Functional Collaboration]
        STI[System Testing and Implementation]
        SE[Stakeholder Engagement]
    end

    KM --> REA
    TD --> REA
    II --> REA
    PM --> REA

    REA --> SDV
    SDV --> CFC
    CFC --> STI
    STI --> SE
