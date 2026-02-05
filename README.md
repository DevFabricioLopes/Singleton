# Singleton

Implementação do padrão de projeto Singleton em Java.

## 📌 Descrição
O padrão Singleton garante que uma classe possua apenas uma única instância durante toda a execução da aplicação, fornecendo um ponto global de acesso a essa instância.

Este padrão é amplamente utilizado em cenários como gerenciamento de configurações, controle de conexões, logs e acesso a recursos compartilhados.

## 🧠 Estrutura
- Classe Singleton com construtor privado
- Atributo estático para armazenar a instância
- Método público estático para acesso à instância única

## ▶️ Como funciona
A instância é criada apenas quando solicitada pela primeira vez (lazy initialization), garantindo controle total sobre a criação do objeto.

## 🧪 Como usar
Clone o repositório e execute a classe de exemplo para observar que múltiplas chamadas retornam a mesma instância.

## 📚 Referências
- Padrões de Projeto – GoF
