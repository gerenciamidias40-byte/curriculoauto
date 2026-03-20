# 🚀 Automação de Envio de Currículos

Este projeto é um Dashboard interativo que se liga ao **Google Sheets** para monitorizar o envio automatizado de currículos via Gmail e Drive.

## 📊 Funcionalidades
- Visualização de status dos envios em tempo real.
- Integração com Google Sheets API.
- Hospedagem gratuita via GitHub Pages.

## 🛠️ Configuração Local
Para que o dashboard funcione com os teus dados, precisas de configurar as seguintes constantes no ficheiro `index.html`:

1. **API_KEY**: Obtida no Google Cloud Console (Sheets API).
2. **SPREADSHEET_ID**: O ID da tua folha de cálculo do Google.
3. **SHEET_NAME**: O nome da aba (ex: 'Respostas').

```javascript
const SPREADSHEET_ID = 'TEU_ID_AQUI';
const API_KEY = 'TUA_CHAVE_AQUI';
const SHEET_NAME = 'Página1';
