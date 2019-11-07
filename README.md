# Projeto-IF669-IP

> RPG Companion

### Integrantes
- João Mazzarolo
- José Danilo
- Julio Vinícius
- Thiago Henrique

## Desenvolvimento

-------------

### Classes bases:
- [x] [Personagem](./src/ClassesBasicas/Personagem.java)
- [x] [Herói](./src/ClassesBasicas/Heroi.java)
- [x] [Monstro](./src/ClassesBasicas/Monstro.java)
- [x] [Equipamento](./src/ClassesBasicas/Equipamento.java)
- [x] [Magia](./src/ClassesBasicas/Magia.java)
- [ ] Cidade

### Repositórios:
 - [x] de Personagens
    - [x] [Interface](./src/Repositorios/RepositorioPersonagem.java)
        - [x] [Array](./src/Repositorios/RepositorioPersonagemArray.java)
        - [x] [Lista](./src/Repositorios/RepositorioPersonagemLista.java)
 - [ ] de Equipamentos
    - [x] [Interface](./src/Repositorios/RepositorioEquipamento.java)
        - [x] [Array](./src/Repositorios/RepositorioEquipamentoArray.java)
        - [x] [Lista](./src/Repositorios/RepositorioEquipamentoLista.java)
 - [ ] de Magias
    - [x] [Interface](./src/Repositorios/RepositorioMagia.java)
        - [ ] [Array](./src/Repositorios/RepositorioMagiaArray.java)
        - [x] [Lista](./src/Repositorios/RepositorioMagiaLista.java)
 - [ ] de Cidades
    - [ ] Interface
        - [ ] Array
        - [ ] Lista

### Excecoes:
- [x] Personagem
    - [x] [Nao existe](./src/Excecoes/PersonagemJaExisteException.java)
    - [x] [Ja existe](./src/Excecoes/PersonagemNaoExisteException.java)
- [ ] Equipamento
    - [ ] Ja cadastrado(./src/Excecoes/EquipamentoJaCadastradoException.java)
    - [ ] Nao encontrado(./src/Excecoes/EquipamentoNaoEncontradoException.java)
- [ ] Magia
    - [ ] Ja existe
    - [ ] Nao encontrada
- [ ] Cidade

### Classe abstrata:
- [x] [Personagem](./src/ClassesBasicas/Personagem.java)
 - Heróis
 - Monstros

### Fachada de Negócio
- [x] [Personagem](./src/FachadasNegocio/FachadaPersonagem.java)
- [ ] [Equipamento](./src/FachadasNegocio/FachadaEquipamento.java)
- [ ] Cidade
- [ ] Magia

### Fachada Geral
- [ ] [Feita](./src/FachadaGeral/FachadaGeral.java)
