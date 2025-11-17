## Hi there 👋     ![giphy](https://github.com/user-attachments/assets/9490de4a-d1c6-4a29-a462-252772d17ea4)
            


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

