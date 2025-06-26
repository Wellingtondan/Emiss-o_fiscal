## Emissão Fiscal

### Transferência entre estabelecimentos da mesma empresa

- Ferro STORE (LOJA) ↔️ Ferro STORE (CD)
  
Operação lançada com CFOP 1.152 na entrada e 5.152 na saída. Não gera direito a crédito de PIS/COFINS, uma vez que se trata de movimentação de estoque entre estabelecimentos da mesma empresa, sem envolvimento financeiro.

**Dados**

- **CFOP:** 1.152 (Entrada)

- **CST PIS/COFINS:** 70 – Operação sem direito a crédito

- **Crédito de PIS/COFINS:** Não se aplica

- **Justificativa:** Operação de transferência de mercadorias entre estabelecimentos do mesmo titular, sem geração de receita ou valor financeiro. Portanto, não gera direito a crédito de PIS/COFINS, conforme previsto na legislação das contribuições.

- **Dados para emissão de nota com a base legal:** Operação de simples transferência entre estabelecimentos da mesma empresa, sem geração de receita, conforme arts. 3º, §2º, II da Lei 10.637/2002 (PIS) e Lei 10.833/2003 (COFINS), art. 3º, §1º da Lei 9.718/1998 e arts. 166 e 167 da IN RFB 1.911/2019. CST 70 – operação sem direito a crédito.

   - Nota fiscal referente à transferência de mercadoria entre filiais da mesma empresa, sem fins comerciais. Operação sem direito a crédito de PIS/COFINS.
 

| TIPO   | CFOP | CST PIS/COFINS | OBSERVAÇÃO |
|---------|----------|---------|----------|
| Entrada | 1.152 | 70 | Operação sem direiro a crédito |
| Saída | 5.152 | 04 | Operação sem incidência (Não tributada) |


## Devolução de fornecedores

### 1. Devolução sem Substituição Tributária (ICMS próprio destacado - TRIBUTADO)

- Devolução de mercadoria recebida como Tributado.

**Dados**

- **CFOP:** 5.102 (Devolução de compra de mercadoria)

- **CST PIS/COFINS:** 010 – Operação tributável com crédito (ou outro conforme caso)

- **Crédito de PIS/COFINS:** Normalmente não gera crédito, pois é operação de devolução.

- **Tratamento do ICMS:** Deve ser destacado o ICMS próprio nos campos próprios da NF-e, com base e valor iguais à operação original.

- **Justificativa:**

   - Devolução que anula operação anterior, conforme art. 57 do RICMS/2000 e Convênio ICMS 54/2000.

   - ICMS próprio destacado normalmente para permitir o estorno do crédito.

- **Base legal:**

   - Art. 57 do RICMS/2000

   - Convênio ICMS 54/2000

   - Arts. 3º, §§ 1º e 2º das Leis 10.637/2002 (PIS) e 10.833/2003 (COFINS)

   - IN RFB 1.911/2019

| TIPO   | CFOP | CST PIS/COFINS | OBSERVAÇÃO |
|---------|----------|---------|----------|
| Saída |	5.102 - 6.102	| 49	| Devolução **sem ICMS-ST**; ICMS próprio destacado no campo próprio da NF-e; sem crédito PIS/COFINS |
| Entrada | 1.102 - 2.102 | 70 | Recebimento da devolução sem direito a crédito de PIS/COFINS, pois não houve geração de receita |

### 2. Devolução com Substituição Tributária (ST)

- Devolução de mercadoria recebida com ICMS-ST.

**Dados**

- **CFOP:** 5.411 (Devolução de compra de mercadoria com ICMS-ST)

- **CST PIS/COFINS:** 010 – Operação tributável com crédito (ou conforme caso)

- **Crédito de PIS/COFINS:** Geralmente não gera crédito, por não ser operação geradora de receita.

