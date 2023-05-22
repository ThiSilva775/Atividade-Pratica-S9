GET /api/exercises - recuperar a lista de exercícios disponíveis

POST /api/exercises - criar um exercício

GET /api/exercises/{exercise_id} - recuperar informações de um 
exercício específico por ID

PUT /api/exercises/{exercise_id} - atualizar informações de um exercício específico por ID

DELETE /api/exercises/{exercise_id} - excluir um exercício específico por ID

GET /api/workouts - recuperar a lista de treinos disponíveis

POST /api/workouts - criar um novo treino

GET /api/workouts/{workout_id} - recuperar informações de um treino específico por ID

PUT /api/workouts/{workout_id} - atualizar informações de um treino específico por ID

DELETE /api/workouts/{workout_id} - excluir um treino específico por ID

GET /api/users/{user_id}/workouts - recuperar a lista de treinos de um usuário específico por ID

POST /api/users/{user_id}/workouts -icionar um novo treino para um usuário específico por ID

GET /api/users/{user_id}/workouts/{workout_id} - recuperar informações de um treino específico de um usuário por ID

PUT /api/users/{user_id}/workouts/{workout_id} - atualizar informações de um treino específico de um usuário por ID

DELETE /api/users/{user_id}/workouts/{workout_id} - excluir um treino específico de um usuário por ID

Com esses endpoints, podemos criar uma API REST completa para gerenciar exercícios e treinos de uma academia. É importante lembrar de incluir autenticação e autorização para garantir a segurança dos dados dos usuários. Além disso, é recomendado seguir as boas práticas de design de API REST, como utilizar os verbos HTTP corretos e retornar códigos de status apropriados.