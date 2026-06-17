# LACEN-AL BioMol Calc — Versão 1.0

Laboratório: LACEN-AL  
Desenvolvedor: Jean Nascimento  
Versão: 1.0  

## O que é
Aplicativo web instalável (PWA) para cálculos de rotina em Biologia Molecular, PCR convencional e qPCR.

## Módulos incluídos
- Diluição C1V1
- Montagem de PCR/qPCR
- Mix primer-sonda concentrado
- Reconstituição de oligonucleotídeos
- Número de cópias por µL
- Curva padrão de qPCR
- Diluição seriada
- Cálculo de temperatura de anelamento
- Histórico local de cálculos

## Exportação
- PDF: o aplicativo abre uma versão imprimível do relatório. No Android/iOS, escolha salvar/compartilhar como PDF quando disponível.
- Excel: exporta arquivo .xls compatível com Excel/LibreOffice/Google Sheets.

## Campo “Módulo informado pelo usuário”
O campo aparece no cabeçalho dos relatórios como:
Cálculos para Reações de PCR de {módulo informado}

## Instalação como PWA
Para instalação em Android e iOS, hospede esta pasta em um servidor HTTPS.

Exemplos:
- GitHub Pages
- Netlify
- Vercel
- servidor institucional HTTPS do laboratório

Android:
1. Abrir o endereço no Chrome.
2. Menu ⋮ > Instalar app ou Adicionar à tela inicial.

iOS:
1. Abrir o endereço no Safari.
2. Compartilhar > Adicionar à Tela de Início.

Observação: navegadores móveis geralmente não permitem instalar PWA corretamente a partir de arquivo local file://. Use HTTPS.
