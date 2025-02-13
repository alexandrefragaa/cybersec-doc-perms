# cybersec-doc-perms
### Repositório para documentar comandos Linux de gerenciamento de permissões, explicando seu funcionamento e aplicações práticas

## 📖 Índice  
1. [Introdução](#introdução)  
2. [Verificando Permissões (`ls -l`)](#verificando-permissões-ls--l)  
3. [Modificando Permissões (`chmod`)](#modificando-permissões-chmod)  
4. [Alterando Proprietário (`chown`)](#alterando-proprietário-chown)  
5. [Auditoria de Permissões](#auditoria-de-permissões)  



## 📌 Introdução  
No Linux, cada arquivo tem permissões que controlam **quem pode ler, escrever e executar**.  

## 🔹 Exemplo de **permissões de um arquivo**:  
```bash```

ls -l arquivo.txt

-rw-r--r-- 1 usuario grupo 1024 Fev 13 10:00 arquivo.txt

### Explicação:

    rw- → O dono pode ler e escrever.
    r-- → O grupo pode apenas ler.
    r-- → Outros usuários podem apenas ler.
