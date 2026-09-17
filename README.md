# 🏋️‍♂️ Cronograma Semanal de Treinos (Hipertrofia)

Um aplicativo web responsivo e minimalista projetado para funcionar como um diário ou guia de treinos digital diretamente no seu smartphone ou computador. O foco do cronograma é otimizado para praticantes de musculação de nível intermediário/avançado que buscam hipertrofia e densidade muscular.

---

## 📱 Recursos do Aplicativo

* **Design Mobile-First:** Totalmente responsivo e otimizado para telas de smartphones. Perfeito para usar e consultar enquanto está na academia.
* **Demonstrações Visuais:** Links estáveis integrados com GIFs reais que demonstram a execução biomecânica correta de cada movimento.
* **Interface Dark Mode:** Tema escuro nativo com detalhes em neon verde para garantir boa leitura sob as luzes da academia ou em ambientes externos.
* **Código Limpo:** Separação estrita entre a estrutura de dados (HTML) e a estilização visual (CSS) em arquivos independentes.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi construído de forma pura e nativa, garantindo carregamento instantâneo no celular:

* **HTML5:** Para a estruturação semântica dos cards de treino, listagem de exercícios e metatags de responsividade.
* **CSS3:** Para a estilização visual, uso de variáveis globais (`:root`), flexbox e `@media queries` para garantir adaptabilidade em qualquer tamanho de tela.

---

## 📂 Estrutura do Projeto

A organização dos arquivos segue o padrão recomendado de desenvolvimento web:

```text
├── index.html   # Estrutura semântica e conteúdo do treino
├── style.css    # Estilização, cores e regras de responsividade
└── README.md    # Documentação oficial do projeto
```

---

## 🚀 Como Executar o Projeto

Como a aplicação utiliza tecnologias web fundamentais nativas, não há necessidade de instalar dependências complexas ou servidores:

1. Certifique-se de que os arquivos `index.html` e `style.css` estejam localizados na **mesma pasta** no seu computador.
2. Abra o arquivo `index.html` em qualquer navegador moderno (Google Chrome, Firefox, Safari, Edge) clicando duas vezes sobre ele.
3. *Dica de Desenvolvimento:* Caso utilize o **Visual Studio Code**, use a extensão **Live Server** para rodar o projeto localmente com recarregamento automático em tempo real durante suas modificações.

---

## 📝 Customização de Exercícios

Para alterar a quantidade de séries, repetições ou o nome de movimentos do cronograma, basta atualizar o conteúdo das tags de lista no arquivo `index.html`:

```html
<div class="exercise-item">
    <div class="info">
        <h3>Nome do Seu Exercício</h3>
        <p>4 séries × 10 repetições</p>
    </div>
    <img src="link-do-seu-gif-aqui.gif" alt="Nome do Exercício">
</div>
```
