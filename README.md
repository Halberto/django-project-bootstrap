# {{ project_name|title }} Django Project #
## Prerequisites ##

- python >= 2.5
- pip
- virtualenv/wrapper (optional)

# create Django Project From template #
```bash
django-admin.py startproject --template https://github.com/artofhuman/django-project-bootstrap/zipball/master project_name
```

# Start procject #
```bash
virtualenv --no-site-packages ENV
source ENV/bin/activate
python manage.py runserver
```

# Project structure #
 * - {{ project_name }}
 * apps/ - Create you apps here ( pytnon manage.py startapp you_app_name {{ project_name }}.apps.you_app_name )
 * lib/  - Create libs here
 * templates/ - Put project templates here
 * media/ - For upload media files
 * static/ - For static files (css, js, etc.)
 * settings.py - For global settings
 * local_settings - For local settings (DB config, etc. )