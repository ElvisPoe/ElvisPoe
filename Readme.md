## Hi, I am Elvis Poenaru a Software Engineer

```python
class ElvisPoe:

    def __init__(self):
        self.username = 'elvispoe'
        self.name = 'Elvis Poenaru'
        self.position = 'Software Engineer'
        self.linkedin = 'https://www.linkedin.com/in/elvis-poenaru/'
        self.cv = 'https://elvispoe.github.io/ElvisPoenaru.pdf'
        self.code = {
            'backend': ['Laravel', 'Golang', 'Python', 'Django', 'FastAPI', 'PHP'],
            'database': [, 'MySQL', 'SQLite3', 'Mongo DB', 'Redis', 'PostgreSQL'],
            'devops': ['Docker', 'Linux', 'GitHub Actions', 'AWS'],
            'frontend': ['VueJs', 'NuxtJs', 'InertiaJS', 'Boostrap', 'Tailwind'],
            'tools': ['GIT', 'GitHub', 'Nginx'],
            'misc': ['TDD', 'SCRUM', 'SOLID', 'gRPC', 'ML']
        }
        self.architecture = ['DDD', 'MVC', 'Serverless', 'Microservices']

    def __str__(self):
        return f'{self.name} | {self.position}'


if __name__ == '__main__':
    me = ElvisPoe()
    print(me)


```
