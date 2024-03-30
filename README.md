# Django-HTMX Quiz App

<p align="center">

  ![Screenshot01](Screenshot01.png)
  ![Screenshot02](Screenshot02.png)
  ![Screenshot03](Screenshot03.png)
  ![Screenshot04](Screenshot04.png)
  ![Screenshot05](Screenshot05.png)

</p>

---

- Create environment (only first time)

  - py -m venv .venv

- Activate python environment

  - source .venv/Scripts/activate

- Install dependencies (only first time)

  - pip install -r requirements.txt

- Run app

  - python manage.py runserver

- Visit website
  - http://localhost:8000

---

- To load extra data, create a new yaml file following quiz_data.yaml format and execute:
  - python manage.py loaddata quiz_data.yaml
    - New quiz data must have different/consecutive pk's for quiz, question, answer to avoid conflict with existing ones.
