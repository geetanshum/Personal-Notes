### Django password change and reset urls

#### In urls.py, add:
```
path('accounts/'include('django.contrib.auth.urls'))
```

Urls for passwords change and reset
- /accounts/password_change
- /accounts/password_reset
