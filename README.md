
```python
class JxTx:

    def __init__(self):
        self.username = 'jthorpe6'
        self.name = 'Joe Thorpe'
        self.web = 'https://jxtx.gitlab.io'
        self.twitter = '@JxTx__'
        self.editor = 'Emacs'
        self.projects = 'https://gitlab.com/JxTx'
        self.code = {
            'frontend': ['HTML', 'CSS', 'JavaScript'],
            'backend': ['Python', 'PHP', 'Flask', 'NodeJS', 'C#'],
            'database': ['PostgreSQL', 'MySQL', 'SQLite3'],
            'devops': ['Docker', 'Vagrant', 'Gitlab Pipelines']
        }
        self.os = ['Debian', 'Mac OSX', 'Microsoft Windows']
        
    def __str__(self):
        return self.name


if __name__ == '__main__':
    me = JxTx()
```
