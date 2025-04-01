# Projeto Framework 2 

## Requirements
- PHP >= 8.1
- Composer
- MySQL or compatible database

## Instalação

1. Clonar o repositório:
```bash
git clone https://github.com/BrunoWagler/ProjetoTopicosEspeciais.git
```

2. Navegando no projeto:
```bash
cd ProjetoTopicosEspeciais
```

3. Instalando as depêndencias do php:
```bash
composer install
```

4. Configuração do .env:
- DB_DATABASE
- DB_USERNAME
- DB_PASSWORD

7. Gerar chave da aplicação:
```bash
php artisan key:generate
```

8. Executar migração:
```bash
php artisan migrate
```

10. Executar o php artisan serve:
```bash
php artisan serve
```
