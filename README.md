<h1 align="center">Traducao Magento 2 - pt-BR - Tezus</h1>

<hr>

<p align="center">
  <a href="#dart-sobre">Sobre</a> &#xa0; | &#xa0; 
  <a href="#checkered_flag-instalação">Instalação</a>
</p>

<br>

## :dart: Compatibilidade ##

Projeto de tradução do Magento 2 exclusivo da Tezus Ecommerce.
- [x] Magento 2.3.x
- [x] Magento 2.4.x

## :checkered_flag: Instalação ##

### Instalação Manual

```bash
# Clone este repositório
$ git clone https://github.com/tezusecommerce/traducao-tezus

# Copie a estrutura de pasta do reposiório /app/i18n/Tezus/pt_BR/
# Para a pasta /app da sua loja 
# Depois faça o deploy e limpe o cache
$ php bin/magento setup:static-content:deploy pt_BR -f
$ php bin/magento cache:clean
```

<hr>

### Habilitando a Tradução no Backend
1. Entre no painel admin da loja
2. Clique no boneco que representa a conta e depois em "Account Settings"
3. Troque a Interface Language do Inglês para o Português e salve.
4. Se a tradução não pegar instantaneamente limpe os caches.

<a href="#top">Voltar para o topo</a>
