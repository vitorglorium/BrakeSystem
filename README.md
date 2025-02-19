#  Sistema de Freios - Análises Estáticas e Dinâmicas

### Sobre o Projeto
Este projeto envolve a validação estática e dinâmica do susbsistema de freios em protótipos do tipo Formula SAE. 🏎️💨 <br>
A ideia é, em cima de cada um dos tópicos, criar um documento com toda programação que foi utilizada e compactar mais adiante como uma ferramenta para o subsistema.<br>
Cada tópico quando abordado será evidencidao sua evolução e também sua conclusão para facilitar, até o término, o entendimento do abaixo proposto.<br>
Ao finalizar cada módulo vou aos poucos compartilhando.

### Progresso
[████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░] 12,32% concluído.

## Temas abordados 
* <ins>`Pedal:` </ins> Curso, Ganho Mecânico, Distribuição de Carga, Analise de Trajetória, BIAS, Regulamento SAE Brasi (conformidade), avaliar modelos e geometrias distintas e seu comportamento.(Quase concluído)<br>
* <ins>`Balance Bar:`</ins> Curso, Estudos de Material, Distribuição de Carga, Análise de Trajetória, inputs e outputs do/no sistema, variações e consequências, Sensoriamento, Elementos Eletrônicos para ajuste, Modelagem de Erros concatenados durante o processo de ajuste e traçar ideal para otimizações futuras, Modelagem do comportamento de materiais não metálicos.<br>
* <ins>`Pinças de Freio:`</ins> Pressão, Dilatação, Distribuição de Carga, Análise de movimentação (No tipo Flutuante), Estudo dos elementos, Análise Termodinamica, Sensoriamento <br>
* <ins>`Pistão da Pinça:`</ins> Distribuição de Carga, Soluções Termodinâmicas, Soluções para vedação, Estudo de Casos, Análise de movimentação e Cases de estudo, Delimitar Limites, Sensoriamento <br>
* <ins>`Pastilha de Freio:`</ins> Estudo de distribuição de Carga, Estudo Tribológico, Análise de Vibrações, Ruídos e teste de Cases diversos quanto a materiais, Estudo Termodinamico, Sensoriamento, Estudo de Geometrias distintas e como isto influencia em outros parametros.
* <ins>`Disco de Freio:`</ins> Estudo Tribológico, Cases de análise Térmico, Modelagem de Transcal, Estudo de Vibração, Alivios de Massa, Comportamento Estático e Dinamico, Distribuição de Carga,Sensoriamento, avaliar elementos que influenciam também na auto-ionização do sistema.
* <ins>`Linha de Freio (Rígida e Flexível):`</ins> Validar dilatação, análise com case de cargas, estudar materiais, transferência de calor, máximos suportados pela linha, Sensoriamento.
* <ins>`Cilindro Mestre:`</ins> Vínculo com Bias, análise de parâmetros, estudo para fabricação de um modelo novo, pressão máxima de operação, modelagem da pressão no cm, modelagem do Curso e dos elementos internos, Estudo de Influências; Curso, Áreas Efetivas, Saídas, Posições de Saídas, Molas de Retorno com diferentes K, Compreender Limites, Sensoriamento.
* <ins>`Conectores:`</ins> Avaliar influência nos fenomenos de transporte, Compreensão de Limites, Caracterização, Distribuição de carga e Sensoriamento
* <ins>`Duto de Freio:` </ins>Sensoriamento, Avaliação CFD, Thermal, Fadigue, Viabilidade de manufatura por processos aditivos ou fruto de laminação com prévio estudo de viabilidade, modelagem física e matemática do que ocorre no escoamento assim como nos fenomenos de transporte, Vincular com Pinças de Freio, Pastilhas e Disco, Modelar estruturas para laminação.
* <ins>`Validação do Coeficiente de Atrito:`</ins>Sensoriamento, curva em função do teste de fadiga, elementos que influenciam, modelagem matemática deste elemento com seu comportamento em função da pressão superficial, simulação de atrito vs resfriamento (cfd)
* <ins>`Validação do Torque:`</ins> Avaliar e Validar o comportamento do Torque durante a frenagem gerando curvas característcias e abordar de maneira matemática a sua modelagem com correções proveniente de fatores visualizados como de grande peso, tais como temperatura e variação do sistema tribológico, influencia de elementos de autoionização
* <ins>`Bancada de Teste:` </ins> Validação do Coeficiente de Atrito da pinça em função da temperatura, validação do torque, testes de estresse, validação de curso do pistão do cilindro mestre, estudo para reter informações sobre a expansão das pinças, influência de materiais no sistema tribológico e influência do meio em sistemas tribológicos, testar vedação e validar/modelar o comportamento com materiais distintos, alterar a influência da temperatura no sistema, forçar fade e reter informações relevantes, realizar um estudo com compósitos, estudo de liga e viabilidade, delimitar um meio para simular a transferência de massa.
  
### Próximos Passos:
- [X] Delimitar o que será feito;
- [] Modelar Matemáticamente;
- [ ] Implementar em Python as modelagens;
- [ ] Criar ecosistema no simulink do matlab
- [ ] Validar empiricamente e criar correções nos modelos;
- [ ] Distribuir o conteúdo em trabalhos acadêmicos diversos;


`Este projeto será executado a longo prazo, manterei o Read.me bem atualizado para que saibam o que ja foi concluído e o que está sendo feito.` <br>
<br>
Caso tenha alguma dúvida peço que entrem em contato!!!


OBS: O projeto esta sendo manipulado inicialmente pelo time de FC do UFPR Formula, estamos delimitando tudo que precisamos e então faremos a criação dos elementos citados.<br>
Outro ponto é que em algumas das coisas apontadas acima não teremos a validação empírica por limitações financeiras. Faremos o possível com o possível e possivelmente com parcerias apenas.
