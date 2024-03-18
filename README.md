# GoogleHack

## Aqui está uma lista expandida com mais de 100 "Google dorks" e informações sobre suas implicações:

1. **Inurl:admin** - Potencial acesso não autorizado a sistemas administrativos.
2. **Intitle:index.of private** - Exposição de diretórios privados e seus conteúdos sensíveis.
3. **Filetype:log inurl:password** - Possibilidade de encontrar arquivos de log contendo senhas não criptografadas.
4. **Intext:”sql syntax error” site:example.com** - Indica falhas potenciais de segurança no banco de dados de um site específico.
5. **Intitle:"index of" intext:sftp-config.json** - Exposição de configurações SFTP, incluindo credenciais de acesso.
6. **Filetype:config intext:password -github** - Localização de arquivos de configuração com senhas, excluindo resultados do GitHub.
7. **Intitle:"Index of" .ssh** - Revelação de pastas .ssh que podem conter chaves de acesso SSH.
8. **Filetype:env intext:APP_KEY** - Descoberta de arquivos de ambiente com chaves de aplicativos sensíveis.
9. **Intitle:"Index of" .vscode** - Exposição de pastas do Visual Studio Code, onde podem estar armazenadas informações sensíveis.
10. **Filetype:properties inurl:prod** - Acesso a arquivos de propriedades de produção que podem conter configurações críticas.
11. **Intitle:"Index of" .htpasswd** - Localização de pastas que podem conter arquivos .htpasswd com senhas de acesso.
12. **Filetype:json intext:apikey** - Descoberta de arquivos JSON contendo chaves de API.
13. **Intitle:"Index of" wp-content/uploads/private** - Exposição de pastas privadas de uploads do WordPress, onde podem estar arquivos sensíveis.
14. **Filetype:xml inurl:/conf/global-settings** - Revelação de arquivos XML de configuração global, potencialmente incluindo informações sensíveis.
15. **Intitle:"Index of" .docker** - Acesso a pastas Docker que podem conter arquivos de configuração ou segredos.
16. **Filetype:yml intext:AWS_ACCESS_KEY_ID** - Descoberta de arquivos YAML que podem incluir chaves de acesso da AWS.
17. **Intitle:"Index of" .git/config** - Exposição de pastas do Git contendo arquivos de configuração, que podem incluir URLs de repositórios remotos e credenciais.
18. **Filetype:sql "insert into" (pass|passwd|password)** - Localização de consultas SQL que inserem senhas em um banco de dados, potencialmente expondo senhas em texto simples.
19. **Intitle:"Index of" database** - Mostra pastas que podem conter bancos de dados ou backups, expondo informações confidenciais.
20. **Filetype:env intext:DB_PASSWORD** - Descoberta de arquivos de ambiente que contêm senhas de banco de dados.

