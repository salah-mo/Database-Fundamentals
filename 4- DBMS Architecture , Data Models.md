# **Chapter 1: Introduction**
## DBMS Architecture.
    (Consist of 3 Schema Architecture)

### External Schema.(Higher Level)
    The final set of data that the user will see.
    
### Conceptual Schema.(Mid Level)
    Defines database structures such as tables and constraints

### Physical Schema.(Lower Level)
    The data is saved in files.
    Represents the location of the data files in the disk.
    How is the data represented in the database?

## Mappin.
    It is the process of transforming requests and results between levels.
    
## Data Indeprndence.
    When I Change a Specific Schema this change doesn't need to be reflected in the Schema at the higher level.

## Data Models.

### Logical Model
    - basis for developing the physical model.
    - Logical data models are used to visualize data entities, attributes, keys, and relationships.

### Physical Model.
    Physical data models are used to visualize the physical structure of databases and data files.

### Difference Between Logical and Physical Data Model
    A logical data model is a model that describes data as much as possible, without regard to how they will be physically implemented in the database.
    A physical data model is a model that represents how the actual database is built.