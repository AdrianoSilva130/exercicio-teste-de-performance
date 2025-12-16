🚀 Como iniciar o projeto – Testes de Performance com JMeter

Este projeto utiliza o Apache JMeter para execução de testes de performance, simulando carga, usuários simultâneos e analisando o comportamento da aplicação sob estresse.

🔹 1. Clonar o repositório

No terminal:

git clone https://github.com/AdrianoSilva130/exercicio-teste-de-performance.git


Acesse o diretório:

cd exercicio-teste-de-performance

🔹 2. Pré-requisitos
✔️ Java (obrigatório)

O JMeter depende do Java.

Verifique se o Java está instalado:

java -version


👉 Recomendado: Java 8 ou superior

Se não estiver instalado, baixe em:
https://www.oracle.com/java/technologies/downloads/

✔️ Apache JMeter

Baixe o JMeter no site oficial:

👉 https://jmeter.apache.org/download_jmeter.cgi

Extraia o arquivo ZIP em sua máquina.

🔹 3. Iniciar o JMeter
🔸 Windows
jmeter.bat

🔸 Linux / macOS
./jmeter


O JMeter será aberto em modo gráfico (GUI).

🔹 4. Abrir o plano de teste

No JMeter:

Clique em File → Open

Selecione o arquivo .jmx presente no repositório
(exemplo: teste-performance.jmx)

O arquivo .jmx contém todo o plano de testes configurado.

🔹 5. Executar o teste de performance

Clique no botão ▶ Start no JMeter ou use:

Ctrl + R


O teste será iniciado e o JMeter irá simular os usuários conforme configurado.

📊 6. Análise dos Resultados

Durante e após a execução, é possível analisar:

Tempo médio de resposta

Throughput (requisições por segundo)

Taxa de erro

Percentis (90%, 95%, 99%)

Estabilidade da aplicação

Os resultados podem ser visualizados em:

View Results Tree

Summary Report

Aggregate Report

🧠 O que esse projeto demonstra

✔️ Testes de performance com Apache JMeter
✔️ Conhecimento em testes não funcionais
✔️ Configuração de Thread Group
✔️ Análise de métricas de desempenho
✔️ Boas práticas em QA
