
-----
```python
from Github import GithubReadme

class Gaurav:
    def __init__(self):
        self.name = "Gaurav!"
        self.age = "17"
        self.location = "Mumbai , Maharashtra"
        self.work = "Developer"
        self.system = "Windows 10, x64"

    def skills(self):
        self.languages = {
            "main": ["Python", "Java", "Node.js", "C#", "HTML/CSS/JS"],
            "learning": ["golang", "C++" ,"Php"]
        }

        self.works = [ 'ai' , 'web' , 'bug hunter', 'etc...']
    
    def social_media(self):
        self.instagram = "gaurav_.491"
        self.telegram = none
        self.sellix = none
        self.onlyfans = None


if __name__ == "__main__":
    readme = GithubReadme.create(Gaurav)
```
-----
