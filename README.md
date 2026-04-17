# CTT10 - Variáveis no GitHub Actions

## Respostas

**Por que a Secret aparece como ***?**  
Porque o GitHub mascara dados sensíveis por segurança.

**O Job 2 consegue ler BUILD_VERSION do Job 1?**  
Não. Cada job roda em um ambiente separado.
