# Micro services
1. Créer un projet Spring Boot avec les dépendances Web, Spring Data JPA, H2, Lombok
![Capture d'écran 2023-05-15 221229](https://github.com/oumaimabenaboud/micro_service/assets/120368654/02ac3d92-0004-44fb-820d-c99d5a85cc03)

2. Créer l'entité JPA Compte

![Capture d'écran 2023-05-15 224940](https://github.com/oumaimabenaboud/micro_service/assets/120368654/3c2aec23-6ea3-4de5-b39e-2c647f12cbe4)


3. Créer l'interface CompteRepository basée sur Spring Data
![Capture d'écran 2023-05-15 222714](https://github.com/oumaimabenaboud/micro_service/assets/120368654/05661bc5-e13b-4a5d-afe7-f7d491ecf8eb)

4. Tester la couche DAO
![Capture d'écran 2023-05-15 222548](https://github.com/oumaimabenaboud/micro_service/assets/120368654/ad9bacbe-b79d-443f-a436-c66075799bb0)
![Capture d'écran 2023-05-15 224626](https://github.com/oumaimabenaboud/micro_service/assets/120368654/21a25c27-a002-45c0-9ca2-6f38aae0af9b)
![Capture d'écran 2023-05-15 224903](https://github.com/oumaimabenaboud/micro_service/assets/120368654/3d53149a-c291-4c3c-9e9c-9060092f639d)

5. Créer le Web service Restful qui permet de gérer des comptes
- Liste des comptes
![Capture d'écran 2023-05-15 233041](https://github.com/oumaimabenaboud/micro_service/assets/120368654/38169c7f-0caa-489e-813e-5da839dfa1b7)
- Find account by Id
![Capture d'écran 2023-05-15 233800](https://github.com/oumaimabenaboud/micro_service/assets/120368654/d13f2bcc-b305-4d08-82e7-b62fecf8fb3c)

6. Tester le web micro-service en utilisant un client REST comme Postman
- Liste des comptes
![Capture d'écran 2023-05-16 000127](https://github.com/oumaimabenaboud/micro_service/assets/120368654/b620654e-f8fe-4074-9b8d-4d4bb7bdc135)
- Find account by Id
![Capture d'écran 2023-05-16 000235](https://github.com/oumaimabenaboud/micro_service/assets/120368654/54fa6eee-0d09-4c94-9f90-8f2352c0adbf)
- Save new account
![Capture d'écran 2023-05-16 001933](https://github.com/oumaimabenaboud/micro_service/assets/120368654/13a79119-322e-488c-9c98-66af947530a8)
- Update account info
![Capture d'écran 2023-05-16 001952](https://github.com/oumaimabenaboud/micro_service/assets/120368654/e6472709-1265-4da6-8c9b-3b7e36e57998)

7. Générer et tester la documentation Swagger du API Rest du Web service
![image](https://github.com/oumaimabenaboud/micro_service/assets/120368654/8e5b7eba-678d-4436-aa21-aecc4f755cad)
![image](https://github.com/oumaimabenaboud/micro_service/assets/120368654/aaf31962-957c-4584-bbc8-6e3b80464148)
- Importer la documentaion OpenAPI dans Postman
![image](https://github.com/oumaimabenaboud/micro_service/assets/120368654/968b22d2-af90-46c0-be0a-35b63d086932)

8. Exposer une API Restful en utilisant Spring Data Rest en exploitant des projections
- Utilisation de Spring Data Rest
![image](https://github.com/oumaimabenaboud/micro_service/assets/120368654/3f23c2dd-f8cb-42c5-bd3f-fc53347b7045)
- Search using "findByType"
![image](https://github.com/oumaimabenaboud/micro_service/assets/120368654/7d742709-bafa-458f-8af9-12c3d591632b)
- Projection
![image](https://github.com/oumaimabenaboud/micro_service/assets/120368654/99fb0e1a-b608-4f0c-bf0f-620a1e48a9d3)
- Search using "byType"
![image](https://github.com/oumaimabenaboud/micro_service/assets/120368654/e0b2c396-9d71-43ab-a78e-2f37b168136c)

9. Créer les DTOs et Mappers
- Save new account using DTOs
![image](https://github.com/oumaimabenaboud/micro_service/assets/120368654/4fb9fff8-7bec-4667-846e-d2a81b3fb36a)

![image](https://github.com/oumaimabenaboud/micro_service/assets/120368654/e938205a-e136-4fcd-83c3-271d02752aae)
- Save new account using Mappers
![image](https://github.com/oumaimabenaboud/micro_service/assets/120368654/52c1bc57-869e-441e-8df2-dda8d0c01789)

![image](https://github.com/oumaimabenaboud/micro_service/assets/120368654/f51e2990-4f37-4775-aacd-a41f73537558)

10. Créer la couche Service (métier) du micro service
![image](https://github.com/oumaimabenaboud/micro_service/assets/120368654/f0ba00f7-401a-491d-ad30-2472965f9173)

11. Créer un Web service GraphQL pour ce micro-service
- Test du Webservice using GrahiQL : Liste des comptes
![image](https://github.com/oumaimabenaboud/micro_service/assets/120368654/ace2badd-a62c-4019-b7fc-1b9d652d01f6)
- Test du Webservice using GrahiQL : Find account by Id
![image](https://github.com/oumaimabenaboud/micro_service/assets/120368654/35c6fc4b-36ab-4527-a2a9-678ee5515e68)
- Ajout de l'Exception Handler
![image](https://github.com/oumaimabenaboud/micro_service/assets/120368654/1a11a723-27c9-4066-a723-afa742a91d4a)
- Test du Webservice using GrahiQL : Add new account
![image](https://github.com/oumaimabenaboud/micro_service/assets/120368654/3cd59bd4-0b01-4d01-b301-988107c4c912)
![image](https://github.com/oumaimabenaboud/micro_service/assets/120368654/62c6b6b3-4c17-49ff-9844-d91ba883d68a)
