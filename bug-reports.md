
# Bug Reports — Sauce Demo

## BUG-001 — Imagens incorretas nos produtos

**Aplicação:** Sauce Demo  
**Tipo:** Defeito visual / funcional  
**Usuário utilizado:** `problem_user`  
**Ambiente:** Navegador Chrome  
**Status:** Observado; documentação inicial

### Descrição

Ao acessar a listagem de produtos com o usuário `problem_user`, foi observada a imagem de um cachorro no lugar das imagens correspondentes a vários produtos.

Na página de detalhes da jaqueta (`Sauce Labs Fleece Jacket`), a imagem apresentada correspondia à jaqueta.

Na verificação adicional da mochila (`Sauce Labs Backpack`), foi observada uma imagem incorreta tanto na listagem quanto na página de detalhes.

### Pré-condições

- A aplicação Sauce Demo está acessível.
- O usuário `problem_user` consegue acessar a página de produtos.

### Passos para reproduzir

1. Abrir https://www.saucedemo.com/.
2. Entrar com o usuário `problem_user`.
3. Utilizar a senha `secret_sauce`.
4. Observar as imagens na listagem de produtos.
5. Abrir o produto `Sauce Labs Fleece Jacket` e observar sua imagem.
6. Abrir o produto `Sauce Labs Backpack` e observar sua imagem.
7. Comparar as imagens observadas com os produtos correspondentes.

### Resultado esperado

Cada produto deve apresentar a imagem correspondente ao item anunciado, tanto na listagem quanto na página de detalhes.

### Resultado observado

- **Listagem:** foi observada a imagem de um cachorro em vários cartões de produtos.
- **Detalhes da jaqueta:** a imagem apresentada correspondia à jaqueta.
- **Listagem da mochila:** foi observada uma imagem incorreta.
- **Detalhes da mochila:** foi observada uma imagem incorreta.

### Impacto potencial

Imagens incorretas podem confundir os usuários, dificultar a identificação dos produtos e prejudicar a apresentação visual da loja.


### Severidade e prioridade

**Severidade:** Média  
**Prioridade:** Média

**Justificativa:** As imagens incorretas prejudicam a identificação visual dos produtos e podem confundir os usuários. Até o momento, não foi verificado se o defeito impede a conclusão de uma compra. A classificação poderá ser revisada conforme novas evidências e os critérios do projeto.



### Evidências

- Captura da listagem mostrando imagens incorretas: [BUG-001-listagem.png](evidencias/BUG-001-listagem.png).
- A captura comprova que vários produtos apresentam a imagem de um cachorro na listagem.
- As imagens das páginas de detalhes devem ser registradas separadamente quando disponíveis.


### Limitações da verificação

Os resultados documentados correspondem aos produtos efetivamente verificados: a jaqueta e a mochila.

Não foram registrados detalhes visuais suficientes para descrever exatamente qual imagem incorreta apareceu na página de detalhes da mochila. Outros produtos não verificados não devem ser considerados defeituosos sem evidências adicionais.

### Conclusão

Foram observadas inconsistências nas imagens dos produtos ao utilizar o usuário `problem_user`.

Na jaqueta `Sauce Labs Fleece Jacket`, a imagem dos detalhes correspondia ao produto, apesar da imagem incorreta observada na listagem.

Na mochila `Sauce Labs Backpack`, foram observadas imagens incorretas tanto na listagem quanto na página de detalhes.

O defeito foi documentado com base nos resultados observados. A severidade e a prioridade permanecem pendentes de classificação.
