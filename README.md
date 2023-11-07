Entities
* Student 
    * id
    * rating
    * first_name
    * last_name
* Rating
    * id
    * student_id
    * value

Operations
* Student
    * CREATE a new student
    * READ the student by id
    * READ all students
    * UPDATE the student by id
    * DELETE the student by id
* Rating
    * CREATE a new rating
    * READ the rating by id
    * READ the best students by value
    * READ all ratings
    * UPDATE the rating by id
    * DELETE the rating by id

Relationships
* Student
    * OneToMany Rating
* Rating
    * ManyToOne Student


