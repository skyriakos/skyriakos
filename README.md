## Hi there 👋    <p align="center">  <img src="https://github.com/user-attachments/assets/3f0c1a00-def7-4edd-b1eb-0cdf08414278" width="240px"> </p>

           




```python


class HobbyProgrammer:

    def __init__(self):
        self.name = "Kyriakos Stefanakos"
        self.role = "Student / Hobby Programmer"
        self.languages_spoken = ["German", "English", "Greek", "Swiss German"]
        self.programming_languages = ["Python", "C# (learning Unity)"]

    def say_hi(self):
        print(f"Hi! I'm {self.name}, a {self.role}.")
        print("Languages I speak:", ", ".join(self.languages_spoken))
        print("Programming with:", ", ".join(self.programming_languages))
        print("Thanks for stopping by – enjoy exploring my work!")


me = HobbyProgrammer()
me.say_hi()

```

