# What is Spring data?

- Spring data is one of the umbrella project in spring ecosystem.
- Spring data helps you connect with different data sources example: SQL and NoSQL

--

# Which Spring data module used recently?
- I have used Spring data JPA for communicating with PQSql.

--

# How to define a repository using Spring Data JPA?
- We have extends CrudRepository which will provide basic crud operation. 
- For Example:  EmployeeRepository extends CrudRepository<Employee , Long>

--

# What is JPARepository in Spring Data JPA?
- It is advance version of repository which comes with addition features.  
- JPARepository offers features like : Batch Support, Pagination support.	

--

# How to customise database operation using Spring Data JPA repository?
- Spring Data JPA repository supports @Query("") annotation. 

---