# Treinamento de Cadastro  
**Rodrigo Amaral**

## Objetivos do treinamento:

- Capacitar para saber registrar corretamente informações relevantes, minimizando erros e garantindo uma transição suave na implementação do ERP.

---

## Importância do cadastro de dados:

- O cadastro de dados é fundamental para o sucesso das operações de uma empresa, pois fornece informações precisas para a tomada de decisões e otimiza processos como faturamento e compras.

---

## Estrutura do sistema ERP:

- O sistema ERP integra diferentes áreas da empresa, permitindo um fluxo de informações contínuo entre departamentos, desde finanças até logística, garantindo uma gestão unificada.

---

## Integração:

- É a junção de dois sistemas que se comunicam entre si.

---

## Cadastros principais:

- **Cadastro Geral**
- **Cadastro de Itens**
- **Informações Fiscais para Faturamento**
- **Configuração Inicial do Sistema**

---

### Cadastro Geral:

Cadastro geral é fundamental para o gerenciamento da empresa. Informações como:
- Razão social
- CNPJ
- Endereço
- Limite de crédito

Devem ser registradas no sistema ERP para facilitar a administração e a tomada de decisões.

---

### Cadastro de Itens:

O cadastro de itens inclui dados cruciais, como:  
- **Nome**  
- **Taras**  
- **Classificação**  
- **Layout**

---

### Informações Fiscais para Faturamento:

- **CFOP**  
- **Tributação**  
- **ICMS**

---

### Configuração Inicial do Sistema:

- **Permissões**  
- **Criação de usuários**  
- **Operações da empresa**

---

## Personalizações de Regras de Negócio:

- Adaptações de fluxos de trabalho  
- Criação de campos personalizados  
- Ajustes  
- Regras de validação

---

## Licença de Uso:

- Quantos acessos simultâneos o cliente terá

---

## Tipos de Cadastros:

| Código | Descrição                          |
|--------|------------------------------------|
| C      | Clientes Mercado Interno          |
| D      | Prestadores de Serviço            |
| E      | Comprador                         |
| F      | Fornecedores Almoxarifado         |
| P      | Produtor: Animal Vivo             |
| I      | Fornecedor: Animal Abatido        |
| H      | Empresas do Grupo (Filiais)       |
| K      | Plano de Contas                   |
| M      | Motoristas                        |
| N      | A Pagar Diversos (Impostos, Taxas e Outros) |
| O      | Perfil Tributário - CG            |
| S      | Sistema                           |
| T      | Transportador                     |
| U      | Funcionários                      |
| V      | Vendedores                        |
| X      | Clientes Mercado Externo          |
| Y      | Fornecedor Mercado Externo        |
| Z      | Prospect                          |

---

# Cadastro de Funcionário no ERP: Tipo (U) Funcionários

**Observações:**
- Sempre use letra maiúscula e sem acentos.
- Caso erre o CPF ou CNPJ, será necessário inativar o cadastro e realizar um novo.

## Cadastro Geral:
- **Cadastro Geral**
- **Novo**

## Tipo de Cadastro:
- **Lupa**
- **Funcionários**

## Tipo de Pessoas:
- **Física**  
  - CPF (CI)  
- **Jurídica**  
  - CNPJ (NIT)

## Indicador de IE:
- **Não Aplicável**

## Estado:
- **PR**

## Nome: Razão Social  
- **Apelido: Nome Fantasia**

## Filial:
- **100**  
  Qual filial será feito o cadastro.

## Endereço:
- Preencha os campos obrigatórios.

**Observações:**
- Caso seja o mesmo endereço: replicar o mesmo endereço.  
- Caso algum endereço seja diferente, preencher campo a campo: faturamento, cobrança, entrega, residencial, trabalho.

## Salvar
---

# Responsável pelo Cadastro de Todos:

## Módulo Tabela Auxiliares:

- **Usuário:**  
  - @Mateus  
    - **Código de Cadastro:**  
      - 86006 - Mateus de Souza  
      - **Posto de Trabalho:**  
        - CPD01 * C.P.D

---

# Produtor Rural

## Cadastro Geral:
- **Cadastro Geral**
- **Novo**

