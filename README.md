### clean-architecture
#### 1. Interactor
	- input: requestModel
	- output: responseModel
	- includes
	  - controllers
	  - dto
	- collaborate with
	  - infrastructure
	  - adapter
	  - core usecase
#### 2. Infrastructure - DB, Framework
	- jpa
	  - mapper
	  - repository
	  - entity
	- config
#### 3. Adapter
	- transformer class from DTO to Model
	- Adapter from presentation to core
#### 4. Core
	- models - business model
	- usecases - whole business functionality
![Alt text](https://github.com/ravedien/clean-architecture/blob/master/Architercture%20Diagram.png?raw=true "Optional Title")

