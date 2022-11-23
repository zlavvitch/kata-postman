### **Практическая задача 4.4.9 (Postman)**

---

</br>

1. **Регистрируемся (Registration)**

```
{
  "user": {
    "username": "zla",
    "email": "zla@ya.ru",
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzN2U3OWI4MjA3NTk0MWIwMGU0NmJiMiIsInVzZXJuYW1lIjoiemxhIiwiZXhwIjoxNjc0NDE3MDgwLCJpYXQiOjE2NjkyMzMwODB9.C5M8M5JPfCqS7o-0-a4PjQsOqm1fUSzGynPs5JO9TBg"
  }
}
```

2. **Логинимся (Authentication)**

```
{
  "user": {
    "username": "zla",
    "email": "zla@ya.ru",
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzN2U3OWI4MjA3NTk0MWIwMGU0NmJiMiIsInVzZXJuYW1lIjoiemxhIiwiZXhwIjoxNjc0NDIwOTI0LCJpYXQiOjE2NjkyMzY5MjR9.5FEYOok-lfaPJC-77CFOB9LaoizP45M2jvgiwPdh_7k"
  }
}
```

3. **Используя заголовок авторизации получить данные текущего пользователя (Endpoints -> Get Current User)**
```
Authorization -> Token eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzN2U3OWI4MjA3NTk0MWIwMGU0NmJiMiIsInVzZXJuYW1lIjoiemxhIiwiZXhwIjoxNjc0NDIwOTI0LCJpYXQiOjE2NjkyMzY5MjR9.5FEYOok-lfaPJC-77CFOB9LaoizP45M2jvgiwPdh_7k
```

```
{
  "user": {
    "username": "zla",
    "email": "zla@ya.ru",
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzN2U3OWI4MjA3NTk0MWIwMGU0NmJiMiIsInVzZXJuYW1lIjoiemxhIiwiZXhwIjoxNjc0NDIwOTUwLCJpYXQiOjE2NjkyMzY5NTB9.CBiNSmDPvt_BNyPLoqAFZ1PvXnYasTsByWp_YocHSUI"
  }
}
````
