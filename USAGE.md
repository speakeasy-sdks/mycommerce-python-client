<!-- Start SDK Example Usage -->
```python
import mycommerce

s = mycommerce.Mycommerce()


res = s.pets.create_pets()

if res.status_code == 200:
    # handle response
    pass
```
<!-- End SDK Example Usage -->