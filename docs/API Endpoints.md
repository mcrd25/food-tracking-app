This table lists all RAILS based API ENDPOINTS for the food tracking app.

+----------------+-------------------------------------------------------------------------------------+
|**ENDPOINTS**   |**FUNCTIONALITY**                                                                    |
+----------------+-------------------------------------------------------------------------------------+
|POST /signup    |Allows visitor to sign up as a user                                                  |
|                |                                                                                     |
|POST /login     |Allows a registered user to login and use the app and returns a token when successful|
|                |                                                                                     |
|GET /login      |Allows logged in user to logout                                                      |
|                |                                                                                     |
|POST /food      |Allows logged in users to create a new food item entry                               |
|                |                                                                                     |
|GET /food       |Gets all food item entries                                                           |
|                |                                                                                     |
|GET /food/:id   |Gets food item entry                                                                 |
+----------------+-------------------------------------------------------------------------------------+
|PUT /food/:id   |Allows logged in user to update their food item                                      |
|                |                                                                                     |
|DELETE /food/:id|Allows logged in use to delete their food item                                       |
+----------------+-------------------------------------------------------------------------------------+