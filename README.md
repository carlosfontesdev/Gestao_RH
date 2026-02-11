# Gestão de Recursos Humanos

Projeto desenvolvido em **Java Swing** para a gestão simplificada de colaboradores.

## 📸 Demonstração

### Janela Principal e Listagem
*Interface principal onde são listados os nomes e moradas inseridos.*
![Listagem de Pessoas](pictures/listar.png)


### Formulário de Inserção
*Janela de diálogo para introdução de novos dados no sistema.*
![Formulário de Dados](pictures/inserir.png)


## 🚀 Funcionalidades

**Menu GestaoRH**: Permite abrir o formulário para adicionar novas pessoas.
**Interface Dinâmica**: Utiliza uma `JTextArea` (`txtDados`) para mostrar a informação.
**Encapsulamento**: Os dados são tratados através da classe `Pessoa` no pacote `dataModel`.
**Diálogos de Confirmação**: Sistema para validar a saída do programa com segurança.

## 📂 Estrutura Técnica

**`uI.desktop`**: Contém a lógica visual (`FrmStarted` e `JDialogEditarPessoa`).
**`dataModel`**: Contém a estrutura de dados (`Pessoa.java`).
**Sem dependências**: Utiliza apenas bibliotecas nativas do Java (Swing/AWT).

---
*Trabalho prático realizado no âmbito da formação de Programador Informático.*
