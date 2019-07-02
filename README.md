# Monografia de conclusão de curso

Este repositório contém a monografia do projeto de conclusão de curso TheoPrax dos cursos de Engenharia de Controle e Automação e Engenharia Mecânica que será apresentada no Centro Universitário SENAI CIMATEC como requisito parcial para obtenção do título de **Bacharel em Engenharia**.

Componentes da equipe:
- Caio Amaral
- Élisson Ríller
- Elton Marques
- Iure Pinheiro
- Mateus Meneses

Orientador: Prof. Msc. Marcos Reis

## Como usar:
Para a compilação e edição dos arquivos da monografia, recomenda-se o uso do ambiente de gravação integrado para criar documentos LaTeX [TeXstudio](https://www.texstudio.org/). 

Para instalação deste ambiente, recomenda-se primeiro instalar o [TeX Live](https://www.tug.org/texlive/). Para isso, execute o seguinte comando no seu terminal:

```sh
sudo apt-get install texlive-full
```

Após a instalação do `textlive-full`, instale o TeXstudio através do seguinte comando:

```sh
sudo apt-get install texstudio
```
**Observações:** Os comandos foram executados utilizando o terminal da distribuição Ubuntu 16.04. Caso queira utilizar o editor de sua preferência, ignore os passos acima.

Caso possua git instalado na sua máquina, clone o repositório numa pasta de desejo. Caso contrário, faça o download do repositório em formato `.zip` e descompacte-o.

```sh
git clone https://github.com/cimatecmateus/monografia_theoprax_doogie.git
```

No TeXstudio ou no seu editor de escolha, abra o arquivo `tprax_doc_tex.tex` e então compile-o para obter uma versão pdf da monografia. Navegue entre os capítulos e seções para editá-los e então recompile novamente o documento para visualizar o resultado da edição.

## Contribuição
### Algumas dicas:
- Sempre que forem editar o documento, atualizar seu repositório local para evitar problemas futuros de conflitos

- A branch `master` deve ficar sempre com o conteúdo mais atualizado e revisado da monografia. Para atualizá-la, solicite um **pull request** e adicione um revisor. Quando o pull request for revisado e aprovado, imediatamente exclua a branch em que se estava trabalhando. Essa boa prática evita futuros problemas de conflitos

- As mensagens de commit devem ser realizadas em português. Como recomendação, utilize as seguintes [boas práticas](https://chris.beams.io/posts/git-commit/). Isto deixa o histórico de commits mais claro e limpo

- Use as *labels* em conformidade com as boas práticas. O seguinte [artigo](https://en.wikibooks.org/wiki/LaTeX/Labels_and_Cross-referencing) dá dicas de como utilizar *labels*. Como recomendação, separar as palavras com underscore e com todas as letras minúsculas. Em caso de dúvida, verificar alguma *label* já existente

- Em caso de dúvidas, verificar nos fóruns da comunidade LaTeX. De prefrência, utilize o inglês para fazer as perguntas. Os fóruns na língua inglesa possuem mais contribuições!
