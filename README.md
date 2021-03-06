<p align="center"><img src ="https://theme.zdassets.com/theme_assets/494154/baff07fc755fee5daf2e4a0f42b4552cad1ed68e.png" width="30%" height="30%" /></p>

##
# Vindi - WooCommerce

[![Licença do Software][badge-license]](LICENSE)
[![Última Versão no WordPress][badge-version]][link-version]
[![Avaliação do Plugin][badge-rates]][link-rates]
[![Downloads no Total][badge-downloads]][link-downloads]
[![Build Status](https://semaphoreci.com/api/v1/vindi/vindi-woocommerce-subscriptions/branches/master/shields_badge.svg)](https://semaphoreci.com/vindi/vindi-woocommerce-subscriptions)

# Descrição
O **Vindi WooCommerce** oferece uma solução completa para pagamentos únicos e assinaturas com cartão de crédito e boleto utilizando o [Woocommerce Subscriptions](https://www.woothemes.com/products/woocommerce-subscriptions/). Basta ter [uma conta habilitada na Vindi](https://app.vindi.com.br/prospects/new), para começar a cobrar seus clientes.

# Observações
- Ainda não são suportados Upgrades ou Downgrades de assinaturas.

A [Vindi](http://www.vindi.com.br/) é líder em cobrança recorrente no Brasil. Com centenas de clientes usando soluções como pagamento online, soluções de notas fiscais integradas, emissão de boletos por email e PDF, integrações com ERPs e diversos relatórios, a Vindi possibilita um sistema online completo para negócios de venda recorrente. Além disso, empresas podem usar o gateway de pagamento integrado ao billing recorrente ou para faturas avulsas.

# Requisitos
- PHP versão **5.6.x** ou superior.
- Um site com o WordPress instalado.
- Plugin [WooCommerce](https://wordpress.org/plugins/woocommerce/ "Plugin WooCommerce") instalado e habilitado.
- Plugin [WooCommerce Extra Checkout](https://wordpress.org/plugins/woocommerce-extra-checkout-fields-for-brazil/ "WooCommerce Extra Checkout") Fields for Brazil instalado e habilitado.
- Plugin [WooCommerce Subscriptions instalado](https://www.woothemes.com/products/woocommerce-subscriptions/ "WooCommerce Subscriptions") instalado e habilitado.
- Certificado Digital.
- Conta ativa na [Vindi](https://www.vindi.com.br "Vindi").

# Instalação
1. Envie os arquivos do plugin para a pasta wp-content/plugins, ou utilize o instalador de plugins do WordPress.
1. Ative o plugin.

# Configuração
1. Ative os Webhooks abaixo na Vindi em Configurações -> Webhooks:
    - Assinatura cancelada
    - Assinatura efetuada
    - Cobrança rejeitada
    - Fatura emitida
    - Fatura paga
1. Copie a Chave API que está localizada na Vindi em Configurações -> Chaves de acesso API.
1. De volta no WooCommerce Cole a Chave API na página administrativa do plugin WooCommerce -> Configurações -> Vindi:
1. Após salvar a Chave API o Woocommerce Subscriptions vai preencher o campo com sua URL de retorno + um token de segurança, copie essa URL e cole na Vindi em Configurações -> Webhooks -> URL
1. De volta no WooCommerce -> Configurações -> Finalizar Compra -> Cartão de crédito / Boleto Bancário.
1. Em WooCommerce -> Campos do Checkout, ative Tipo de Pessoa Física e Jurídica, RG e Inscrição estadual.
1. Em WooCommerce -> Configurações -> Assinaturas, marque as opções "Aceitar pagamento manual" e "Desabilitar renovação automatica"
1. Em WooCommerce -> Configurações -> Produtos -> Inventário, coloque um zero na opção "Manter estoque (minutos)".

>Para mais detalhes sobre a instalação de plugins no WordPress leia o tutorial [WordPress - Gerenciando Plugins](http://codex.wordpress.org/pt-br:Gerenciando_Plugins#Instalando_Plugins).

# Dúvidas
Caso necessite de informações sobre a plataforma ou API por favor siga através do canal [Atendimento Vindi](http://atendimento.vindi.com.br/hc/pt-br)

# Notas fiscais
Para emissão de notas fiscais, o mais indicado é a utilização de um plugin para emissão em seu Word Press.

# Contribuindo
Por favor, leia o arquivo [CONTRIBUTING.md](CONTRIBUTING.md).

Caso tenha alguma sugestão ou bug para reportar por favor nos comunique através das [issues](./issues).

# Changelog
Tipos de mudanças
- **Adicionado** para novos recursos
- **Ajustado** para mudanças em recursos existentes
- **Depreciado** para recursos que serão removidos em breve
- **Removido** para recursos removidos
- **Corrigido** para correção de falhas
- **Segurança** em caso de vulnerabilidades

Todas as informações sobre cada release pode ser  [CHANGELOG.md](CHANGELOG.md).

# Créditos
- [Vindi](https://github.com/vindi)
- [Todos os Contribuidores](https://github.com/vindi/vindi-woocommerce-subscriptions/contributors)

# Licença
GNU GPLv3. Por favor, veja o [Arquivo de Licença](LICENSE) para mais informações.

[badge-license]: https://img.shields.io/badge/license-GPLv3-blue.svg
[badge-version]: https://img.shields.io/wordpress/plugin/v/vindi-woocommerce-subscriptions.svg
[badge-rates]: https://img.shields.io/wordpress/plugin/r/vindi-woocommerce-subscriptions.svg
[badge-downloads]: https://img.shields.io/wordpress/plugin/dt/vindi-woocommerce-subscriptions.svg


[link-version]: https://wordpress.org/plugins/vindi-woocommerce-subscriptions/
[link-rates]: https://wordpress.org/support/view/plugin-reviews/vindi-woocommerce-subscriptions
[link-downloads]: https://wordpress.org/plugins/vindi-woocommerce-subscriptions/stats/
