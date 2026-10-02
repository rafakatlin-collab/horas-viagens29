HORAS VIAGENS29 - VERSÃO 5 ONLINE

Esta versão já está configurada para o projeto Firebase horas-viagens29.

O que funciona:
- login visível por celular + senha;
- dados online no Firestore;
- vários motoristas em celulares diferentes;
- foto do motorista comprimida e salva no perfil;
- iniciar trabalho e salvar só o horário inicial;
- finalizar depois e calcular as horas automaticamente;
- cálculo correto quando o trabalho termina após meia-noite;
- histórico individual;
- relatório por período e impressão/PDF;
- cadastro de veículos;
- painel de administrador;
- promover outro motorista a administrador e rebaixar administrador para motorista.

PASSOS NO FIREBASE ANTES DE USAR:
1. Firestore > Regras: cole o conteúdo do arquivo firestore.rules e clique em Publicar.
2. Abra o app e use "Criar primeiro acesso". Esse primeiro perfil será criado como Motorista por segurança.
3. No Firebase > Firestore > Dados > coleção users, abra o documento do seu usuário e altere o campo role de driver para admin. Isso é necessário somente para o primeiro administrador.
4. Saia e entre novamente no app. A partir daí o administrador consegue cadastrar os outros motoristas normalmente.

OBSERVAÇÃO:
Excluir um perfil pelo app remove o perfil e seus registros do Firestore, mas não apaga automaticamente o usuário em Authentication. A exclusão completa do login deve ser feita no Firebase Authentication.

Para instalar como aplicativo no Android, hospede esta pasta em HTTPS e use a opção "Adicionar à tela inicial" do Chrome. Em uma etapa posterior ela pode ser empacotada como APK.
