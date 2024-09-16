FROM quay.io/astronomer/astro-runtime:12.1.0

RUN python -m venv snowenv1 && source snowenv1/bin/activate && \
    pip install --no-cache-dir dbt-snowflake && deactivate
