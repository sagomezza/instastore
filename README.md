# InstaStore
Technical test for back-end developers.
 - [Instructions for developers](#instructions-for-developers)
 - [Requirements](#requirements)
 - [Improvements and trade offs](#improvements-and-trade-offs)
 
## Instructions for developers
 1. Fork this repo.
 2. Create a new branch.
 3. Understand the requirement and the user stories.
 4. Ask any questions to david.camargo@instaleap.io. (you have 1 chance, make it worth)
 4. As your first commit, copy your questions and David's answers, and design the "architecture" of your service. Upload a
    sketch/photo/readme, etc explaining how your service is going to work, and when do you think you can deliver
    the final product (we expect you to deliver it in less than 2 days).
 5. Have fun coding this challenge. Take into account that the data provided could have inconsistencies, make sure to handle them.
 6. If you find blockers, keep moving and get them solved later, please write them down in a markdown file inside your repo.
 7. Answer the [Improvements and trade offs](#improvements-and-trade-offs) section.
 7. Create a Pull Request (in your own fork), add 'davidcp90' as a reviewer, and send an email to david.camargo@instaleap.io

## Requirements
InstaStore is a microservice in charge of selecting the closest "convenience" store to deliver a groceries order to our B2B clients.

### Non-functional
- We expect you to deliver idiomatic code in a way that is easy to read and follows the accepted guidelines in your area of expertise.
- You should write it on Node.js with Express.js. Libraries, transpilers , etc are up to you.
- Endpoints are fast (less than 300ms).
- Endpoints respond error codes that makes sense to the case.
- Please provide documentation for the endpoints you create.

### Functional (user stories)
1. Our B2B clients should be able to consume an endpoint that provides them the following information:
  - storeId
  - storeName
  - isOpen
  - coordinates
  - nextDeliveryTime
2. The endpoint returns the closest store available
3. We need to keep track of each call to the endpoint

## Improvements and trade offs
1. What would you improve from your code? why?
2. Which trade offs would you make to accomplish this on time? What'd you do next time to deliver more and sacrifice less?
3. Do you think your service is secure? why?
4. What would you do to measure the behaviour of your product on a production environment?
