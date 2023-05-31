# Anotações gerais sobre a aula de Git e GitHub 
## Prática individual
### Ferramenta em que vários devs podem mexer no código ao mesmo tempo.
Cotidiano de quem cria software.
Mexer e gerenciar no código fonte.


Git: Sistema de versionamento -> para controlar versões. 
Mantém o histórico;
Permite voltar versão;
Permite avançar.

GitHub: serviço online de hospedagem dos projetos em Git

SSH: protocolo para comunicação de dados com segurança;
Cadastrar quais computadores podem acessar o meu GitHub.

Comandos:
git init  (inicialização do projeto) 

git add .   (adiciona os arquivos que vão fazer parte do histórico, adiciona as modificações)

git commit -m "mensagem explicativa"   (junta todas as modificações. Posso adicionar vários arquivos para criar um commit)

git branch -M main     (master)

git remote add origin git@github.com:caterinawiers/seurepositório.git

git push -u origin main     (master) -> envia o commit para o GitHub as modificações

git status m  (mostra o que está acontecendo)

git add -p  (adiciona aos poucos as partes dos arquivos que eu quero)

cd   (navega entre as pastas)

clear  (limpar)


-a  (mostra arquivos ocultos)

Clone: 
Cópia local de um repositório remoto

Fork: 
Cópia de um repositório remoto sem afetar o repositório principal

Pull: 
Puxa a atualização do código 

Git Bash é um terminal para otimizar o uso do Git
