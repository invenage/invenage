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
Unfortunately, the project does not have a business model at this moment as the project intend to require a large community with a lot of users and all the functions are free and available for everyone. Instead, if the project can grow large enough and having a strong will to stay continues, we may set up a foundation similar to the Wikipedia to accept donation with the characteristic of charity. Currently, there have no foundation or company registered in the name of ‘invenage’, but we reserve the right for doing so.

# About Development
## System architecture
### Frontend
We may create a webpage base on React to access backend API. The module will be containerized and use AWS for hosting it. Check [this repo](https://github.com/invenage/www.invenage.com) for more details.
### Backend
We target to create two APIs using dotnet 6 and host on AWS. One is for authorization and one is for the core functions.  Check [this repo](https://github.com/invenage/api.invenage.com) for more details for the core.
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
#### Target functionality
After complete this phase we expect to have an API for handling the information of items, allow users to add new items and update them. The API will also allow users register their connections for direct API access. There will also have an Authorization API allow users to login and grant access to the functions of core API.
#### Target rollout date
We target to complete this phase before early-2022.
### Phase 1
#### Target functionality
After complete this phase we expect to have a UI for accessing the functions of core API and Authorization API. We will also add more functions to core API in parallel, such as methods of creating the items, comments, rating and fuzzy search for items.
#### Target rollout date
We target to complete this phase before late-2022 depends on the progress of phase 0.
### Phase 2 and Support
#### Target functionality
This phase will work on the remining functions that not implemented in previous phases.
#### Target rollout date
We expect to have continuous deployment for this phase and support. Expect to have a minor release per 2 weeks for bug fixing and a major release per 3 months for new functions, but depend on the emergency level, the period can be shorter or longer.

# About Future
This project is the seed for other potential projects that in our point of views, sustainability should not be the only solution for the future of humanity. As entropy keep increasing under the laws of thermodynamic, the only way for humans to prevent extinction for following hundreds or million years is to get enough energy from the sun, i.e. a deep space solar array system, or a Dyson Sphere. Both are very expensive in cost currently but we still hope that from this project we can achieve a faster technology evolution or getting enough time for us to prepare, before it is too late.


<i>invenage, 2021
  
We invent, We manage</i>
