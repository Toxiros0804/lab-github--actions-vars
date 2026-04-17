# Respostas do Lab

## 1. Por que a Secret aparece como **?
Porque o GitHub mascara automaticamente secrets por segurança.

## 2. O job deploy_app consegue acessar BUILD_VERSION?
Não, porque cada job roda em um ambiente separado (runner diferente).
