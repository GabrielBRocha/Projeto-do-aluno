# Prática - Qualidade de Software em PHP

## Objetivo
Corrigir um código com erros e aplicar testes automatizados usando **PHPUnit** e **GitHub Actions**.

## Passos

1. Clone este repositório.
2. Instale as dependências:
   ```bash
   composer install
   ```
3. Rode os testes localmente:
   ```bash
   vendor/bin/phpunit
   ```
   - Você verá que **os testes falham** inicialmente.
4. Corrija o código em `src/Media.php` para que os testes passem.
5. Faça commit e push das alterações.
6. Verifique no GitHub se o pipeline (`Actions`) passou com sucesso.

## Critérios de avaliação
- Código corrigido e funcionando.
- Todos os testes passando.
- Pipeline verde no GitHub Actions.
- Documentação clara no README.

---
