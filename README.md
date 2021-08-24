# About this repo
This repo is for documenting the 'invenage' project. It will contain the basic idea about 'invenage' and the macro view of the system implementation. If you think you need more information or clarification, you can create an issue and we will try our best to describe the principle of the project 'invenage'. Thank you for spending your time on reading this.

# About invenage
## Background
The word 'invenage' is the short form of 'invention management system'. The purpose for the project is to provide users with an alternative view on the invention that we human already created and in use. The system is combining some of the hot topics for recent years in order to stand out from the apps that having similar functionality on the market, i.e. Sustainability, AI and IoT.
## Problem
Currently, we do not have the full picture on how to make the products on our hands. Those methods are holding by the companies or the specialists in order to preserve economic advantage to earn as much money as possible. It is a good approach for rising investment or funding but it can go better if they can share it to the public, just like the cases of open source projects. This project is not going to break the laws of patents and trademarks but instead summarizing the knowledge and inventions that already exists to allow users to benefit from different areas, which will mention below.
## Benefits
### Sustainability
The product owners are hiding the choice of usage of the raw materials from users. Not using environmental friendly materials but as low cost as possible, until it raises the debates and regulation take involved. By allowing public to take part in the production, they can monitor and request for changes if that production methods are harmful to environment or can achieve a higher standard of sustainability. The final approach is to create a circular economy through the effort of global users.
### Education
By providing the methods of constructing some funny products, it can help to raise interest of innovation for the users. The more people involve, the faster technology evolve. It can also help for spreading the concepts and laws of physics, chemistry and mathematics that take part in the products.
### Inheritance
The methodology for some unpopular products may be lost over time. By recording that, it will help the people to understand the history and evolving path of the products, getting inspiration and learn from the mistake.
### Research
Do not reinvent the wheel. By sharing research processes and results, it can help to reduce the consumption of the materials and time for repeat the experiments. The tasks can also divided across the global which can take the advantages of strengths and weaknesses of different parties.
### IoT
By capturing the data of the products from production, delivery and consumption, the users can explore the lifecycle of the products from the beginning of the raw materials and provide an alternative to reduce the energy consumption.
### AI
With the methods of how the products being produced, an AI can learn from it and try to simulate the process of creation, discover the imperfect parts in the existing methods and making improvement suggestions. Providing the access of using tools, the AI will learn to manufacture the products by their own. Combine with the data from IoT, it can help to manage the resources from real demand and supply forecast.
### CICD (Cloud manufacturing)
With the AI already capable for manufacturing, the users can design the products then send the methodology to AI to create a demo product for the new items. Once the tests are passed, it can be deploy to production and share the results for others.
## Challenges
The project may face some challenges from different areas and stakeholders. The challenges include but not limit to:
* Personal Security
* Social Security
* National Security
* Conflict of interest

Rules and regulations may apply to the system and hence reducing its usage and functionality. We will continuously monitor the status of the system and hope it can overcome those challenges and deliver a healthy and legal system to all the users.
## Business Model
Unfortunately, the project dose not have a business model at this moment as the project intend to require a large community with a lot of users and all the functions are free and available for everyone. Instead, if the project can grow large enough and having a strong will to stay continues, we may set up a foundation similar to the Wikipedia to accept donation with the characteristic of charity. Currently, there have no foundation or company registered in the name of ‘invenage’, but we reserve the right for doing so.

# About Development
## System architecture
### Frontend
We may create a webpage base on React to access backend API. The module will be containerized and use AWS for hosting it. Check [this repo]() for more details.
### Backend
We target to create two APIs using dotnet 6 and host on AWS. One is for authorization and one is for the core functions.  Check [this repo]() for more details for the core.
### Database
We may use AWS MongoDB for main data storage and Redis or local Memory cache for cached data.
## Functions
The system will have following functions and subject to add more base on requirement changes. The description may not written in details and just for reference only.
* Login services with compatible for hiding user name.
* Create or update an item with some descriptions.
* Create or update the methods for the items.
* Search the items.
* Comment or rate the items or comments.
* Declare patents and copyrights of the item. 
* Record the flow of the items.
* Allow direct API access.
## Schedule
### Phase 0
This phase will focus on the core API system and implement the functions listed above. Target launch data should be no earlier than mid-2022. The code will be open sourced that allow community to apply changes.
### Phase 0.5
This phase will focus on authorization API system to control access. The implementation will start after completed the phase 0 and may require three months for develop and test. This system will not be open sourced as it contains sensitive information and not affect any core functions.
### Phase 1
This phase will target on the frontend system. If we have enough resources, it may run in parallel with phase 0 and phase 0.5. We will see if we can complete the development and let the project progress in production state in mid-2023.
### Phase 2
This phase is to upgrade the system for both frontend and backend if some functions are missing and improvements are needed. 

# About Future
This project is the seed for other potential projects that in our point of views, sustainability should not be the only solution for the future of humanity. As entropy keep increasing under the laws of thermodynamic, the only way for humans to prevent extinction for following hundreds or million years is not go to Mars but get enough energy from the sun, i.e. a deep space solar array system, or a Dyson Sphere. Both are very expensive in cost currently but we still hope that from this project we can achieve a faster technology evolution or getting enough time for us to prepare, before it is too late.


<i>invenage, 2021
  
We invent, We manage</i>
