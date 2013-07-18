# Code

# Questions

** Questions should be answered with the simplest, most barebone solution possible.

###1. Arrays

	`array = ["Blake","Ashley","Jeff"]`

	a. Add a element to an array

	b. Write a statement to print out all the elements of the array.

	c. Return the value at index 1.

	d. Return the index for the value "Jeff".

###2. Hashes

 	`instructor = {:name=>"Ashley", :age=27}`

	a. Add a new key for location and give it the value "NYC".
	
	b. Write a statement to print out all the key/value pairs in the hash

	c. Return the name value from the hash.

	d. Return the key name for the value 27.

###3. Nested Structures

	```ruby
	school = { :name => "Happy Funtime School",
		  :location => "NYC"
		  :instructors => [ {:name=>"Blake",
							  :subject=>"being awesome"	},
							  {:name=>"Ashley",
							  :subject=>"being better than blake"},
							  {:name=>"Jeff",
								:subject=>"karaoke"}]
		  :students => [ {:name => "Marissa",
						:grade => "B"},
						{:name=>"Billy",
						:grade => "F"},
						{:name => "Frank",
						:grade => "A"},
						{:name => "Sophie",
						:grade => "C"}
						]
		}
	```

	a. Add a key to the school hash called "founded_in" and set it to the value 2013. 

	b. Add a student to the school's students' array.

	c. Remove "Billy" from the students' array.

	d. Add a key to every student in the students array called "semester" and assign it the value "Summer".

	e. Change Ashley's subject to "being almost better than Blake"

	f. Change Frank's grade from "A" to "F".

	g. Return the name of the student with a "B".

	h. Return the subject of the instructor "Jeff".

	i. Write a statement to print out all the values in the school. ***FLAG

###4. Methods

	**Note: You will need to pass the school variable to each of these methods to include it in scope.

	a. 	
		i. Create a method to return the grade of a student, given that student's name.
		ii. Then use it to refactor your work in 3.i. 

	b. 
		i.Create a method to udpate a instructor's subject given the instructor and the new subject.
		ii. Then use it to update Blake's subject to "being terrible".

	c. 
		i. Create a method to add a new student to the schools student array.
		ii. Then use it to add yourself to the school students array.

	d. 
		i. Create a method that adds a new key at the top level of the school hash, given a key and a value. 
		ii. Then use it to add a "Ranking" key with the value 1.

#5. Object Orientation

	a. Create a bare bones class definition for a School class.

	b. Define an initialize method for the School class.

		i. Give your School class the instance variables: name, location, ranking, students, instructors.
		**NOTE: These variables should be of the same type as they are in the hash above.

		ii. Rewrite your initialize method definition to take a parameter for each instance variable. 

		iii. Initialize each instance variable with the value of the corresponding parameter.

	c. Create an attr_accessor for name, location, instructors, and students. Create an attr_reader for ranking.

	d. Create a method to set ranking, given a ranking value.

	e. Create a method to add a student to the school, given a name, a grade, and a semester.

	f. Create a method to remove a student from the school, given a name.

	g. Create an array constant SCHOOLS that stores all instances of your School class.

	h. Create a class method `reset` that will empty the SCHOOLS constant.

## blah

	a. Create a Student class.

	b. Refactor your School instance methods to treat Students as an array of objects instead of an array of hashes.

	c. Create a method in the School class that finds a student by name and returns the correct Student object.	


## Enumerables

