# Sistema de Estacionamento 🚗

Este projeto implementa um sistema de estacionamento em C#, permitindo:

- **Cadastrar veículos:** O usuário insere a placa de um veículo para adicioná-lo à lista de estacionados.  
- **Remover veículos:** Remove veículos informando a placa e calcula o valor a ser pago com base no preço inicial e na duração da estadia.  
- **Listar veículos:** Exibe todos os veículos estacionados no momento.  
- **Encerrar o programa:** Fecha o sistema.  

## 🚀 Tecnologias Utilizadas

- **Linguagem:** C#  
- **Estrutura:**  
  - `Program.cs`: Interface de interação com o usuário via console.  
  - `Estacionamento.cs`: Gerencia a lógica de negócios (cadastro, remoção e listagem de veículos).  
- **Entrada de Dados:** Preço inicial e preço por hora configurados no início da execução.  
- **Manipulação de listas:** `List<string>`

## 📋 Pré-requisitos

- .NET SDK instalado na máquina.  
- Console configurado para exibir caracteres UTF-8.

## 🛠️ Como executar o projeto

1. Clone este repositório:
   ```bash
   git clone <https://github.com/LarissaAndreaPRuiz/ProjetoEstacionamento.git>
