
# Calculadora UTI – Aplicativo PWA

Este aplicativo foi desenvolvido para auxiliar no cálculo de infusões contínuas em pacientes críticos, com base nas diluições padronizadas previamente instituídas por protocolo institucional da UTI 30 leitos HMVG.

## Funcionalidades

- 💉 Cálculo de velocidades (mL/h) com base em mcg/kg/min ou mcg/kg/h
- ⚖️ Conversor por peso com dose mínima e máxima
- 🧮 Calculadora reversa: digite mL/h e veja a dose equivalente
- 💾 Funciona offline (PWA)
- 📱 Compatível com dispositivos móveis
- 📘 Tabela de Diluições Padronizadas

## Instalação

1. Acesse o `index_abas_funcionais_fixas_topo.html` em um navegador moderno.
2. No celular, clique em “Adicionar à tela inicial” para instalar como app.
3. O ícone aparecerá como **Calculadora UTI** com funcionamento offline.

## Estrutura do pacote

- `index_abas_funcionais_fixas_topo.html`: interface principal
- `manifest.json`: definição PWA
- `icon-192.png`, `icon-512.png`: ícones para instalação
- `service-worker.js`: cache offline
- `README.md`: instruções e descrição

---

⚠️ **Advertência:** Estes cálculos estão com base nas diluições já instituídas anteriormente por protocolo institucional UTI 30 leitos HMVG. Verifique sempre as diretrizes locais e supervisão clínica.
