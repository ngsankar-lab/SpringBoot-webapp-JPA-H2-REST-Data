# SpringBoot-webapp-JPA-H2-REST-Data
Spring boot app using JPA, H2, REST and Data

What is it?
----------
Spring boot app using JPA, H2 and REST Data
Created a repo interface by extending JpaRepository like below
@RepositoryRestResource(collectionResourceRel = "persons", path="persons")
public interface PersonRepo extends JpaRepository<Person, Integer>

With this you don't need to create any controller to perform CRUD Operations.
