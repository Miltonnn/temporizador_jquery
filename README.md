# Manipulando Atributos
Este é um exemplo simples de uma página HTML que demonstra a manipulação de atributos usando jQuery.
O código cria relógios dinâmicos com a capacidade de alterar a taxa de atualização através de botões.

## Estrutura do Projeto
O projeto é composto pelos seguintes arquivos:

- index.html: Contém a estrutura HTML da página.
- css/estilo.css: Arquivo de estilo externo para a formatação da página.
- js/jquery.js: Biblioteca jQuery para simplificar a manipulação do DOM.

## Funcionalidades
## Relógios Dinâmicos
Dois relógios são criados dinamicamente na página, cada um atualizando-se a cada intervalo de tempo especificado no atributo ´wm-relogio´.
Os relógios são exibidos no formato de data e hora local.

## Controles de Intervalo
Cada relógio possui botões "+" e "-" para aumentar e diminuir o intervalo de atualização, respectivamente.
Os botões permitem ajustar dinamicamente a frequência com que os relógios são atualizados.

## Manipulação de Atributos
O código jQuery incluído demonstra a manipulação de atributos nos elementos com o atributo wm-relogio. 
Ele inclui exemplos de leitura, alteração e remoção de atributos.

```javascript
// Exemplos de manipulação de atributos
$('[wm-relogio]').attr('opa') // Ler
$('[wm-relogio]').attr('opa', 3) // Alterar ou incluir um novo atributo
$('[wm-relogio]').attr({ opa: 1, novo: true }) // Incluindo vários atributos a partir de um objeto
$('[wm-relogio]').removeAttr('opa').removeAttr('novo') // Removendo atributos
```
## Como Usar
- Abra o arquivo index.html em um navegador da web.
- Observe os relógios dinâmicos e experimente os botões de controle para ajustar o intervalo de atualização.
- Explore os exemplos de manipulação de atributos no código jQuery.
