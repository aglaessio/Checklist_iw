Manual de Utilização do Formulário de Informações para o Evento
Este manual tem como objetivo guiar o usuário no preenchimento e utilização do Formulário de Informações para o Evento, que permite coletar dados essenciais para o planejamento técnico de eventos. O formulário é uma ferramenta web que, após o preenchimento, gera um PDF com as informações fornecidas.

1. Introdução
O formulário foi desenvolvido para facilitar a coleta de informações técnicas necessárias para a organização de eventos. Ele é dividido em seções que abrangem recursos humanos, acessos, bilheterias, horários de funcionamento e outras necessidades. Após o preenchimento, o usuário pode gerar um PDF com os dados fornecidos.

2. Como Acessar o Formulário
Pré-requisitos:

Navegador web moderno (Google Chrome, Firefox, Edge, etc.).

Conexão com a internet (para carregar as bibliotecas externas).

Instalação:

Clone o repositório ou faça o download dos arquivos do projeto:

bash
Copy
git clone https://github.com/seu-usuario/formulario-evento.git
Navegue até a pasta do projeto:

bash
Copy
cd formulario-evento
Abra o arquivo index.html no seu navegador.

3. Estrutura do Formulário
O formulário é dividido em cinco seções principais:

Recursos Humanos:

Número de técnicos necessários: Informe a quantidade de técnicos que serão necessários para o evento.

Acessos e Validações:

Quantidade de portões de acesso: Informe o número de portões que estarão disponíveis para o evento.

Número total de validações: Informe o número total de validações que serão realizadas nos portões.

Bilheterias e Guichês:

Quantidade de bilheterias: Informe o número de bilheterias que estarão disponíveis.

Número total de guichês de venda: Informe o número total de guichês de venda que estarão disponíveis.

Horários de Funcionamento:

Abertura da Bilheteria: Informe o horário de abertura da bilheteria.

Abertura da Portaria: Informe o horário de abertura dos portões.

Outras Necessidades:

Wi-fi para bilheteria e portaria: Informe se a produção do evento deve disponibilizar Wi-fi para a bilheteria e portaria.

4. Como Preencher o Formulário
Recursos Humanos:

No campo "Número de técnicos necessários", insira a quantidade de técnicos que serão necessários para o evento.

Acessos e Validações:

No campo "Quantidade de portões de acesso", insira o número de portões que estarão disponíveis.

No campo "Número total de validações", insira o número total de validações que serão realizadas.

Bilheterias e Guichês:

No campo "Quantidade de bilheterias", insira o número de bilheterias que estarão disponíveis.

No campo "Número total de guichês de venda", insira o número total de guichês de venda.

Horários de Funcionamento:

No campo "Abertura da Bilheteria", insira o horário de abertura da bilheteria.

No campo "Abertura da Portaria", insira o horário de abertura dos portões.

Outras Necessidades:

No campo "A Produção do Evento deverá disponibilizar Wi-fi para bilheteria e portaria!", selecione "Sim" ou "Não" de acordo com a necessidade.

5. Como Gerar o PDF
Após preencher todos os campos do formulário, clique no botão "Gerar PDF" localizado no final do formulário.

Um arquivo PDF será gerado automaticamente com todas as informações fornecidas.

O PDF será salvo com o nome "formulario_evento.pdf" no seu computador.

6. Exemplo de Saída do PDF
O PDF gerado terá o seguinte formato:

Copy
FORMULÁRIO DE INFORMAÇÕES PARA O EVENTO

1. RECURSOS HUMANOS
Número de técnicos necessários: 5

2. ACESSOS E VALIDAÇÕES
Quantidade de portões de acesso: 3
Número total de validações: 10

3. BILHETERIAS E GUICHÊS
Quantidade de bilheterias: 1
Número total de guichês de venda: 6

4. HORÁRIOS DE FUNCIONAMENTO
Abertura da Bilheteria: 10:00
Abertura da Portaria: 12:00

5. OUTRAS NECESSIDADES
A organização do Evento deverá disponibilizar Wi-fi para bilheteria e portaria!: Sim

Gerado em: 25/10/2023 14:30
7. Personalização
Alterar Estilos: Para personalizar o design do formulário, edite o arquivo styles.css.

Adicionar Campos: Para adicionar novos campos ao formulário, edite o arquivo index.html e atualize o scripts.js para incluí-los no PDF.

Alterar Fonte do PDF: No arquivo scripts.js, você pode alterar a fonte usada no PDF modificando a linha doc.setFont("Times", "normal"); para outra fonte suportada pelo jsPDF.

8. Dicas e Boas Práticas
Certifique-se de preencher todos os campos obrigatórios (marcados com *).

Verifique as informações antes de gerar o PDF para garantir que estão corretas.

Caso precise de mais espaço para informações adicionais, considere adicionar campos de texto livre no formulário.

9. Suporte e Contribuição
Problemas ou Dúvidas: Caso encontre algum problema ou tenha dúvidas, abra uma issue no repositório do projeto.

Contribuições: Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests com melhorias ou correções.

10. Licença
Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

11. Conclusão
O Formulário de Informações para o Evento é uma ferramenta simples e eficaz para coletar e organizar informações técnicas essenciais para o planejamento de eventos. Com este manual, esperamos que você consiga utilizar o formulário de forma eficiente e gerar PDFs com todas as informações necessárias para o sucesso do seu evento.
