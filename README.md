# SurveyBackend

📦survey
 ┣ 📂src
 ┃ ┣ 📂main
 ┃ ┃ ┣ 📂java
 ┃ ┃ ┃ ┗ 📂com
 ┃ ┃ ┃ ┃ ┗ 📂survey
 ┃ ┃ ┃ ┃ ┃ ┗ 📂survey
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂Auth
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜AuthController.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜AuthResponse.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜AuthService.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜LoginRequest.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜RegisterRequest.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂Config
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ApplicationConfig.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜SecurityConfig.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂Demo
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜DemoController.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂ExceptionHandler
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜GlobalExceptionHandler.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂Jwt
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜JwtAuthenticationFilter.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜JwtService.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂User
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜Role.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜User.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜UserController.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜UserDTO.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜UserRepository.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜UserRequest.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜UserResponse.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜UserService.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜surveyApplication.java
 ┃ ┃ ┗ 📂resources
 ┃ ┃ ┃ ┗ 📜application.properties
 ┃ ┗ 📂test
 ┃ ┃ ┗ 📂java
 ┃ ┃ ┃ ┗ 📂com
 ┃ ┃ ┃ ┃ ┗ 📂survey
 ┃ ┃ ┃ ┃ ┃ ┗ 📂survey
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜DemoJwtApplicationTests.java
 ┣ 📂target
 ┃ ┣ 📂classes
 ┃ ┃ ┣ 📂com
 ┃ ┃ ┃ ┗ 📂survey
 ┃ ┃ ┃ ┃ ┗ 📂survey
 ┃ ┃ ┃ ┃ ┃ ┣ 📂Auth
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜AuthController.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜AuthResponse$AuthResponseBuilder.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜AuthResponse.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜AuthService.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜LoginRequest$LoginRequestBuilder.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜LoginRequest.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜RegisterRequest$RegisterRequestBuilder.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜RegisterRequest.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📂Config
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ApplicationConfig.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜SecurityConfig.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📂Demo
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜DemoController.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📂ExceptionHandler
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜GlobalExceptionHandler.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📂Jwt
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜JwtAuthenticationFilter.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜JwtService.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📂User
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜Role.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜User$UserBuilder.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜User.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜UserController.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜UserDTO$UserDTOBuilder.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜UserDTO.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜UserRepository.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜UserRequest$UserRequestBuilder.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜UserRequest.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜UserResponse$UserResponseBuilder.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜UserResponse.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜UserService.class
 ┃ ┃ ┃ ┃ ┃ ┗ 📜surveyApplication.class
 ┃ ┃ ┗ 📜application.properties
 ┃ ┣ 📂generated-sources
 ┃ ┃ ┗ 📂annotations
 ┃ ┣ 📂generated-test-sources
 ┃ ┃ ┗ 📂test-annotations
 ┃ ┗ 📂test-classes
 ┃ ┃ ┗ 📂com
 ┃ ┃ ┃ ┗ 📂survey
 ┃ ┃ ┃ ┃ ┗ 📂survey
 ┃ ┃ ┃ ┃ ┃ ┗ 📜surveyApplicationTests.class
 ┣ 📜Readme.md
 ┣ 📜mvnw
 ┣ 📜mvnw.cmd
 ┗ 📜pom.xml