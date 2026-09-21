# Roteiro - Entrevista Semi Estruturda de Levantamento de Processos

- Objetivo: Mapear uma cadeia de processos realizados para chegar a finalização dos cadastros de clientes e vendas de consórcio da Consagre Consórcios.
- Entrada:  Quando uma venda é recebida.
- Saida: Venda e cliente cadastrados no sistema interno.

### 1. Quais os documentos necessários para um CPF ou CNPJ comprar um conórcio e como a venda chega a empresa?
* **Pessoa Física (CPF):**
  * Documento de identificação com foto.
  * CPF.
  * Comprovante de residência.
  * Comprovante de renda.
* **Pessoa Jurídica (CNPJ):**
  * Contrato social ou estatuto.
  * Cartão de CNPJ.
  * Documentos dos sócios representantes.
  * Comprovante de faturamento.
* **Formulário/Proposta:**
  * O vendedor encontra um cliente intereçado e preenche uma proposta (física ou digital) com as informações do cliente e da cota.

### 2. Oque acontece com uma venda onde há documentos faltantes ou documentos inválidos?
* **Quem avisa:** O backoffice notifica o vendedor ou o cliente diretamente (pede documentação novamente).
* **Onde trava:** O processo fica retido na etapa de análise de documentação / pendência cadastral.
* **Prazo:** Há um prazo limite para envio das correções. Se estourar, a proposta perde-se a data de corte do grupo (Cliente só será elegivel a participar da assembléia do mês seguinte).

### 3. Existem ferramentas externas que são consultadas na verificação dos documentos?
* Utilizam consultas à Receita Federal e Sintegra (para PJ).
* Usam sistemas de proteção ao crédito (SPC/Serasa).

### 4. Oque pode fazer com que um cadastro não seja efetuado?
* Falta de documentos obrigatórios.
* Idade fora do limite aceito (18 anos) ou sem a assinatura conjunta dos responsáveis (16-17 anos).
* Restrição cadastral ou fiscal impeditiva no CPF ou CNPJ (CPF/CNPJ regularizado).
* Assinatura digital inválida ou pendente.
* Não pagamento ou falta de compensação da primeira parcela/taxa de adesão.

### 5. Quando um cadastro é aprovado, quais os passos seguintes?
1. Entrevistado relatou que a importação dos dados da proposta é feita no sistema interno.
2. Vinculação oficial da venda ao grupo e cota do consórcio.
   
### 6. Como o processo lida com um cliente comprando uma segunda cota?
* Com cadastro existente apenas e cadastrada a venda vinculada ao cliente.
* A mesma documentação precisa ser entregue.

### 7. Existem pontos de falha no processo, onde algum passo deve ser refeito?
* Erros manuais de digitação de dados cadastrais (Volta para a etepa anterior ).
* Documentos enviados com baixa qualidade ou ilegíveis (se cria uma solicitação de reenvio e volta para a etapa de analise de documentação).

### 8. Quais são as saídas do processo? Existem saidas negativas, como um cancelamento do cadastro?
* **Saídas possíveis:** Cadastrado, Não Cadastrado e o estado intermediário (documentação ou pagamento ainda pendente).
* **Em caso de recusa/cancelamento:**
  * Vendedor e cliente são avisados do motivo.
  * Se houve pagamento prévio, é aberto processo para devolução do dinheiro.
  * O histórico da tentativa não é apagado; fica gravado no sistema para consultas futuras e auditoria.

### 9. Quais são os setores envolvidos no cadastro do cliente e venda?
* **Vendedor:** Faz a captação e o preenchimento inicial dos dados.
* **Backoffice:** Recebe o fluxo, checa a documentação e digita/valida tudo no sistema.
* **Analista:** Faz a segunda checagem e dá a aprovação final antes da liberação da venda.