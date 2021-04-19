# Como funciona
Este pacote serve para gerar arquivos baseados no framework **Kurin**

# Como usar
Veja abaixo algums exemplos de utilização da ferramenta

### Exemplo 1

```bash
php vendor/albreis/bin/scaffold
```

Após executar o comando acima alguns perguntas serão feitas
```
Namespace: App
```
Namespace onde serão alocadas as classes do app

```
Class name:
```
Nome da classe

```
Resources separated by commas or spaces: (empty equals all)
```
Recursos a serem criados separados por vírgula ou espaços:
- controller
- storagemanager
- model
- producer
- repository
- validator

```
Controller name:
```
Nome do controller

```
StorageManager name:
```
Nome do Storage Manager

```
Model name:
```
Nome do Model

```
Producer name:
```
Nome do Producer

```
Repository name:
```
Nome do Repository

```
Validator name:
```
Nome do Validator

### **Finalizado!**
Após isso os arquivos serão gerados a partir da raiz da instalação seguindo a hierarquia de diretórios definidos pelo namespace.