# 📍 Busca de Locais Próximos

Este é um projeto simples de aplicação web que permite aos usuários buscar locais próximos com base na sua localização atual, utilizando a API do Google Maps e a biblioteca Places. O projeto também conta com uma interface estilizada usando Material UI (Google Fonts e ícones).

## 🚀 Funcionalidades

- Detecta a localização atual do usuário via geolocalização do navegador.
- Permite pesquisar locais próximos com base em palavras-chave (ex: "farmácia", "restaurante").
- Exibe os resultados diretamente no mapa com marcadores personalizados.
- Mostra informações básicas ao clicar em um marcador (nome, endereço, avaliação).

## 🛠️ Tecnologias Utilizadas

- HTML5, CSS3 e JavaScript
- [Google Maps JavaScript API](https://developers.google.com/maps/documentation/javascript/overview)
- Google Places Library
- [Material UI (via CDN)](https://mui.com/)
- [Google Fonts - Roboto](https://fonts.google.com/specimen/Roboto)

## 📷 Prévia da Interface

> Uma interface limpa e amigável:
- Campo de busca para digitar o local desejado
- Botão de busca estilizado
- Mapa centralizado com a localização do usuário e marcadores dos locais encontrados

## 📦 Como Usar

1. **Clone ou baixe o repositório.**
2. **Abra o arquivo `index.html` em seu navegador.**
3. **Substitua `YOUR_API` pela sua chave da API do Google Maps:**

```html
<script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API&libraries=places&callback=initMap" async defer></script>
```

4. **Permita o acesso à localização quando solicitado pelo navegador.**
5. **Digite o que deseja procurar e clique em "Buscar".**

## 📌 Observações

- O projeto requer uma chave válida da API do Google Maps com suporte à biblioteca `places`.
- A funcionalidade de geolocalização pode não funcionar corretamente em navegadores com permissões restritas ou em conexões não seguras (use `https`).
