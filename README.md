# rpa-operational-process-automation

# 🤖 Automação RPA de Processo Operacional (Python + SAP + Web Scraping)

---

# 📌 Proposta do Projeto

Este projeto teve como objetivo automatizar integralmente um processo operacional de alto volume, responsável pelo tratamento de solicitações recebidas através de um portal corporativo e processadas em um sistema legado.

A solução foi desenvolvida em Python utilizando técnicas de RPA (Robotic Process Automation), Web Scraping e integração com sistema ERP, eliminando atividades repetitivas realizadas manualmente e garantindo maior eficiência operacional.

O fluxo inclui:

- Coleta automática de solicitações
- Download de arquivos individuais
- Tratamento e cruzamento de dados
- Atualização automática de registros
- Validação pós-processamento
- Geração de relatórios
- Comunicação automática por e-mail

---

# 🎯 Objetivos

- Automatizar um processo operacional executado manualmente
- Reduzir o tempo de tratamento das solicitações
- Eliminar erros operacionais
- Garantir o cumprimento dos SLAs
- Criar rastreabilidade através de relatórios e logs
- Liberar capacidade operacional da equipe para atividades analíticas

---

# 🛠 Tecnologias Utilizadas

- Python
- Pandas
- OpenPyXL
- SAP GUI Scripting
- PyWinAuto
- PyAutoGUI
- Outlook COM
- Web Scraping
- CSV
- Excel

---

# 🏗 Arquitetura da Solução

Portal Web ↓ Web Scraping ↓ Download de Arquivos ↓ Tratamento e Consolidação (Pandas) ↓ Validações de Negócio ↓ Integração Sistema Corporativo ↓ Validação Final ↓ Relatórios e Logs ↓ Envio Automático de E-mails

--- 

# ⚙️ Principais Funcionalidades 
## Extração de Dados 
- Acesso automatizado ao portal
-  Download automático dos arquivos individuais
- Consolidação das informações recebidas
  
## Tratamento de Dados 
- Leitura de planilhas Excel
- Leitura de arquivos CSV
- Padronização de dados
- Cruzamento entre diferentes fontes

## Integração com Sistema Corporativo 
- Navegação automática
- Inclusão de registros
- Atualização de informações
- Encerramento automático de processos

## Validações 
- Regras de negócio
- Conferência de consistência
- Tratamento de exceções
- Retentativas automáticas

## Comunicação 
- Envio automático de relatórios operacionais
- Notificação de conclusão
- Geração de logs de erro

--- 

# 📊 Resultados Obtidos 
## Indicadores do Projeto 
| Indicador | Resultado | 
|------------|------------| 
| Volume tratado em testes | 1.880 registros | 
| Média diária | 117 registros | 
| Redução de tempo | 55% | 
| Tempo manual | ~3 minutos por registro | 
| Tempo automatizado | ~1 minuto por registro | 
| Tempo médio atual | 89 segundos por registro | 
| Redução do TMA | 19 dias → D+1 | 
| Capacidade operacional | Dobrada | 

--- 

# 🚀 Impacto da Automação 
### Antes 
- Processo totalmente manual
- Alto risco de retrabalho
- Dependência operacional elevada
- Possibilidade de atraso nos prazos

### Depois 
- Execução automática ponta a ponta
- Redução significativa do tempo de processamento
- Padronização do processo
- Maior confiabilidade operacional
- Capacidade ampliada sem aumento de equipe

--- 

# 🧠 Desafios Técnicos 
- Integração com Sistema Legado Desenvolvimento de automação utilizando SAP GUI Scripting, sem utilização de APIs. 
- Tratamento de Bloqueios Implementação de retentativas automáticas para registros temporariamente indisponíveis. 
- Robustez Operacional O processamento foi desenvolvido para continuar executando mesmo diante de erros individuais. 
- Consolidação de Múltiplas Fontes Integração de informações provenientes de portais web, arquivos CSV, planilhas Excel e sistema corporativo. 

--- 

# 💻 Exemplo de Código 
## Tratamento de DataFrames 
python df_final = df_web.merge( df_sistema, on="protocolo", how="inner" )

# 📈 Competências Demonstradas
- Automação de Processos (RPA)
- Python
- Manipulação de Dados com Pandas
- Integração de Sistemas
- Excel Automation
- SAP GUI Scripting
- Tratamento de Exceções
- Engenharia de Processos
- Melhoria Contínua
- Geração de Relatórios

---

# 📷 Imagens do Projeto
- Fluxo da Automação
Inserir imagem do fluxo do processo.
assets/fluxo-rpa.png

- Arquitetura da Solução
Inserir diagrama de arquitetura.
assets/arquitetura-rpa.png

- Dashboard de Acompanhamento
Inserir dashboard com dados anonimizados.
assets/dashboard.png

---

#📚 Aprendizados
Este projeto permitiu aprofundar conhecimentos em:
- Automação corporativa
- Integração entre sistemas heterogêneos
- Tratamento de grandes volumes de dados
- Desenvolvimento de soluções robustas e escaláveis
- Observabilidade e monitoramento de processos automatizados

#⚠️ Observação
Por questões de confidencialidade e propriedade intelectual, o código-fonte completo e detalhes específicos de negócio não são disponibilizados publicamente.
O projeto é apresentado com finalidade demonstrativa, evidenciando a arquitetura, tecnologias empregadas, desafios enfrentados e resultados obtidos.
