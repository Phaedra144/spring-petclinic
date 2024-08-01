# PetClinic Java Spring Application with React

This is an exercise project deepening my React knowledge combined with refreshing my Java Spring knowledge.
<img width="1385" alt="Screenshot 2024-07-31 at 13 57 57" src="https://github.com/user-attachments/assets/817f5b64-4e32-4ab9-b575-6e3ed29c18e0">

## Installation

[Backend readme](https://github.com/Phaedra144/spring-petclinic-with-react/tree/main/backend#readme)

[Frontend readme](https://github.com/Phaedra144/spring-petclinic-with-react/tree/main/frontend#readme)

## Usage

**Backend**

Useful links to set up java environment in vscode:
- https://code.visualstudio.com/docs/java/java-tutorial
- https://code.visualstudio.com/docs/java/extensions

Sample server start with postgres:
`docker-compose --profile postgres up`
`./mvnw spring-boot:run -Dspring-boot.run.profiles=postgres`

**Frontend**

node version v20.15.0

`nm run dev`


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

### Next steps

- Testing rest controllers
- Toggle navbar in responsive screens
- Extend features with:
  - Pet creation/modification
  - Visit creation
- Service layer between repository and controller
- Remove thymeleaf and mvc controllers
- Return with DTOs in rest controllers
- Login and authentication
- Contanerisation and deployment
