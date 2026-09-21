
# Configuração do README do perfil

1. Crie um repositório **público** no GitHub chamado exatamente `viniciusbevilaqua` na conta `viniciusbevilaqua`.
2. Envie o conteúdo desta pasta para o repositório. O `README.md` deve permanecer na raiz.
3. Mantenha `.github/workflows/snake.yml` no mesmo local mostrado aqui.
4. No repositório, abra **Settings → Actions → General** e permita **Read and write permissions** para os workflows. Salve a alteração.
5. Abra a aba **Actions**, escolha **Gerar Snake de Contribuições** e clique em **Run workflow** uma vez.
6. Quando o workflow terminar, ele criará a branch `output` e publicará a imagem da Snake. O README passará a exibi-la automaticamente.

O workflow será executado novamente todos os dias. Ele usa o `GITHUB_TOKEN` fornecido pelo repositório; não é necessário token pessoal nem segredo adicional.