## Tipo de Cadastro:
- **Lupa**  
  - **P - Produtor**

## Tipo de Pessoas:
- **Física**  
  - CPF (CI)

## Indicador de IE:
- **Não Aplicável**

## Estado:
- **Acre**

## Nome:  
- **Apelido:**

## Filial:
- **100**  
  Qual filial será feito o cadastro.

## Endereço:
- Preencha os campos obrigatórios.

**Observações:**
- Caso seja o mesmo endereço: replicar o mesmo endereço.  
- Caso algum endereço seja diferente, preencher campo a campo: faturamento, cobrança, entrega, residencial, trabalho.

## E-mail:
- E-mail do cliente.  
  Caso ele não tenha e-mail: **A@A.COM.BR**

## Telefone:
- **(99)99999999**

## Contabilidade:
- **Speed Reinf/eSocial:**  
  Indicativo da opção pelo produtor rural pela forma de tributação da contribuição previdenciária:  
  - **Opção 1:** A empresa recolhe.  
  - **Opção 2:** O produtor que recolhe.

## Salvar

---

# Propriedade Rural

## Cadastro Geral:
- **Propriedade Rural**
- **Novo**

## Produtor Rural:
- **Lupa**

## Nome da Propriedade:
- CPF/CNPJ  
- Inscrição Estadual  
- Endereço

## Mercados Habilitados:
- **Lista Geral**  
- **Mercado Interno**  
- **Irã**

# TMV - Tipo de Movimentação

- **Sisatak**  
  - **Compra de Animais:**  
    - T220  
    - Perfil Tributário  
      - Produtor Rural Mateus PF  
      - Propriedade Rural

---

# Cadastro de Comprador

## Cadastro Geral:
- **Cadastro Geral**
- **Novo**

## Tipo de Cadastro:
- **Lupa**  
  - **E - Comprador**

## Tipo de Pessoas:
- **Física**  
  - CPF (CI)  
- **Jurídica**  
  - CNPJ (NIT)

## Indicador de IE:
- **Não Aplicável**

## Estado:
- **PR**

## Nome: Razão Social  
- **Apelido: Nome Fantasia**

## Filial:
- **100**  
  Qual filial será feito o cadastro.

## Endereço:
- Preencha os campos obrigatórios.

**Observações:**
- Caso seja o mesmo endereço: replicar o mesmo endereço.  
- Caso algum endereço seja diferente, preencher campo a campo: faturamento, cobrança, entrega, residencial, trabalho.

## Abrir o Cadastro Produtor:
- Comercial  
  - **Vendedor:** Colocar o comprador.

## Salvar

---

# Cadastro de Transportadora

## Cadastro Geral:
- **Cadastro Geral**
- **Novo**

## Tipo de Cadastro:
- **Lupa**  
  - **T - Transportadora**

## Tipo de Pessoas:
- **Jurídica**  
  - CNPJ (NIT)

## Indicador de IE:
- **Não Aplicável**

## Estado:
- **PR**

## Nome: Razão Social  
- **Apelido: Nome Fantasia**

## Filial:
- **100**  
  Qual filial será feito o cadastro.

## Endereço:
- Preencha os campos obrigatórios.

**Observações:**
- Caso seja o mesmo endereço: replicar o mesmo endereço.  
- Caso algum endereço seja diferente, preencher campo a campo: faturamento, cobrança, entrega, residencial, trabalho.

---

# Cadastro de Fornecedor Almoxarifado

- **Fornecedor Interno:** Computador, Embalagem, Faca

## Cadastro Geral:
- **Cadastro Geral**
- **Novo**

## Tipo de Cadastro:
- **Lupa**  
  - **F - Almoxarifado**

## Tipo de Pessoas:
- **Jurídica**  
  - CNPJ (NIT)

## Indicador de IE:
- **Não Aplicável**

## Estado:
- **PR**

## Nome: Razão Social  
- **Apelido: Nome Fantasia**

## Filial:
- **100**  
  Qual filial será feito o cadastro.

## Endereço:
- Preencha os campos obrigatórios.

**Observações:**
- Caso seja o mesmo endereço: replicar o mesmo endereço.  
- Caso algum endereço seja diferente, preencher campo a campo: faturamento, cobrança, entrega, residencial, trabalho.

