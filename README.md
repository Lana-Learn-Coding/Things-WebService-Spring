## Spring Things-WebService

- Support: POST,GET,DELETE,PUT,PATCH

- Json:
  - Thing:
    - name: string
    - generic: string
    - description: string
    - attribute: id (string|number)
  - Attribute:
    - name: string
    - description: string
    
- Api url:
  - /api/things
  - /api/attributes
  - /api/attributes/:id/things
  
- CrossOrigin: http://localhost:4200
