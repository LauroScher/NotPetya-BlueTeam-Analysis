# NotPetya-BlueTeam-Analysis
# 🛡️ Cyber Defense Operations Report: NotPetya Analysis

Este repositório contém o relatório final do estudo de caso sobre o malware **NotPetya**, desenvolvido como parte das avaliações práticas de cibersegurança. 

O projeto consistiu em dissecar a anatomia do ataque (que operou como um *Wiper* disfarçado de Ransomware), mapear suas táticas no framework **MITRE ATT&CK** e reproduzir sua cadeia de infecção através de 5 laboratórios controlados na plataforma **TryHackMe**.

## 🔍 Escopo da Análise (Blue Team)
* **Vetor Inicial:** Comprometimento de Cadeia de Suprimentos (Supply Chain via NPM).
* **Reconhecimento Interno e Movimento Lateral:** Enumeração SMB e exploração da vulnerabilidade MS17-010 (EternalBlue).
* **Escalada e Evasão:** Injeção de processos (VirtualAlloc) e extração de credenciais em memória via Mimikatz (LSASS).
* **Impacto:** Persistência via tarefas agendadas e destruição da MFT/MBR.

## 👥 Equipe
* Lauro Scher - Documentação, Revisão Técnica e Execução de Laboratórios  
* Mateus Araujo - Documentação, Revisão Técnica e Execução de Laboratórios
* Tibério Cerqueira - Execução de Laboratórios  
* Pedro Aires - Execução de Laboratórios  
* Roberto Dourado - Execução de Laboratórios  
* **Orientador:** Prof. Eduardo Muller

📄 **[Clique aqui para ler o relatório completo em PDF](https://drive.google.com/file/d/1XeWMdU4x2T7onbCwS1KLpEmmbcccO29N/view?usp=sharing)**
