# 🛰️ Monitoramento de Áreas Queimadas e Risco de Fogo (v2.0)

Este plugin para QGIS foi desenvolvido para automatizar o processamento de índices de severidade de queimadas (dNBR) e análise de risco meteorológico de fogo baseados em dados do INPE e Sentinel-2.

## 🚀 Funcionalidades
* **Cálculo de dNBR:** Processamento automatizado de bandas do Sentinel-2 para detecção de cicatrizes de fogo.
* **Limiar Dinâmico:** Ajuste fino de severidade para diferentes biomas.

## 🛠️ Requisitos
* QGIS 3.22 ou superior.
* Bibliotecas Python: `processing`, `numpy` (nativa do QGIS).

## 📥 Instalação (Via Nuvem)
1.  Abra o QGIS.
2.  Vá em **Complementos > Gerenciar e Instalar Complementos**.
3.  Em **Configurações**, clique em **Adicionar** um novo repositório.
4.  Insira a URL do repositório (após configurar o passo 2 abaixo).

## 📖 Como Usar
1.  **Processamento dNBR:** Selecione as bandas pré e pós fogo e defina o limiar.
2.  **Relatório de Risco:** Carregue o arquivo `.nc` do INPE e a camada de municípios. O plugin gerará uma lista de alertas no console ou layout.

---
Desenvolvido por **Leandro Luiz da Paixão**
