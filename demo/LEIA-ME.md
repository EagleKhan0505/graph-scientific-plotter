# Demonstração no Graph · 17/11/2026

O CSV contém 301 pontos entre X = 0 e X = 10, com duas curvas construídas matematicamente. A primeira coluna é X; as demais são Curva_A e Curva_B. Não há medidas experimentais nem informações de terceiros.

## Execução observada

1. Importação do CSV pelo menu Arquivo → Importar Dados do Graph.
2. Uso da primeira curva, Curva_A, carregada como demonstracao_sintetica.
3. Abertura do assistente local pelo atalho Ctrl+I.
4. Envio do pedido: “Normalize a curva selecionada entre 0 e 1, suavize e marque os três picos principais pelo valor de X. Use o título ‘Demonstração com dados sintéticos’.”
5. Inspeção do resultado e dos recibos das operações.

## Resultado visível

- Normalização aplicada em um novo conjunto de dados.
- Suavização Savitzky–Golay aplicada ao conjunto derivado.
- Três picos anotados em X = 2,00; 5,20; 8,00.
- Título atualizado para “Demonstração com dados sintéticos”.
- Status do assistente: “Comando direto local — sem espera pelo Ollama”.

A normalização precedeu a suavização; portanto, o máximo final pode diferir de 1. O gráfico e os registros estão nas capturas em assets. Esta execução comprova o fluxo mostrado, não todos os recursos do aplicativo nem uma nova inferência do modelo.

## English

This CSV is a synthetic demonstration fixture with 301 points and two curves. The application imported Curva_A, then executed a Portuguese request to normalize, smooth and label the three main peaks. The resulting X labels were 2.00, 5.20 and 8.00. The interface reported direct local command execution without waiting for Ollama. Normalization occurred before smoothing, so the final maximum may differ from 1. No experimental research measurements are included.
