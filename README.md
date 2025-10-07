This project focuses on investigating a cybersecurity incident using TheHive as a case management platform and Wireshark for network traffic analysis. The main objective was to identify and document evidence of possible data exfiltration over unencrypted FTP.

I performed a complete investigation cycle — from PCAP analysis to evidence documentation and final reporting. The entire work was conducted in an isolated lab environment, emphasizing accuracy, transparency, and adherence to DFIR (Digital Forensics & Incident Response) best practices.

Project Goal

To build a reproducible, professional workflow for investigating a network incident using open-source DFIR tools. The project demonstrates how to detect suspicious activity in PCAP data, extract and classify evidence, enrich observables via Cortex analyzers, and organize everything in a centralized incident response platform.

Process Overview
Analyzed a PCAP file and identified FTP sessions transmitting files in plaintext.
Extracted and examined file contents, IP addresses, and data flow patterns to establish a timeline of activity.
Used Wireshark, tshark, and tcpflow to reconstruct sessions and retrieve transferred artifacts.
Created a case in TheHive, documenting all details including severity, description, TLP/PAP levels, and observables (IP, file, hash, filename).
Integrated Cortex analyzers to enrich observables, verify file reputations, and correlate findings with external threat intelligence (IOC matching).
Produced a final report containing a detailed timeline, extracted artifacts, and actionable recommendations for mitigation.
Findings and Results

The investigation confirmed that sensitive data was transferred over an unencrypted FTP channel, posing a potential data exfiltration risk. Using TheHive streamlined evidence management, ensured proper chain of custody, and improved analysis efficiency through automated enrichment via Cortex.

The project demonstrated that open-source DFIR tools can deliver a complete incident response workflow — from detection to documentation — with full reproducibility and professional-level structure.

Key Outcomes
Confirmed data exfiltration via plaintext FTP sessions.
Extracted and documented critical artifacts (files, IP addresses, session data).
Built a complete TheHive case with observables and analysis results.
Provided recommendations for network monitoring and migration to encrypted protocols (FTPS/SFTP).
Conclusion

This project illustrates how TheHive, Cortex, and network forensics tools can be effectively combined for incident response and evidence-based analysis. The results validate the power of open-source DFIR ecosystems for building structured, transparent, and scalable investigation workflows.


********************************************************************************************************************************************************************************************************************************************************************************************************************

HiveGuard Forensics — Investigação de Incidente e Análise de PCAP
Sobre o projeto

Este projeto tem como foco a investigação de um incidente de segurança cibernética utilizando o TheHive como plataforma de gestão de casos e o Wireshark para análise de tráfego de rede. O principal objetivo foi identificar e documentar evidências de possível exfiltração de dados por meio de FTP não criptografado.

Realizei todo o ciclo de investigação — desde a análise do PCAP até a documentação das evidências e a elaboração do relatório final. Todo o trabalho foi conduzido em um ambiente de laboratório isolado, priorizando precisão, transparência e conformidade com as boas práticas de DFIR (Digital Forensics & Incident Response).

Objetivo do projeto

Construir um fluxo de trabalho reproduzível e profissional para investigação de incidentes de rede utilizando ferramentas DFIR de código aberto. O projeto demonstra como detectar atividades suspeitas em dados PCAP, extrair e classificar evidências, enriquecer observáveis por meio dos analisadores do Cortex e organizar tudo em uma plataforma centralizada de resposta a incidentes.

Etapas do processo
Analisei o arquivo PCAP e identifiquei sessões FTP transmitindo arquivos em texto simples.
Extraí e examinei o conteúdo dos arquivos, endereços IP e padrões de tráfego para estabelecer uma linha do tempo da atividade.
Utilizei Wireshark, tshark e tcpflow para reconstruir as sessões e recuperar os artefatos transferidos.
Criei um caso no TheHive, documentando todos os detalhes, incluindo severidade, descrição, níveis TLP/PAP e observáveis (IP, arquivo, hash, nome de arquivo).
Integrei os analisadores do Cortex para enriquecer os observáveis, verificar a reputação dos arquivos e correlacionar os achados com fontes externas de inteligência de ameaças (IOC).
Elaborei um relatório final contendo uma linha do tempo detalhada, artefatos extraídos e recomendações práticas de mitigação.
Resultados e descobertas

A investigação confirmou que dados sensíveis foram transferidos por meio de um canal FTP não criptografado, representando risco de exfiltração de informações. O uso do TheHive facilitou a gestão das evidências, garantiu a integridade da cadeia de custódia e aumentou a eficiência da análise com o enriquecimento automático via Cortex.

O projeto demonstrou que ferramentas DFIR de código aberto permitem realizar um fluxo completo de resposta a incidentes — da detecção à documentação — com total reprodutibilidade e estrutura profissional.

Principais resultados
Confirmação da exfiltração de dados via sessões FTP em texto simples.
Extração e documentação de artefatos críticos (arquivos, endereços IP, dados de sessão).
Criação de um caso completo no TheHive com observáveis e resultados de análise.
Elaboração de recomendações para reforçar o monitoramento de rede e adoção de protocolos criptografados (FTPS/SFTP).
Conclusão

Este projeto demonstra como o TheHive, o Cortex e as ferramentas de análise de rede podem ser combinados de forma eficaz para resposta a incidentes e análises baseadas em evidências. Os resultados comprovam o potencial do ecossistema DFIR de código aberto para construir fluxos de investigação estruturados, transparentes e escaláveis.
