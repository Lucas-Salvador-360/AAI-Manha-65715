# AAI-Manha-65715
Lucas Salvador Pereira Nascimento - 65715 - ADS Manhã

//1. Como criar um projeto React Native do zero e subir no GitHub
// Comandos React Native:
// se for para criar um projeto do 0 deve criar a pasta dando um mkdir "nome da pasta". Exemplo:
mkdir dog-ever-match-prof-aula-manha
cd dog-ever-match-prof-aula-manha //entar na pasta criada
code . //abrir a pasta no vs code
// Após isso você deve baixar a biblioteca do React Native executando o comando:
npx create-expo-app@latest //irá criar as pastas de um novo projeto
npm install react-native //irá baixar todas as depedencias
npm install react@version_printed_above // Em caso apareça a mensagem " react-native@0.70.5" tem dependência de par não atendida " react@18.1.0"
//Após fazer os codigos e as alterações, segue os comandos para subir.
git init // cria um repositorio vazio ou reinicia um existente
git add . // adiciona todas as alterações
git commit -m "mensagem de commit" //registre o estado original como o primeiro comando original
git branch -M main //ele tranforma a branch main
git remote add origin https://github.com/GuilhermeCamargo744/dog-ever-match-prof-aula-manha.git    // você define o cominho onde será colocado as alterações.
git push origin main //você joga tudo no repositorio


//2. Como clonar o projeto da nossa aula e rodá-lo
git clone https://github.com/GuilhermeCamargo744/dog-ever-match-prof-aula-manha.git    // você copia tudo no repositorio na sua maquina
cd dog-ever-match-prof-aula-manha //entar na pasta que foi clonado
git pull //puxa todas as alterações
git checkout "nome da branch"  //entra na branch crianda ou exitente
npm i //baixa todas as depedencias
code . //abrir a pasta no vs code
npm run start  //roda o codigo
//E você já começa as alterações.
