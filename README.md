# NonoJapan in Django

### Built fake nonojapan with django

```python
class Nojapan(models.Model):

    product = models.CharField(max_length=100)
    replace = models.CharField(max_length=100)
    info = models.CharField(max_length=100)
```