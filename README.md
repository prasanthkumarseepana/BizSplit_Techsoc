# Budget Splitting Application

We will be using React and ChakraUI for the frontend of this application. And for backend, we will be using Postgres database and it would be deployed on Azure.

Budget splitting app can be used to keep track of our budget and maintain a record of how much money is to be received by us or paid to others. We can see how much money is owed by and to us at multiple occasions.

## Key Features
1. Google sign in for users along with email ID login.
2. Users can create new events, add their friends who were involved in the event and the money owed by them.
3. It also has the feature of adding the items bought and the members among whom the items were shared so the budget can be split accordingly.
4. We can update the settlement by each member whenever the payment is made accordingly.

### Run Instructions

Assumptions- Node.JS and NPM are installed on the computer.

1)Starting the server
```
docker compose up
npm run build
npm run start

```
2)Starting the client
```
cd client
npm run build
npm run start
```
**Link**: 

## Screenshots

![techsoc1](https://user-images.githubusercontent.com/75605140/188299571-f0237201-3299-46bd-bd15-a705373260f7.jpeg)

![techsoc2](https://user-images.githubusercontent.com/75605140/188299569-010a605a-a4fc-4691-a984-dc975fea6eb1.jpeg)

![techsoc5](https://user-images.githubusercontent.com/75605140/188299763-268e9bb4-f665-41d1-a09b-0dc82ea843c2.jpeg)







### <b>Design Workflow:

![Screenshot (583)](https://user-images.githubusercontent.com/75605140/188299743-501cd404-2cf5-438e-8f0d-7d624b12b1b2.png)

### API Testing on **Postman**
![techsoc6](https://user-images.githubusercontent.com/75605140/188300693-2e5ad9e1-9620-4549-b12a-77c066509cce.jpeg)
![techsoc7](https://user-images.githubusercontent.com/75605140/188300692-4f755f97-b565-4005-872e-bb54db68c6ed.jpeg)
![techsoc8](https://user-images.githubusercontent.com/75605140/188300690-7a84f0ab-aa0d-4714-8aa1-88dc0c3afd0f.jpeg)
![techsoc9](https://user-images.githubusercontent.com/75605140/188300689-08c06485-8006-48a9-b71b-0f9f18360c7f.jpeg)
![techsoc10](https://user-images.githubusercontent.com/75605140/188300688-e739c32a-657a-4d08-8080-49b8cde6979f.jpeg)



Acknowledgements:

Prasanth- Designing on [Figma](figma.com), Mock data on Mockaroo

Madhav P- Working on Frontend using React and ChakraUI

Naveen-   Working on Backend using Express(NodeJS), Postgres database and API testing using Postman


