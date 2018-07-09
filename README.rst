pugip_site
==========

Getting Started
---------------

- Change directory into your newly created project.

    cd pugip_site

- Create a Python virtual environment.

    python3 -m venv env

- Upgrade packaging tools.

    env/bin/pip install --upgrade pip setuptools

- Install the project in editable mode with its testing requirements.

    env/bin/pip install -e ".[testing]"

- Configure the database.

    env/bin/initialize_pugip_site_db development.ini

- Run your project's tests.

    env/bin/pytest

- Run your project.

    env/bin/pserve development.ini

PUG-IP TODO
-----------

- UX Design
- Authentication/Authorization
- Resources page: Can be static, but needs a management portal.
- Project Ideas: Can be static, but needs a management portal.
- Meeting management
- Sign up page
- contact page
- Job postings
- Code Sharing: Ambitious
- Calendar: tied to meeting management
- Forum 