21. **Intitle:"Index of" .env** - Exposição de arquivos de ambiente que podem conter configurações sensíveis.
22. **Filetype:conf "Authentication"** - Localização de arquivos de configuração com informações de autenticação.
23. **Intitle:"Index of" inurl:/config** - Acesso a diretórios de configuração que podem conter arquivos sensíveis.
24. **Filetype:php intitle:"Index of" config** - Descoberta de arquivos de configuração PHP que podem conter credenciais.
25. **Intitle:"Index of" .bash_history** - Exposição de histórico de comandos Bash que podem conter informações sensíveis.
26. **Filetype:ini inurl:config** - Localização de arquivos INI de configuração que podem incluir segredos.
27. **Intitle:"Index of" .bak** - Acesso a arquivos de backup que podem conter versões anteriores de dados sensíveis.
28. **Filetype:pwd service** - Descoberta de serviços que possam expor senhas em texto simples.
29. **Intitle:"Index of" .ftpquota** - Exposição de pastas que podem conter arquivos .ftpquota com informações de quotas de FTP.
30. **Filetype:txt inurl:robots.txt** - Localização de arquivos robots.txt que podem conter diretrizes sensíveis.
31. **Intitle:"Index of" .ssh/id_rsa** - Revelação de chaves privadas SSH que podem permitir acesso não autorizado.
32. **Filetype:log inurl:access.log** - Descoberta de arquivos de log de acesso que podem conter informações sensíveis.
33. **Intitle:"Index of" inurl:/proc/self/cwd** - Acesso a diretórios do sistema que podem conter informações sensíveis.
34. **Filetype:txt intext:@gmail.com intext:password** - Localização de arquivos de texto contendo senhas associadas a contas de e-mail do Gmail.
35. **Intitle:"Index of" .git/HEAD** - Revelação de informações sobre o repositório Git, potencialmente incluindo URLs de repositórios remotos.
36. **Filetype:env "DB_PASSWORD"** - Exposição de arquivos de ambiente que contêm senhas de banco de dados.
37. **Intitle:"Index of" .svn** - Acesso a pastas SVN que podem conter informações sensíveis ou histórico de versões.
38. **Filetype:sh intext:pass** - Localização de scripts de shell que podem conter senhas em texto simples.
39. **Intitle:"Index of" .mysql_history** - Exposição de histórico de comandos MySQL que podem conter informações sensíveis.
40. **Filetype:reg "Internet Settings"** - Descoberta de arquivos de registro do Windows contendo configurações de internet sensíveis.

41. **Intitle:"Index of" .gitignore** - Revelação de arquivos .gitignore que podem indicar arquivos ou diretórios sensíveis que são ignorados pelo Git.
42. **Filetype:sql password** - Localização de arquivos SQL que podem conter senhas.
43. **Intitle:"Index of" .history** - Acesso a arquivos de histórico que podem conter informações sensíveis.
44. **Filetype:env intext:SECRET_KEY** - Descoberta de arquivos de ambiente contendo chaves de segredo.
45. **Intitle:"Index of" config.php** - Exposição de arquivos de configuração PHP que podem conter credenciais de banco de dados.
46. **Filetype

:cfg "EnablePassword"** - Localização de arquivos de configuração que podem conter senhas de dispositivos de rede.
47. **Intitle:"Index of" .bashrc** - Revelação de arquivos de configuração Bash que podem conter informações sensíveis.
48. **Filetype:xml intext:password** - Descoberta de arquivos XML contendo senhas.
49. **Intitle:"Index of" .aws/credentials** - Acesso a pastas AWS que podem conter credenciais de acesso.
50. **Filetype:cnf password** - Localização de arquivos de configuração contendo senhas.
51. **Intitle:"Index of" .DS_Store** - Exposição de pastas que podem conter informações sobre a estrutura do diretório em sistemas macOS.
52. **Filetype:env intext:MYSQL_ROOT_PASSWORD** - Descoberta de arquivos de ambiente contendo senhas do MySQL root.
53. **Intitle:"Index of" /private** - Revelação de pastas privadas que podem conter arquivos sensíveis.
54. **Filetype:log "PHP Parse error"** - Localização de arquivos de log contendo erros de análise PHP que podem revelar informações sensíveis.
55. **Intitle:"Index of" .svn/entries** - Acesso a arquivos SVN que podem conter informações sobre o repositório.
56. **Filetype:config "password"** - Descoberta de arquivos de configuração contendo senhas.
57. **Intitle:"Index of" .git/COMMIT_EDITMSG** - Exposição de mensagens de commit do Git que podem conter informações sensíveis.
58. **Filetype:env DB_USERNAME** - Localização de arquivos de ambiente contendo nomes de usuário de banco de dados.
59. **Intitle:"Index of" .npmrc** - Revelação de arquivos de configuração do npm que podem conter tokens de acesso.
60. **Filetype:sql intext:password** - Descoberta de arquivos SQL contendo senhas em texto simples.

Espero que esta lista expandida seja útil para seus propósitos. Lembre-se sempre de usar essas técnicas de forma ética e responsável, respeitando a privacidade e a segurança das informações online.