- **Tratamento do ICMS e ICMS-ST:**

   - ICMS próprio destacado normalmente no campo próprio da NF-e.

   - ICMS-ST **não deve ser destacado no campo próprio do ICMS da NF-e na devolução**.

   - Base de cálculo e valor do ICMS-ST devem ser informados no campo **“Informações Adicionais de Interesse do Fisco (infAdFisco)”**.

   - Valor do ICMS-ST registrado no campo **“Outras despesas acessórias (vOutro)”** para validação do documento fiscal.

- **Justificativa:**

   - Devolução que anula operação anterior com ST, conforme art. 127, §5º e art. 274, §3º do RICMS/SP e cláusula primeira do Convênio ICMS 54/2000.

   - Necessário informar ICMS-ST nos campos indicados para evitar rejeição pela NF-e.

- **Base legal:**

   - Art. 127, §5º e art. 274, §3º do RICMS/SP

   - Cláusula primeira do Convênio ICMS 54/2000

   - Arts. 3º, §§ 1º e 2º das Leis 10.637/2002 (PIS) e 10.833/2003 (COFINS)

   - IN RFB 1.911/2019

| TIPO   | CFOP | CST PIS/COFINS | OBSERVAÇÃO |
|---------|----------|---------|----------|
| Saída |	5.411 - 6.411	| 49	| Devolução com ICMS-ST; ICMS próprio destacado no campo próprio; valor do ICMS-ST informado em “Outras Despesas Acessórias” e detalhado em “Informações Adicionais”; sem crédito de PIS/COFINS |
| Entrada | 1.411 - 2.411 | 70 | Recebimento da devolução com ICMS-ST; operação sem direito a crédito de PIS/COFINS |

> Exemplo para campo Informações Adicionais (infAdFisco):

```
Devolução referente à NF nº 12345, série 1, de 10/06/2025.
Base de cálculo do ICMS-ST: R$ 5.000,00. Valor do ICMS-ST: R$ 850,00.
Informações conforme art. 127, §5º e art. 274, §3º do RICMS/SP e cláusula primeira do Convênio ICMS 54/2000.
ICMS-ST informado em “Outras Despesas Acessórias” (vOutro), conforme regras da NF-e.
```


### 3. 📄 Resposta à Consulta Tributária 30001/2024 (SP)

**Assunto:** Devolução de mercadoria – Substituição tributária (ICMS-ST) – Documento fiscal – Direito ao crédito

> 🔗 [Resposta à consulta](https://legislacao.fazenda.sp.gov.br/Paginas/RC30001_2024.aspx)

---

#### 4. ✅ Pontos principais:

**🔹 Competência Interestadual**  

O Estado de São Paulo **não regula** a forma de emissão de NF-e por contribuintes de outros Estados, como o Paraná. Portanto, **não opina** sobre a vedação do destaque do ICMS-ST na devolução conforme regras locais.

**🔹 Obrigatoriedade do Destaque (SP)**  

Para que o contribuinte paulista tenha **direito ao crédito do ICMS**, o imposto deve estar **destacado em documento fiscal hábil**, mesmo quando se trata de devolução de mercadoria sujeita à substituição tributária.

**🔹 ICMS Próprio e ST na Devolução**

- O **ICMS próprio** deve ser **destacado nos campos próprios** da NF-e.
- O **ICMS-ST** **não é destacado**, mas deve ser:
  - Informado no campo **"Informações Adicionais de Interesse do Fisco"** (`infAdFisco`), com **base de cálculo e valor**.
  - Lançado no campo **`vOutro` (Outras Despesas Acessórias)** para que o **valor total da NF-e seja validado** pelo sistema.

---

#### 5. 📚 Fundamento Legal:

- **RICMS/SP**:  
  - Art. 127, §5º  
  - Art. 274, §3º  
  - Art. 57  
  - Art. 59, §1º, item 2

- **Convênio ICMS 54/2000**  
- **Decisão Normativa CAT 04/2010**

---

#### 6. ⚠️ Consequência:

Caso o **ICMS próprio não esteja destacado** na NF-e da devolução, **não será permitido o crédito** 
