# Django REST Framwork (EDWIZ Interview Screening)
Student REST API using Django REST Framework

You are required to create a REST API to manage the records of Students and their enrolled courses.

Here's what your models.py would look like:
Courses:
  + course_name : CharField
  + source : CharField

Students:
  + name : CharField
  + enrolled_courses : ManyToManyField(Courses)


Now, serialize them to create the required output. The sample output is attached in sample.json file.
