## Hi there 👋

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

class HobbyProgrammer:

    def __init__(self):
        self.name = "Kyriakos Stefanakos"
        self.role = "Student at DSA / Hobby Programmer"
        self.languages_spoken = ["German", "English", "Greek", "Swiss German"]
        self.programming_languages = ["Python", "C# (learning Unity)"]

    def say_hi(self):
        print(f"Hi! I'm {self.name}, a {self.role}.")
        print("Languages I speak:", ", ".join(self.languages_spoken))
        print("Programming with:", ", ".join(self.programming_languages))
        print("Thanks for stopping by – enjoy exploring my work!")

# Run the script
me = HobbyProgrammer()
me.say_hi()

```
