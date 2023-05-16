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

5. Créer le Web service Restfull qui permet de gérer des comptes
![Capture d'écran 2023-05-15 233041](https://github.com/oumaimabenaboud/micro_service/assets/120368654/38169c7f-0caa-489e-813e-5da839dfa1b7)
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

7. Générer et tester le documentation Swagger de des API Rest du Web service

8. Exposer une API Restful en utilisant Spring Data Rest en exploitant des projections
9. Créer les DTOs et Mappers
10. Créer la couche Service (métier) et du micro service
11. Créer un Web service GraphQL pour ce micro-service
