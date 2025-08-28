# 💳 Sistema de Compras com Cartão de Crédito

Este projeto foi desenvolvido em **Java** utilizando o **IntelliJ IDEA** como ambiente de desenvolvimento.  
O objetivo é simular o uso de um cartão de crédito, controlando limite, saldo e compras realizadas.

---

## 📌 Funcionalidades
- Definir o **limite do cartão** no início do programa.
- Registrar **compras** com descrição e valor.
- Verificar automaticamente se há **saldo suficiente** antes de aprovar uma compra.
- Listar todas as compras realizadas em **ordem crescente de valor**.
- Exibir o **saldo restante** do cartão após as operações.

---

## 🔑 Classes e Responsabilidades

### `CartaoDeCredito`
- Armazena **limite**, **saldo** e **histórico de compras**.
- Método `lancaCompra(Compra)` → valida se há saldo e registra a compra.

### `Compra`
- Representa uma compra com **descrição** e **valor**.
- Implementa `Comparable` para permitir ordenação das compras por valor.

### `Principal`
- Responsável pela **entrada de dados** via `Scanner`.
- Controla o **fluxo do programa** (cadastro de compras, validação e saída).
- Exibe o **resumo das compras** e o **saldo final**.
