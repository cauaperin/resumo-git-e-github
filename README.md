
# DIO | Resumos - Git e GitHub

Repositório para armazenar **resumos** e pontos importantes sobre as aulas relacionadas ao **Git e GitHub** da
[Digital Innovation One](https://www.dio.me/)

## 📖 | Documentação
- [Documentação GIT](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/)

## 🖥️ | Resumo das Aulas
| Aulas | Video |
|-------|---------|
| Autenticando via Token | [link da aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/3d13d85f-2508-4396-9657-4643d3302c79?back=/track/gft-start-logica-de-programacao&tab=path&moduleId=undefined) |
| Autenticando via Chave SSH | [link da aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/a53b7d6e-d7a2-40de-a8f9-cc30b42fc93d?back=/track/gft-start-logica-de-programacao&tab=path&moduleId=undefined) |
| Criando e Clonando Repositórios | [link da aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/a377a00b-461c-4ab0-8258-3addd2fef14c?back=/track/gft-start-logica-de-programacao&tab=path&moduleId=undefined) |
| Salvando alterações no repositório Local |[link da aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/gft-start-logica-de-programacao&tab=path&moduleId=undefined) |
| Desfazendo alterações no repositório Local |[link da aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/3f9f2336-6fd5-44cb-ba39-d1a4f6448023?back=/track/gft-start-logica-de-programacao&tab=path&moduleId=undefined) |

### ℹ️ | Comandos

#### Para inicializar um novo repositório
```
git init
```
#### Para copiar um repositório
```
git copy --global <URL>
```
#### Lembrará e não pedirá novamente seu usuário e senha ao copiar um repositório
```
git config --global credential.helper store
```
#### Mostra a credencial que está configurada no seu Git
```
git config --global credential.helper
``` 
#### Acessar o coração do seu repositório GIT
```
cd .git
```
#### Usado para exibir o conteúdo do arquivo config no diretório .git
```
cat config
```
#### Mostra o estado atual do seu repositório
```
git status
```
#### Cria um commit com uma mensagem específica
```
git commit -m "Alguma coisa"
```
#### É a chave para o histórico de commits do seu repositório
```
git log
``` 
#### Adiciona um arquivo ao próximo commit
```
git add <file>
```


## 🔎 | Referências