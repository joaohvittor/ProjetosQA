
```markdown

# Projetos de QA

Este repositório contém projetos de QA para sites populares, como Amazon, Americanas, eBay e Submarino. 
Cada diretório contém testes automatizados e documentação relacionada.

## Estrutura do Diretório

Abaixo está a estrutura de diretórios de cada projeto:

```

ProjetosQA
└── SitesPopulares
    ├── amazon
    │   ├── drivers           # Drivers de navegador para automação de testes
    │   ├── logs              # Logs gerados durante a execução dos testes
    │   ├── reports           # Relatórios dos testes executados
    │   ├── screenshots       # Capturas de tela de falhas e pontos importantes
    │   ├── src               # Código-fonte dos testes automatizados
    │   └── test_suits        # Suítes de teste organizadas
    ├── americanas
    │   ├── drivers
    │   ├── logs
    │   ├── reports
    │   ├── screenshots
    │   ├── src
    │   └── test_suits
    ├── ebay
    │   ├── drivers
    │   ├── logs
    │   ├── reports
    │   ├── screenshots
    │   ├── src
    │   └── test_suits
    └── submarino
        ├── drivers
        ├── logs
        ├── reports
        ├── screenshots
        ├── src
        └── test_suits

```

## Como Usar

1. **Clone o Repositório**:
   ```bash
   git clone https://github.com/joaohvittor/ProjetosQA.git
   cd ProjetosQA
```

2. **Navegue até o Diretório do Site**:
   Escolha o diretório do site que deseja testar, por exemplo:

   ```bash
   cd SitesPopulares/amazon
   ```
3. **Executar os Testes**:
   Para executar os testes, acesse a pasta `src` e utilize o comando apropriado, dependendo da configuração do seu projeto (ex: `npm test`, `pytest`, etc.).
4. **Verificar Relatórios**:
   Após a execução dos testes, verifique os relatórios na pasta `reports` para resultados detalhados.
5. **Logs e Capturas de Tela**:
   Caso ocorra alguma falha, verifique os logs na pasta `logs` e as capturas de tela na pasta `screenshots`.

## Contribuições

Contribuições são bem-vindas! Se você deseja colaborar, sinta-se à vontade para abrir um pull request ou relatar problemas.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

```

```
