### rsschool-cv
# Shvoren Vladislav
## My contacts
- mail: shvorenvladislav@mail.ru
- [github:](https://github.com/VlaShvor)
- location: Minsk, metro station Petrovshchina
## About me
graduated from BSEU with high academic achievement, GPA - 8,8; a hardworking and responsible person; ready to gain new skills and knowledge.
## My skills
- python (NumPy, Pandas)
- HTML
- Git
## Code exapmle

```python
class Matrix:
    
    def __init__(self, a):
        self.a = copy.deepcopy(a)

    def __mul__(self, other):
        if isinstance(other, int) or isinstance(other, float):
            row = self.size()[0]
            line = self.size()[1]
            b = [[self.a[i][j] * other for j in range(line)]
                 for i in range(row)]
        elif isinstance(other, Matrix):
            row = self.size()[0]
            line = self.size()[1]
            line1 = other.size()[1]
            b = [[sum([self.a[i][j] * other.a[j][y] for j in range(line)
                      for y in range(line1)] for i in range(row)]
        return Matrix(b)

        def size(self):
            return len(self.a), len(self.a[0])
```

## Experience
## Education
- The Belarus State Economic University, economist-analyst
## Language
- English - B2
- Russian - native