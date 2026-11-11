# Network Checker 🌐

Ferramenta de automação desenvolvida em **Python** para diagnóstico rápido de conectividade de rede, verificação de status de hosts/gateways e registo automático de logs em tempo real.

---

## 🚀 Funcionalidades
- **Compatibilidade Multiplataforma**: Adapta automaticamente os parâmetros de ping dependendo do sistema operativo (Windows/Linux).
- **Tratamento de Exceções**: Gestão de *Timeouts* e erros de codificação de caracteres no terminal.
- **Registo de Logs (Audit Trail)**: Regista o histórico completo das verificações com data e hora num ficheiro `.txt` local (`network_log.txt`).

---

## 🛠️ Tecnologias Utilizadas
- **Python 3.x**
- Módulos nativos: `subprocess`, `platform`, `datetime`

---

## 💻 Como Executar

1. Certifica-te de que tens o Python instalado no teu sistema.
2. Descarrega o ficheiro `testing network.py`.
3. Executa o script através do terminal:

```bash
python "testing network.py"
