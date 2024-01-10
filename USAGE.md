<!-- Start SDK Example Usage [usage] -->
```python
import mycommerce
from mycommerce.models import shared

s = mycommerce.Mycommerce()

req = shared.Pet(
    id=596804,
    name='string',
)

res = s.pets.create_pets(req)

if res.status_code == 200:
    # handle response
    pass
```
<!-- End SDK Example Usage [usage] -->