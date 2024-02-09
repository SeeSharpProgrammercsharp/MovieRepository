# MovieRepository
Manage Movies
1. Technology Stack
   1.  Dot Net 7 Micro Service
   2.  Three Layered Architecture
   3.  Entity Framework Core 7
   4.  SQL Database
   5.  Non Genric Repository Pattern
   6.  Linq Queries for Data Retrival
2.  Considerations
    1.  As compexity of the system is medium.
    2.  Relationship data table designs
    3.  DTO's are used to share data to endpoints
    4.  Common response model design
    5.  Microsoft Logging
Worker Service
1. Technology Stack
   1.  Dot Net 7 Worker Service
   2.  Corn Job extension for Time Trigger  
2. Considerations
   1.  Worker service is directly calling Service layer, as this is related to data. Even though i have created an endpoint also for it.
   2.  Simple corn job trigger i have used to trigger midnight.
   3.  Publish destination and code is void.
     