---

# (I) Fornecedor

**Fornecedor - Para Revenda**

## Cadastro Geral:
- **Cadastro Geral**
- **Novo**

## Tipo de Cadastro:
- **Lupa**  
  - **(I) Fornecedor**

## Tipo de Pessoas:
- **Jurídica**  
  - CNPJ (NIT)

## Indicador de IE:
- **Não Aplicável**

## Estado:
- **PR**

## Nome: Razão Social  
- **Apelido: Nome Fantasia**

## Filial:
- **100**  
  Qual filial será feito o cadastro.

## Endereço:
- Preencha os campos obrigatórios.

**Observações:**
- Caso seja o mesmo endereço: replicar o mesmo endereço.  
- Caso algum endereço seja diferente, preencher campo a campo: faturamento, cobrança, entrega, residencial, trabalho.


# Cadastro (M) Motorista

## Cadastro Geral:
- **Cadastro Geral**
- **Novo**

## Tipo de Cadastro:
- **Lupa**  
  - **(M) Motorista**

## Tipo de Pessoas:
- **Física (NIT)**

## Indicador de IE:
- **Não Aplicável**

## Estado:
- **PR**

## Nome: Razão Social  
- **Apelido: Nome Fantasia**

## Filial:
- **100**  
  Qual filial será feito o cadastro.

## Endereço:
- Preencha os campos obrigatórios.

**Observações:**
- Caso seja o mesmo endereço: replicar o mesmo endereço.  
- Caso algum endereço seja diferente, preencher campo a campo: faturamento, cobrança, entrega, residencial, trabalho.

---

# Customização

## Customização:
- **Cadastro Geral**
  - **Tipos de Cadastro**
  - **N**
    - Campos obrigatórios

---

# Cadastro de Dispositivos

## Objetivo:
- Para cadastro de força de vendas do mobile (Cadastro de ID para apenas um celular).

---

# Permissões de Recursos (Criação de Perfil)

## Atenção:
- Para poder utilizar o perfil de um grupo:  
  - Crie o perfil (grupo).  
  - Vincule o grupo ao perfil de usuário no cadastro do usuário.

---

## Passo a Passo:

### Cadastro Geral:
- Criar em **Cadastro Geral** o usuário:
  - **Cadastro Geral**
    - **Novo**

### Tabelas Auxiliares:
- Criar perfil do grupo (PF) em **Tabelas Auxiliares**.  
  - Após finalizar o cadastro, ir em **Tipo de Cadastro** e indicar o tipo de cadastro (neste exemplo utilizamos o tipo 'C').  
- Criar usuário em **Tabelas Auxiliares** (Funcionário).  
  - No campo **Perfil de Usuário**, coloque o PF que foi criado.

### Abrir o Usuário Principal no Sisatak:
- Ferramentas:  
  - **Cadastros e Logins**  
    - **Principal**
      - **Menu**
      - **Pesquisar**
      - Localizar o usuário:
        - Senha  
        - Confirmar a senha  
      - Adicionar manualmente as permissões e telas que o usuário irá poder ter acesso.  
      - Fechar todo o programa e abrir com o login do usuário.  
      - Verificar se as alterações foram realizadas com sucesso.

# Usuários

**Funcionário:**  
- FUNCIONARIO.MATEUS.TI  
- Senha: 123  

**Menor Aprendiz Mateus:**  
- PFMATEUS.TI  

---

# Logística

## Cadastro de Veículo

### Módulo Logístico:
- **Tipos de Veículos:**
  - Código  
  - Nome  
  - Tipo Rodado  
  - Função do Veículo  
  - Faixa Inicial de Peso e Final  
  - Faixa Inicial de Quantidade de Pedidos e Final  

### Especificações:
- O motorista deve sempre ser do tipo **M**.

---

## Cadastro de Veículo:
- **Veículo:**
  - Placa  
  - UF Placa  
  - Tipo de Veículo  
  - Marca/Modelo  
  - Quilometragem  
  - Quilometragem Autotrack  
  - Centro de Custo  

- **Especificações:**
  - Preencha as informações obrigatórias.


