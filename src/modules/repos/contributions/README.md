# Contributions
The requirement of contribution is the most important feature of this project. 

## Subject Methods
- Automated (Best for future implementation)
- Structured

### Automated
This will require the calculation of contribution 
based on known factors in code creation
i.e Code
- Complexity. 
- Lines of Code lCol
- Approximate time required for implementation (man-hours required).
- Base feature utilization on the grand scheme. 
    - i.e In a situation where the project is a chat app how often does one use the video calls. 
      providing a scale of how useful is the feature to the product at hand.
      
### Structured Approach
Providing an automated method to calculate code might be quite hard given the number of unknown factors. 
But if possible it should be more efficient than this. 

In this design each project must have a set of price regulators and evaluators.

And developers will be required to use a punch card software/plugin that might require
integration with to evaluate
their working


##### Sample consider this project. 
It will require project management to handle the pricing of the software. 
And developers to sustain and maintain the project. 
The platform will provide project managers to sign up and apply as for a role in a provided project. 
The developers are the ones to put it to vote on who they require in the team, 
and their capacity to support the manager. 

Managers. Since this is a collaboration platform payments are not based on fixed salaries but rather. 
Developer input. 

[Price Estimation By Project managers or accounts](https://www.toptal.com/product-managers/product-management/software-pricing-strategy-and-architecture)

Now given this is a contribution platform the developers' contribution will be calculated from 
man-hours/total man-hours 

![Pricing sample](../../../../public/images/doc/sample_price_breakdown.png)


### RoadMap
### Features implementation
- Users Account management
    - Financial reports, earnings based on contributions. 
    - Registration and Editing.
    - GitHub API integration 
- Contributions 
    - Use GitHub API to get required data and store on the platform. 
        - hosting the project it's self is more convenient.
    - Provide retrieved data to project managers for evaluation. 
        - Hours the person worked for. Comparing commit time differences. 
          from issuing the issue to solution. 
        - The changes that were made code or design.
            > SCRUM  <br>  Evaluates a developer performance. 
    - Process and save project evaluations from the project manager.
        - Developer efficiency
        - Code estimates
            - This is on a branch to branch basis
    - Provide access control to a repository.
        - Segmented Visibility. 
            - Ability to only see a few sections of code base relevant to the viable task. 
        - Only qualified developers can contribute.
            - The repos are to be private repos. 
                 - API auth http://api.github.com/repos/:owner/:repoName?access_token=:token
                    > This is until the platform can implement its own repo manager.  
            - Qualification process
                - Developers have to put out an application request to participate in a given
                 project. 
                 
> References  
> [Performance Eval, SCRUM](https://pm.stackexchange.com/questions/17514/any-ideas-about-how-to-evaluate-a-developers-performance)  
> [Medium Used in industry](https://medium.com/@yupyork/the-best-developer-performance-metrics-6295ea8d87c0)  
> [Pluralsight Metrix](https://www.pluralsight.com/blog/teams/5-developer-metrics-every-software-manager-should-care-about)

1. Lead Time  
Estimated timelines
2. Code Churn 
Added and deleted code.
[churn sample project](https://github.com/danmayer/churn)
3. Impact
This is the number of code changes done in consideration of number of files updated and lCod changes
git --diff
4. Active days

This will display the active times an :owner made changes to :repo
https://api.github.com/Users/:owner/:repo/stats/punch_card

5. Efficiency
Ability to contribute code that is producive. 
![Efficiency](../../../../public/images/doc/effective.png)

- User registration
    - Personal details including a viable CV. 
    - Account mn
    
- Since Contributions and competence might require a lot of human interaction due to lack of a stable 
and consistent software pricing methodologies. The platform should only provide access to required 
data. 


***extras**
- Costing Guidelines
- Charge by project not by hours
    - Project estimates
        - Is the design available
        - Features
        - Timelines
        - Integration




