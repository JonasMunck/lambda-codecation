# AWS Lambda, zappa

(and django)

---

- Function as a Service
- "Serverless"

---

You as a developer don't have to care about servers and all that comes with that.
Scalability, random crashes, ip configs, update OS,...

---

- Upload code to lambda
- AWS lambda will run it
- you get a result
- pay only for execution time

---

### Zappa

- python wsgi-wrapper around lambda
- "serverless" web hosting for your Python apps

---

### Django 

Web framework written in Python

---

```
python manage.py runserver
```

```
zappa init
zappa deploy dev
```

---

## Business case

- Ticket website
- highly scalable
- payments -- high SLA



