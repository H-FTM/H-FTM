```bash

~ me@archbtw
❯ ls
hello.py Dev Cours Pentest Reverse Coucou Hi Hola 
```
```bash
~ me@archbtw
❯ cat hello.py
class HFTM:
    def __init__(self, name, passions, skills, bio=None):
        self.name = name
        self.passions = passions
        self.skills = skills
        self.bio = bio if bio is not None else "A simple guy exploring the digital world"

    def __str__(self):
      passions_l = ", ".join(self.passions) if self.passions else "no passions (sad)"
      skills_l = ", ".join(self.skills) if self.skills else "no specific skills listed (bad)"
      return f"Hey im {self.name}, a french student passionate in Computer Science from a long time, i love learning new things.\n" \
             f"I love: {passions_l}.\n" \
             f"My main skills are: {skills_l}"


if __name__ == "__main__":
    whoami = HFTM(
        name="Le N",
        passions=["Programming", "CyberSecurity", "Reverse Engineering", "Radio-Communications", "Linux"],
        skills=["Python", "Go", "JavaScript", "Linux"],
        bio="Focused On Learning everything possible",
    )
    print(whoami)
```
```bash
~ me@archbtw
❯ exit
```
