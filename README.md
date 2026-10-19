# Eduardo Henrique Moretti

**Dev + Segurança — full-stack de infraestrutura.** Construo software seguro self-hosted e endureço sistemas Windows, Linux e macOS.

Técnico de campo de TI e desenvolvedor (CCR Telecom) — Jundiaí/SP, Brasil.

Meu diferencial não é só entregar código: é entregar com segurança e ética embutidas desde o design, com prova — testes, VM real e decisões de engenharia documentadas.

---

## 🚀 Projetos em destaque

### [fm-rmm](https://github.com/eduardohenriquemoretti0-ops/fm-rmm)
RMM + acesso remoto autorizado **self-hosted** para parques Windows/Linux/macOS, projetado para resistir a um servidor comprometido.

![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)

- **mTLS por agente** com CA própria revogável e certificate pinning.
- **Jobs e sessões assinados em Ed25519** por uma chave de administrador guardada **fora do servidor** — servidor invadido não fabrica comando.
- Inscrição por **token de uso único + aprovação manual**; **catálogo de ações fechado** (nada de "rode qualquer comando").
- **Auditoria append-only encadeada por hash** (adulterar quebra a cadeia), anti-replay persistente, RBAC por técnico/grupo.
- **Indicador de sessão sempre visível** (fail-closed). Integra RustDesk self-hosted endurecido no Windows.
- Testado em **VM real**, build nos 3 sistemas, `go test -race`.

### [escriba](https://github.com/eduardohenriquemoretti0-ops/escriba)
Transcrição de reuniões com **diarização** (separação de falantes) e geração de ata.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)

- Motor **local e offline** (Faster-Whisper), grátis por padrão. CLI + API FastAPI.
- Segurança embutida: rate limit antes do auth, anti-SSRF no `ffprobe`, escrita atômica.

### [scripts-seguranca](https://github.com/eduardohenriquemoretti0-ops/scripts-seguranca)
Endurecimento de **Windows** (golden image para ~100 máquinas) e **Ubuntu** (SSH, Postfix, SUID, serviços).

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white)

- Scanner de postura de segurança com saída em JSON.

### [convert2md](https://github.com/eduardohenriquemoretti0-ops/convert2md)
Conversor de documentos para Markdown: versão **web** (Flask) e app **Android** (Kivy/APK).

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)

---

## 🛠️ O que eu faço bem

- **Linguagens:** Go, Python, PowerShell, Bash
- **Back-end / Apps:** FastAPI, Flask, Kivy, SQLite
- **Segurança:** mTLS/PKI, Ed25519, hardening Linux e Windows, consciência de LGPD
- **Infra & redes:** Cisco, Aruba, SonicWall; administração e endurecimento de servidores

---

## 📫 Contato

- **E-mail:** fratelli.morettiinformatica@gmail.com

