# Bug Reports — Sauce Demo

## BUG-001 — Imagem incorreta na listagem de produtos

**Aplicação:** Sauce Demo  
**Tipo:** Defeito visual / funcional  
**Usuário utilizado:** `problem_user`  
**Ambiente:** Navegador Chrome  
**Status:** Observado; documentação inicial

### Descrição

Ao acessar a listagem de produtos com o usuário `problem_user`, foi observada a imagem de um cachorro no lugar das imagens correspondentes a vários produtos.

Ao abrir a página de detalhes da jaqueta (`Sauce Labs Fleece Jacket`), a imagem apresentada corresponde à jaqueta.

### Pré-condições

- A aplicação Sauce Demo está acessível.
- O usuário `problem_user` consegue acessar a página de produtos.

### Passos para reproduzir

1. Abrir https://www.saucedemo.com/.
2. Entrar com o usuário `problem_user`.
3. Utilizar a senha `secret_sauce`.
4. Observar as imagens na listagem de produtos.
5. Abrir o produto `Sauce Labs Fleece Jacket`.
6. Comparar a imagem da listagem com a imagem dos detalhes.

### Resultado esperado

Cada produto deve apresentar a imagem correspondente ao item anunciado.

### Resultado observado

Na listagem, a imagem de um cachorro aparece em vários cartões de produtos. Na página de detalhes da jaqueta, aparece a imagem da própria jaqueta.

### Impacto potencial

As imagens incorretas podem confundir os usuários e prejudicar a apresentação dos produtos.

### Severidade e prioridade

Ainda não classificadas definitivamente. Devem ser avaliadas de acordo com o impacto e os critérios do projeto.
### Evidências

- Captura de tela da listagem mostrando imagens incorretas.
- Captura de tela dos detalhes da jaqueta mostrando a imagem correspondente.

### Limitações da verificação

A comparação adicional com a página de detalhes da mochila não foi concluída. Não há evidência suficiente para afirmar qual imagem aparece nessa página.

### Conclusão

Foi observada uma inconsistência entre as imagens da listagem e a imagem dos detalhes da jaqueta. O defeito foi documentado com base nas evidências disponíveis, sem generalizar para páginas que não foram verificadas.
