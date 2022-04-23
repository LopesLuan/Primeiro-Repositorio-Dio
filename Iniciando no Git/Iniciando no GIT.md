# COMANDOS BASICOS PARA NAVEGAÇÃO ENTRE DIRETORIOS

dir(Directory)- Lista todos os diretorios daquele local.
cd (Change Directory)- Muda de diretorios(pastas)
cls (Clear Screen) - Limpa a tela
mkdir(Make Directory) - Criar diretorios(Pastas)
echo - Retorna na tela uma string digitada
del(Delete) - deleta arquivos de um determinado diretorio(Pasta)
rmdir(Remove Directory) /s /q - remove diretorios

# Criando o token do GITHUB no GIT Comandos:
## Primeira Etapa:

ssh-keygen -t ed25519 -C <email do github>
(Após do comando verificar o local onde ficou salvo) após digitar:
cat id_ed25519.pub

## Segunda Etapa:

eval $(ssh-agent-s)
ssh-add id_ed25519





