# 🌍 Open Source Evaluation Checklist

1) Generel considerations
    * Joining existing project?
    * Potential partners?

2) Business case assesment
    * Define roadmap and goals
    * Funding and manegement commitment

3) Legal assesment
    * License compliance
    * Apply license
    * Trademarks

4) Technical assesment
    * Cleanup sensitive information
    * Code quality
    * Document code and process

5) Governance and process
    * Infrastructure including tests.
    * Communication channels.

6) Launch and maintain
    * Publish

7) Brancing and marketing
    * Release and promote
    * Community building

## Step 1: General considerations

__Alternatives:__ Opportunities to join an existing open source project.  
__Broader interest:__ How realistic it is that other companies want to 
participate in this project.  

## Step 2 :Business case assessment

__Define objectives:__ Clearly articulate the purpose, goals, and long-term 
vision of the open source project.  
__Roadmap:__ Develop a roadmap outlining milestones, features, and 
timelines for open sourcing the project.  
__Investment:__ Estimate the initial effort to make it open source.  
__Approval & commitment:__ Determine whether the key stakeholders 
agree with your plan.  

## Step 3: Legal assessment

__IP:__ Check whether open sourcing your project has an impact on your 
organizations intellectual property.  
__Choose a License:__ Select an appropriate open-source license (e.g., Apache 2.0) that aligns with your project's goals.  
__Compliance:__ Ensure all contributors and third-party dependencies 
comply with the chosen license.  
__Trademark:__ Determine whether any trademark-related decisions are 
necessary.  

## Step 4: Technical assessment

__Clean up:__ Remove privacy and security sensitive information.  
__Code Quality:__ Ensure sufficient code quality, including that coding style 
is consistent.  
__Basic Documentation:__ Maintain basic documentation for users and 
developers, including README.md, CONTRIBUTING.md, 
CODE_OF_CONDUCT.md, SUPPORT.md.   
__Copyright and license information:__ Make sure each file has a copyright 
& license header.  

## Step 5: Governance and Processes

__Project governance:__ Provide a PROJECT_GOVERNANCE.md describing the 
governance.  
__Infrastructure needs:__ Provide a code repository, bug reporting and code testing 
infrastructure that is accessible to the community.  
__Communication channels:__ Create supporting open communication channels like a 
mailing list, wiki and chat.  

## Step 6: Launch and maintain

__Publish the project:__ and start the open source development process.  
__DCO:__ Require Developer Certificate of Origin (DCO) for contributions.  
__Best practices:__ Adhere to best practices for development and project management.  
__Security:__ Pass the OpenSSF Best Practices Badge as a security baseline.  
__Changes:__ Communicate changes in the roadmap and governance clearly.  

## Step 7: Branding and marketing

__Responsible:__ Appoint a community advocate.  
__Marketing strategy:__ Create a marketing strategy to promote the community.  
__List:__ List the project on the organization's website.  
__Community building:__ Encourage an organize face-to-face activities for community 
building.  


# Licenses

Rumors has it, that Apache 2.0 has been veted to be used. We need to find documentation for this and include for future projects. Below is list of well known licenses that would fit Energinet.

| License Type           | Pros | Cons |
|------------------------|------|------|
| **MIT License**        | - Very permissive, allowing almost unrestricted use.  <br> - Simple and widely adopted.  <br> - Allows commercial use. | - No patent protection.  <br> - No requirement for modifications to be shared. |
| **Apache 2.0**         | - Includes an explicit patent grant, reducing legal risk.  <br> - Allows commercial use and modifications.  <br> - Requires modifications to include attribution. | - More complex than MIT due to additional clauses.  <br> - Some businesses may find patent clause restrictive. |
| **Business Source License (BSL)** | - Allows source code visibility while restricting certain commercial uses.  <br> - Can later convert to an open-source license (e.g., after X years).  <br> - Good for monetization while still sharing code. | - Not OSI-approved, so not considered true open source.  <br> - Can limit adoption by open-source communities.  <br> - Legal complexity around usage restrictions. |
| **No License**         | - Keeps the code private by default (all rights reserved).  <br> - Maintains full control over who can use the software. | - Legally, others cannot use or modify the code without explicit permission.  <br> - Discourages contributions and public adoption.  <br> - Potential legal uncertainty in different jurisdictions. |

# Similar companies that does open source

* https://www.alliander.com/en/open-source/ 
* https://github.com/eliagroup
* https://www.elia.be/en/grid-data/open-data