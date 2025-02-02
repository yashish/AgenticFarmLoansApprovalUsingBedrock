# AgenticFarmLoansApprovalUsingBedrock
Build an Agentic US Federal FSA Farm loan approval system using RAG with AWS BedRock in Python

Solution Flowchart:
[Flowchart.pdf](https://github.com/user-attachments/files/18633107/Flowchart.pdf)

Use Case: US Dept of Agriculture Farm Loans Credit Approval/Risk analysis

Leverage GenAI with automation of Agricultural Farm loans (crops/poultry) to

    •	Generate Credit Notes (Approve/Reject) based on some authoritative Farm yield assumptions
    
    •	Enhance productivity of Farm Loan employees saving time with data ingestion, determine loan type
    
    •	Remove bias and mathematical errors in Credit Notes calculations/reasoning
    
    •	Perform some basic form validation data  – help with data cleansing??
    
    •	Include some data visualizations/charts for historical data and insights – nice to have

Implement solution using agent(s) that can scour publicly available data for Yield and price for commodities

With data obtained, compare data captured in PDF to current published public price data
Example,
Will help determine say if the 50% yield submitted is feasible/profitable to determine Credit Note

Solution will use AWS GenAI to generate the credit note results automatically using publicly available farm yield data and use it as Knowledge Bank and utilize an Claude Sonnet 3.5 model to automate approvals/rejections.
Capture the data and store it internally using AWS data dump in S3 or Aurora. Use of RAG with a vector database can be included for capturing data/caching/reporting etc if there’s bandwidth to add complexity to augment the use cases for reporting etc
