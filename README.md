# 📃Automação no processo de Faturamento via XML

## 📌 Atualmente, apesar de toda automação tecnologica que sistemas operacionais nos proporcionam, ainda existem lacunas na operação que podem ser preenchidos com impulsos que consigam ajudar durante o dia a dia.

Durante o processo para gerar um arquivo XML, é necessário que o colaborador permaneça preso ao sistema enquanto o sistema gera o arquivo para que seja faturado
 - Durante esse Processo:
   - O colaborador necessita confirmar as solicitações do sistema.❗
   - Realiza analises desnecessárias do arquivo (visto que o arquivo já irá passar por analise após gerado).❗
   - Necessita colocar manualmente comandos para a finalização do processo.❗
  
     ### Exemplo:

     - Ao finalização de um produto, será necessário que o colaborador **Mude o Status**
     - Em Status definitivo, é necessário a confirmação e **Analise SADT daquele produto**
     - Gere o arquivo seguindo os comentos **ALT+SHIFT+E**
     - Ao confirmar, o sistema acusará **Criticas** que possam estar incorretas no arquivo, baseadas nas regras de cadastro do produto
     - Após gerar o arquivo, o colaborador levará ele até o portal do prestador, realizará o anexo e preenchimentos de dados, para ai **finalizar o processo**
       ❌❌❌
    
   Após a realização dessas etapas, é necessário que seja analisado as criticas **Pós Portal**
   Baseando-se na ideia de que haja alguma critica em algum dos produtos
   O funcionário necessitará desfazer o processo anterior, buscar o produto que contém o erro e realizar todas as etapas novamente

## Utilizando extenções no navegador, visto que o sitema funciona em HTML Tasy, seria possivel: 

- Mapear os comandos utilizados
- Montando prompts capazes de reproduzir esses comandos
- Aplicando em ferramentas de automação (**Claude Code Extension**)

  ### Seria possivel utilizar esse tempo de atividades repetitivas, dispondo em demandas fora do computador, enquanto as ferramentas e os prompts conseguiriam realizar os comandos

  - Dessa maneira, é possivel que seja feita duas atividades simultaneas, diminuindo a sobrecarga e repetição de processos
  - Se fazendo necessário interferencia no fluxo, somente após encontro de **Criticas**
     - Após isso, apenas iniciaria o Prompt novamente.
      ✅✅✅
       
   
   



