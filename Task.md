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


Now, serialize them to create the required output. The sample output is attached in <a href="https://github.com/iihsan/Django-REST-Task/blob/main/sample.json">sample.json</a> file.

Here are the some steps:
Create these models in models.py (you are free to add more columns if you want)
Create serializers in serializers.py (you are free to use any serializer)
Create their API endpoints in views.py (you are free to use any viewset)
Route these endpoints in urls.py

Hint: Nested serializer is required to create the sample output format.

You have 24 hours to submit this task or our HR will communicate you accordingly.

After completing your task, you will be required to submit it:
+ you can upload your task to public git repository and share your link at the given email address <a href="mailto:contact@iihsan.com
">contact@iihsan.com</a>
