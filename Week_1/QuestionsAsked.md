# Questions asked by new Djangonauts
<details>
<summary>Q.  I have a question about a ticket on Trac. On this particular one, https://code.djangoproject.com/ticket/18543, I am wondering why does it say 'new bug', when it was first opened 12 years ago?</summary>
<br>
A: The header of the ticket in track '#18543 new Bug' has a format like that more or less is  #<id> <status> <Type> , so in your example the status is new and the type is Bug 
The status is not time-based but it say to you that nobody is working on that ticket.
Other examples of different tickets can be:
#35809 closed Bug (fixed)
#35786 assigned Bug

Note: you can link in all the elements of the header and see other tickets with the same status or type. 
</details>


<details>
<summary>Q. Should we install anything locally to check formatting before committing to Django repo?</summary>
<br>
A. I believe the Django project now uses pre-commit which will force styles when you attempt to commit a change: https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/coding-style/#pre-commit-checks
</details>









