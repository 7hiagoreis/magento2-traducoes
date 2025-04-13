# 🇧🇷 Traduções Magento 2 - pt_BR

Este repositório contém arquivos de tradução em português do Brasil para o Magento 2 e módulos de terceiros, como os da **Amasty**, entre outros.

## 📁 Estrutura

Os arquivos seguem a estrutura:

/<Vendor>/<Module>/i18n/pt_BR.csv


### Exemplos:
- `Magento/Catalog/i18n/pt_BR.csv`
- `Amasty/Blog/i18n/pt_BR.csv`
- `Amasty/SEO/i18n/pt_BR.csv`

## 🛠 Como usar

1. Faça o download ou clone o repositório:
   ```bash
   git clone https://github.com/7hiagoreis/magento2-traducoes.git
Copie os arquivos para seus respectivos módulos dentro da pasta app/code (ou vendor, se for extensão de terceiros).

2. Copie os arquivos para seus respectivos módulos dentro da pasta app/code (ou vendor, se for extensão de terceiros).

3. Execute os comandos do Magento:

```bash bin/magento cache:flush 
   bin/magento setup:static-content:deploy pt_BR -f





💡 Dica
Você pode automatizar esse processo com symlinks ou scripts para facilitar atualizações futuras.

🙌 Contribuições
Pull requests são bem-vindos! Se quiser contribuir com correções ou novas traduções, sinta-se à vontade.

📄 Licença
Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

