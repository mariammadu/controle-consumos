# 🏭 Controle de Consumo PCP & Gestão de Corte / Perdas

Sistema web responsivo projetado para controle de produção, cálculo automático de consumo e apontamento de perdas de matéria-prima (PVC) em linhas industriais de confecção.

---

## 🛠️ Tecnologias Utilizadas

- **Front-end:** HTML5, JavaScript (ES6+), Tailwind CSS (via CDN)
- **Backend & Database:** Supabase (PostgreSQL + Autenticação e APIs REST)
- **Manipulação de Dados / Exportação:** SheetJS (XLSX) para relatórios gerenciais offline
- **Integração de Áudio:** Web MediaRecorder API & Web Speech API

---

## 🚀 Funcionalidades Principais

1. **Módulo Tablet (Apontamento de Perdas):**
   - Seleção dinâmica por categoria (Jaquetas, Calças, etc.), tamanhos (PP ao 5G / Único) e cores.
   - Botão rápido de atalho para motivos frequentes de refugo.
   - Cálculo automático de metros perdidos com base nos dados cadastrados na Ficha Técnica.

2. **Módulo Mesa de Corte:**
   - Lançamento de ordens de corte (comprimento de folha, número de camadas e grade de peças).
   - Apontamento e estimativa de perdas de enfesto.
   - Comparativo automático: **Consumo Real Unitário vs. Consumo Projetado FT**.
   - Opção de entrada de dados por voz via IA.

3. **Dashboard Gerencial & Métricas KPIs:**
   - Visualização em tempo real do total de peças cortadas, consumo médio e diferença acumulada em metros.
   - Tabela analítica com filtros avançados de modelos e intervalo de datas.
   - Exportação completa de relatórios consolidados em `.xlsx`.

4. **Painel Administrativo:**
   - Gestão de Fichas Técnicas (consumos por tamanho de cada modelo).
   - Gerenciamento de acessos e permissões por perfil de usuário (*Operador de PVC, Mesa de Corte, Gerência, Admin*).

---

## 📌 Licença

Este projeto é disponibilizado para fins de demonstração de portfólio.
