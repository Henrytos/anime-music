

Claro! Aqui está o texto formatado como um `README.md` para GitHub, com organização, títulos em markdown, ícones e blocos de código para facilitar a leitura:

---

# 🎵 Desafio: Gerenciador de Playlist Musical

Você foi contratado para desenvolver um sistema de gerenciamento de uma **playlist de músicas**, que será utilizado por um aplicativo de streaming.

O sistema deve permitir a **adição**, **atualização** e **consulta** de músicas, com foco em **avaliações** e nos **integrantes da banda**.

---

## 🎼 Estrutura de uma Música

Cada música deve conter os seguintes atributos:

- `titulo`: o nome da música  
- `banda`: o nome da banda  
- `duracao`: duração da música (em minutos)  
- `anoLancamento`: o ano de lançamento da música  
- `avaliacoes`: lista de avaliações da música (valores de 1 a 5)  
- `integrantes`: nomes dos integrantes da banda  

---

## 📋 Funcionalidades Obrigatórias

- `adicionarMusica`: Adicionar uma nova música à playlist  
- `listarMusicas`: Listar todas as músicas  
- `removerMusica`: Remover uma música pelo título  
- `atualizarAnoLancamento`: Atualizar o ano de lançamento de uma música pelo título  
- `mediaAvaliacoes`: Calcular a média das avaliações de uma música  
- `buscarBandaPorIntegrante`: Descobrir em qual banda está determinado integrante  

---

## ⭐ Dicas Úteis

### Como adicionar integrantes:

Você pode pedir que o usuário digite os nomes separados por vírgulas, por exemplo:

```js
const nomesDigitados = "Bob, Tom, Mel, Dan";
const integrantes = nomesDigitados.split(",");
```

### Como remover os espaços em branco:

```js
for (let i = 0; i < integrantes.length; i++) {
    integrantes[i] = integrantes[i].trim();
}
```

### Use a mesma lógica para cadastrar as avaliações:

```js
const avaliacoesDigitadas = "5, 4, 3, 4";
const avaliacoes = avaliacoesDigitadas.split(",").map(Number);
```

---

## ✅ Observações

- O foco é na lógica de manipulação de dados em arrays e objetos.
- Mantenha o código organizado e utilize boas práticas de programação.

---

Se quiser, posso complementar com instruções de instalação, execução ou estrutura de pastas. Deseja isso também?