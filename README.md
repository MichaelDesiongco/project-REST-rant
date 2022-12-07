#### Project-REST-Rant

| Method |   Path                  |  Purpose                                 |    
|--------|-------------------------|------------------------------------------| 
| GET    |  /                      |Home Page                                 |  
| GET    | /places                 |Places index page                         |   
| POST   | /places                 |create new place                          |   
| GET    | /places/new             |Form page for creating a new place        |   
| GET    | /places/:id             |Details about a particular place          |   
| PUT    | /places/:id/edit        |Update a particular place                 |   
| GET    | /places/:id/edit        |Form page for editing an existing         |   
| DELETE | /places/:id             |Delete a particular place                 |    
| POST   | /places/:id/rant        |Create a comment about a particular place |   
| DELETE | /places/:id/rant/:rantld|Delete a comment about a particular place |
| GET    |     *                   |404 page                                  |