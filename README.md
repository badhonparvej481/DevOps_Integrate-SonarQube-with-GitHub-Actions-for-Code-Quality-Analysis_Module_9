To Run This Application

- Create A virtual Env

  - python -m venv myvenv
  - virtualenv myenv (for linux)

- Activate The Virtual Env

  - source myenv/bin/activate (for linux)
  - myvenv/Scripts/activate

- Install Packages
- pip install -r requirements.txt

- For Run This Applications

  - python manage.py runserver 0.0.0.0:8000

- You may need some os level dependencies in linux
  - apt-get update && apt-get install -y --no-install-recommends \
    build-essential \
    zlib1g-dev \
    libffi-dev \
    libpq-dev \
    && apt-get clean && rm -rf /var/lib/apt/lists/\*

# 🚀 RapidCompetitions

A Django-based application containerized with Docker and deployed on Kubernetes via an AWS EC2 instance.
