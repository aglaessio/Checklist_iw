Formulário de Informações para o Evento
Este projeto consiste em um formulário web para coleta de informações necessárias para o planejamento técnico de eventos. O formulário permite que o usuário preencha dados como recursos humanos, acessos, bilheterias, horários de funcionamento e outras necessidades. Após o preenchimento, é possível gerar um PDF com as informações fornecidas.

Tecnologias Utilizadas
HTML: Estrutura do formulário.

CSS: Estilização do formulário e layout responsivo.

JavaScript: Lógica para gerar o PDF a partir dos dados do formulário.

jsPDF: Biblioteca JavaScript para gerar arquivos PDF.

Como Usar
Pré-requisitos
Navegador web moderno (Google Chrome, Firefox, Edge, etc.).

Conexão com a internet (para carregar as bibliotecas externas).

Instalação
Clone o repositório ou faça o download dos arquivos do projeto.

bash
Copy
git clone https://github.com/seu-usuario/formulario-evento.git
Navegue até a pasta do projeto:

bash
Copy
cd formulario-evento
Abra o arquivo index.html no seu navegador.

Como Funciona
Preencha o Formulário:

Abra o arquivo index.html no navegador.

Preencha todos os campos do formulário com as informações necessárias.

Gerar PDF:

Após preencher o formulário, clique no botão "Gerar PDF".

Um arquivo PDF será gerado com todas as informações fornecidas.

Estrutura do Projeto
index.html: Contém a estrutura HTML do formulário.

styles.css: Contém os estilos CSS para o formulário.

scripts.js: Contém a lógica JavaScript para gerar o PDF.

README.md: Este arquivo, com instruções sobre o projeto.

Exemplo de Saída do PDF
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
Personalização
Alterar Estilos: Edite o arquivo styles.css para personalizar o design do formulário.

Adicionar Campos: Adicione novos campos ao formulário no arquivo index.html e atualize o scripts.js para incluí-los no PDF.

Alterar Fonte do PDF: No arquivo scripts.js, você pode alterar a fonte usada no PDF modificando a linha doc.setFont("Times", "normal"); para outra fonte suportada pelo jsPDF.

Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias ou correções.

Licença
Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

Como Executar o Projeto
Abra o arquivo index.html no seu navegador.

Preencha o formulário.

Clique em "Gerar PDF" para baixar o arquivo com as informações.
