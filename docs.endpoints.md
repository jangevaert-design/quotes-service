## REST Endpoints

* `/quotes`

    * `GET`
    
        * Request: (none)
        * Response: 
            * Body: `Quote[]`
    
    * `POST`
    
        * Request: 
            * Body: `Quote`
        * Response: 
            * Body: `Quote`
        
* `/quotes/search`

    * `GET`
    
        * Request:
            * Query: 
                * `q`: `String`
        * Response:
            * Body: `Quote[]` 
                
* `/quotes/{id}`

    * `GET`
    
        * Request
            * Path: 
                `id`: `long`
                
        * Response:
            * Body: `Quote`