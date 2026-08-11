# 🖥️ Windows Server & Active Directory - Trilha Prática

## 🎯 Objetivos

- Domine a instalação, configuração e administração de ambientes baseados em **Windows Server (2025/2016)**.
- Criar e gerenciar estruturas corporativas no **Active Directory DS** (Usuários, Grupos, OUs e DCs).
- Implementar serviços essenciais de rede (**DNS, DHCP, File Server e Print Server**).
- Aplicar políticas de segurança, restrições e auditoria utilizando **GPO, FSRM e Hardening nativo**.

---

## 🗓️ Progresso do Curso

|  Aula  | Tema                                                       | Fonte / Videos Youtube                            | Status |           Anotações           |
| :----: | :--------------------------------------------------------- | :------------------------------------------------ | :----: | :---------------------------: |
| **01** | Download e Instalação do Windows Server                    | Descomplicando a TI (01) / Marco Andrade (01)     |   ✅   | [Ver Resumo](./modulos/01.md) |
| **02** | Configuração Base de Rede e IP Estático                    | Descomplicando a TI (02) / Marco Andrade (02)     |   ✅   | [Ver Resumo](./modulos/02.md) |
| **03** | Funções, Recursos e Server Manager                         | Descomplicando a TI (03, 14)                      |   ✅   | [Ver Resumo](./modulos/03.md) |
| **04** | Conexão de Área de Trabalho Remota (RDP)                   | Descomplicando a TI (04)                          |   ✅   | [Ver Resumo](./modulos/04.md) |
| **05** | Instalação do Active Directory e Pré-configuração          | Descomplicando a TI (05, 07) / Marco Andrade (03) |   ✅   | [Ver Resumo](./modulos/05.md) |
| **06** | Promovendo o Servidor a Domain Controller (DC)             | Descomplicando a TI (06, 08) / Marco Andrade (04) |   ⏳   | [Ver Resumo](./modulos/06.md) |
| **07** | Criando e Gerenciando Usuários no AD                       | Descomplicando a TI (09) / Marco Andrade (07)     |   ⏳   | [Ver Resumo](./modulos/07.md) |
| **08** | Criando e Gerenciando Grupos de Domínio                    | Descomplicando a TI (10) / Marco Andrade (08)     |   ⏳   | [Ver Resumo](./modulos/08.md) |
| **09** | Organização por Unidades Organizacionais (OUs)             | Descomplicando a TI (11) / Marco Andrade (09)     |   ⏳   | [Ver Resumo](./modulos/09.md) |
| **10** | Configuração de Domain Controller Secundário               | Descomplicando a TI (12)                          |   ⏳   | [Ver Resumo](./modulos/10.md) |
| **11** | Nível Funcional de Domínio e Floresta                      | Descomplicando a TI (13)                          |   ⏳   | [Ver Resumo](./modulos/11.md) |
| **12** | Gerenciamento Remoto do AD via RSAT                        | Descomplicando a TI (15)                          |   ⏳   | [Ver Resumo](./modulos/12.md) |
| **13** | Ingressando Estações Windows no Domínio                    | Descomplicando a TI (16) / Marco Andrade (05)     |   ⏳   | [Ver Resumo](./modulos/13.md) |
| **14** | Instalação e Configuração do Servidor DHCP                 | Marco Andrade (11, 12)                            |   ⏳   | [Ver Resumo](./modulos/14.md) |
| **15** | Reservas de IP no DHCP por MAC Address                     | _Extra Prático_                                   |   ⏳   | [Ver Resumo](./modulos/15.md) |
| **16** | Configuração Avançada do Servidor DNS e Forwarders         | Marco Andrade (13, 14)                            |   ⏳   | [Ver Resumo](./modulos/16.md) |
| **17** | Compartilhamento de Arquivos e Permissões NTFS             | Marco Andrade (15)                                |   ⏳   | [Ver Resumo](./modulos/17.md) |
| **18** | Servidor de Arquivos: FSRM (Cotas e Triagem)               | Marco Andrade (17, 18)                            |   ⏳   | [Ver Resumo](./modulos/18.md) |
| **19** | Conceitos de Objetos de Diretiva de Grupo (GPO)            | Marco Andrade (16)                                |   ⏳   | [Ver Resumo](./modulos/19.md) |
| **20** | Configuração do Servidor de Impressão e Impressora via GPO | Marco Andrade (19, 20)                            |   ⏳   | [Ver Resumo](./modulos/20.md) |
| **21** | Gerenciamento do Firewall do Windows via GPO               | Marco Andrade (21)                                |   ⏳   | [Ver Resumo](./modulos/21.md) |
| **22** | Mapeamento de Discos e Unidades de Rede via GPO            | _Extra Prático_                                   |   ⏳   | [Ver Resumo](./modulos/22.md) |
| **23** | Hardening: Habilitando a Lixeira do Active Directory       | _Extra de Segurança_                              |   ⏳   | [Ver Resumo](./modulos/23.md) |
| **24** | Hardening: Políticas de Senha Granulares (PSO)             | _Extra de Segurança_                              |   ⏳   | [Ver Resumo](./modulos/24.md) |
| **25** | Auditoria de Eventos e Logs de Acesso (Event Viewer)       | _Extra de Segurança_                              |   ⏳   | [Ver Resumo](./modulos/25.md) |
| **26** | Backup e Restauração do Estado do Sistema (System State)   | Marco Andrade (06)                                |   ⏳   | [Ver Resumo](./modulos/26.md) |

<br/>
  Legenda de Status: <br/>
  ❌ Não Iniciado | ⏳ Em Andamento | ✅ Concluído
  
---

## 🛠️ Tecnologias Utilizadas

- **Sistemas Operacionais:** Windows Server 2025 / Windows Server 2016 / Windows 10 Pro
- **Virtualização:** Oracle VirtualBox / Hyper-V
- **Serviços de Infraestrutura:** AD DS, DNS, DHCP, GPO, FSRM, Print Server

---

## 🔗 Links das Playlists do Curso

Os estudos deste repositório foram baseados e estruturados a partir das seguintes playlists gratuitas no YouTube:

- **Descomplicando a TI** [Acessar Playlist no YouTube (Windows Server 2025 do Zero)](https://www.youtube.com/watch?v=wucb-HHeQH0&list=PLHp04fF85c-jnCf8mGriFyG19IlxzQsFP)
- **Marco Andrade** [Acessar Playlist no YouTube ( Curso Windows Server 2016)](https://www.youtube.com/watch?v=OrZO6bwR0ZA&list=PL9lSkGEyDvS-rgTtG8fOmDYSxp0VRAxLL)
