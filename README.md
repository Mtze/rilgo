# Rilgo Server

A simple _R_ead _i_t _L_ater service written in _go_

## Installation
TBA

## Usage
TBA

## Documentation 
See `docs` folder

## Developer Setup 
### Swagger 
To edit the API spec file, we suggest to use the swagger-editor: 
```bash
docker run -d -p 80:8080 swaggerapi/swagger-editor
```


## Roadmap

### Milestone 1 - It's alive!
- First stable version of API to 
   - store and retrieve items in the DB
   - add labels 
   - hierarchical labels
- Choose a DB implementation 
- Docker deployment for server 
- Documentation for basic usage, API and deployment

### Milestone 2 - Make it pluggable
- Add actions framework (e.g. Download)
    - An action is connected to a label 
    - Each item with that label will trigger the action 

### Milestone 3 - Give me all the data!
- Items that are in the database are downloaded and can be retrieved 
    - Texts/Articles are stored on disk and can be queried 
    - Videos are stored on disk 

### Milestone 4 - Maybe Friends?
- Implement a user management 
- Allow tags to be shared between users 


## Feature Ideas 
- RSS export of Tags 
- Project Lists 
- Full data encryption? 
    - How to share lists then?


## License
TBA

## Project status
rilgo is a toy project to learn new techniques and technologies. 
