# Área do Polígono – campo

App web offline para calcular **área e perímetro** de polígonos a partir de pontos coletados com GNSS (coordenadas UTM / SIRGAS 2000), direto na coletora ou no celular Android.

- Lê o TXT/CSV exportado da SingularPad (nome, E, σE, N, σN, h, σh) e arquivos com cabeçalho; converte lat/long para UTM.
- Escolha e ordem dos vértices, aviso de lados cruzados, distâncias e azimutes.
- **Ajuste para área desejada**: deslocamento paralelo de um lado ou giro com vértice fixo, com coordenadas dos pontos a implantar.
- Funciona sem internet depois de instalado (PWA).

## Instalar
1. Abra o endereço do GitHub Pages no Chrome, com internet, uma vez.
2. Toque em **Instalar** (ou menu ⋮ → Instalar app).
3. Use offline pelo ícone na tela inicial.

## Atualizar
Troque os arquivos e mude `CACHE` em `sw.js` (ex.: `v2`).
