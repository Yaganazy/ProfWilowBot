# ProfWilowBot

Bot para ajudar um grupo de Pokémon GO no Telegram

### Funções
- [x] Calculadora de IV
- [ ] Criar lista de raids
- [ ] Criar lista com codigo de treinador dos membros do grupo

## Como usar

Baixe os arquivos, extraia, entre na pasta criada.  
Crie um ambiente virtual: `python3 -m venv .env`  
Ative o ambiente virtual:  
- usando o **CMD**: `.env/bin/activate.bat`  
- usando o **PowerShell**: `.env/bin/activate.ps1`  

Baixe os requeriments para o bot funcionar: `pip install -r requeriments`

#### Pastas e arquivos

se você não tiver um arquivo chamado **config.toml** crie ele dentro da pasta **config** e se ela não existir crie-a.

```
ProfWilowBot
├── bot.py
├── Comandos.py
├── config
│   └── config.toml
├── README.md
└── requeriments
```

Para criar a pasta **config** digite: `mkdir config` e dentro da pasta config crie um arquivo chamado **config.toml** e dentro dele coloque:  
`TOKEN='your TOKEN here'`

Dentro do arquivo **config.toml** coloque seu **TOKEN** onde esta escrito `your TOKEN here` não esqueça das aspas, caso nao tenha um **TOKEN** fale com o [BotFather](https://t.me/BotFather) para criar um.
