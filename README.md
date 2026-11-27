# devops-ci-app

Учебное Flask-приложение для практической работы № 10.

CI: Pylint → pytest → Docker build → smoke-test → GHCR.

Публикация образа выполняется только из main. В Pull Request выполняютсяпроверки без push.
- health endpoint: /health;
- образ: ghcr.io/zenesdk/devops-ci-app;
- основной workflow: .github/workflows/ci.yml.
