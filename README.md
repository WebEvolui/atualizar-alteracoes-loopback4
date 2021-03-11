# Servidor pegar alterações feitas nos .ts
Pacote e comando para pegar automaticamente alterações no projeto loopback 4

### Instalando pacote
```npm install tsc-watch --save-dev```

### Acrescentar script (no package.json)
```"dev": "tsc-watch --target es2017 --outDir ./dist --onSuccess \"node .\""```

Depois só rodar comando no terminal (na pasta do projeto)

```npm run dev```

Pronto servidor pegará as alterações automatimente feitas e ficará mais rápido o desenvovimento 😊
