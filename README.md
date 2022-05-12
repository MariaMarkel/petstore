# Petstore

CRUD operations using Swagger Petstore & Postman:

- POST – adds a new pet to the store
- GET – confirms the pet has been added
- PUT – updates the current pet's category ID
- GET – confirms pet's category ID has been updated
- POST – updates the current pet with form data
- GET – confirms name & status have been updated
- POST – uploads image
- DELETE – deletes the current pet
- GET – confirms the pet has been deleted
- GET – finds all pets by status "available"

# To run this collection with Newman:
 1. Install Newman using the following command*:
  ```bash
  npm install -g newman
  ```
  *[node.js must be installed](https://nodejs.org/en/download/) on your machine
 
 2. In Command prompt run the following command: 
 ```bash
    newman run https://www.getpostman.com/collections/8e43d62056c6ecfc38f8
```

# To import collection & environment:
1. This project -> PetStore.postman_collection.json -> Copy raw contents 
2. Postman -> Import -> Raw Text
3. This project -> petStore.postman_environment.json -> Copy raw contents 
4. Postman -> Import -> Raw Text
5. Postman -> Select PetStore collection you've just imported -> Run collection to see the detailed results
