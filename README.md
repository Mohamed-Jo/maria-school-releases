# MARIA School — instaladores

Sistema de gestão escolar (alunos, matrículas, notas, presenças, propinas, recursos humanos,
cantina, biblioteca e transporte) para um ou vários computadores ligados a um servidor.

Este repositório tem apenas os **instaladores e as notas de cada versão**.
Descarregue a versão mais recente em **[Releases](../../releases/latest)**.

## Instalar ou actualizar
1. Faça uma cópia de segurança (Configuração → Cópias de segurança).
2. Instale primeiro no **servidor** (escolha *Servidor*; requer MySQL) e depois em cada **terminal**
   (escolha *Terminal* e indique o IP do servidor). A actualização instala-se por cima da anterior.
3. Ao arrancar, o servidor actualiza a base de dados automaticamente.

O sistema avisa os utilizadores quando há uma versão nova publicada aqui.
Para desligar esse aviso, ponha `UPDATE_GITHUB_REPO=desactivado` no ficheiro
`C:\ProgramData\MARIA School\.env` do servidor.

A utilização para além do período de avaliação requer licença.
