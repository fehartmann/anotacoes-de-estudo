**Criação de Repositório no Github**

Seus repositórios- Novo
 - Colocar nome do repositório e descrição
 - Perfil público
 - Adicionar arquivo README (arquivo para anotações especiais, links etc)

 > O arquivo README terá a extensão .md (Markdown)

 > O arquivo é editável pelo próprio Github, mas também dá para utilizar o Visual Studio Code

 > Lembrar que o Github é um repositório na nuvem e o Git é local

 O Git é um software de controle de versão, já o GitHub é como se fosse uma rede social de pessoas desenvolvedoras, ou seja, uma plataforma na qual podem compartilhar projetos.

**Como clonar o repositório do Github para o Git**

- Acessa <>Código - SSH - Copia o link
- Na pasta do arquivo no Windows, clica com o botão direito do mouse e seleciona Git Bash Here
- No Git Bash digita: git clone e cola (shift+ins) o link do diretório, depois aperta enter

**Envio de aruivos e atualizações do Git para o Github**

- Na página do Git Bash digita: git status (apenas para atualizações ou para saber o status dos arquivos)
- Depois digita: git add . (adiciona os arquivos)
- Depois: git commit -m "texto de apoio" (comitando os arquivos)
- No fim: git push origin main (para empurrar/enviar os arquivos para o Github)