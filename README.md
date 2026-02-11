# Gestão de Recursos Humanos

Projeto desenvolvido em **Java Swing** para a gestão simplificada de colaboradores.

## 📸 Demonstração

### Janela Principal e Listagem
![Listagem de Pessoas](pictures/listar.png)
*Interface principal onde são listados os nomes e moradas inseridos.*

### Formulário de Inserção
![Formulário de Dados](pictures/inserir.png)
*Janela de diálogo para introdução de novos dados no sistema.*

## 🚀 Funcionalidades

**Menu GestaoRH**: Permite abrir o formulário para adicionar novas pessoas[cite: 37, 38].
**Interface Dinâmica**: Utiliza uma `JTextArea` (`txtDados`) para mostrar a informação[cite: 43].
**Encapsulamento**: Os dados são tratados através da classe `Pessoa` no pacote `dataModel`[cite: 66].
**Diálogos de Confirmação**: Sistema para validar a saída do programa com segurança[cite: 36].

## 📂 Estrutura Técnica

* [cite_start]**`uI.desktop`**: Contém a lógica visual (`FrmStarted` e `JDialogEditarPessoa`)[cite: 34, 65].
* [cite_start]**`dataModel`**: Contém a estrutura de dados (`Pessoa.java`)[cite: 66].
* [cite_start]**Sem dependências**: Utiliza apenas bibliotecas nativas do Java (Swing/AWT)[cite: 34, 65].

---
*Trabalho prático realizado no âmbito da formação de Programador Informático.*
