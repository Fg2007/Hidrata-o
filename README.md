Controle de Hidratação Diária
## Descrição do Projeto
O **Hidratation** é um aplicativo Android desenvolvido para ajudar usuários a
manterem hábitos saudáveis de hidratação. Com base no peso corporal e nível
de atividade física, o app calcula a meta ideal de ingestão de água e
monitora quanto ainda falta para atingir o objetivo do dia.
---
## Interface do Aplicativo

<img width="260" height="536" alt="Captura de tela 2026-05-18 215651" src="https://github.com/user-attachments/assets/fda4b86b-b166-4628-8043-8e15c29fdaf2" />

---
## Regras de Negócio
1. **Consumo Base:** 35ml de água para cada kg de peso corporal.
2. **Adicional por Atividade:**
- Sedentário: +0ml
- Moderado: +300ml
- Intenso: +600ml
3. **Cálculo de Progresso:** Subtração da ingestão atual em relação à meta
calculada.
---
## Tecnologias
- **Linguagem:** Java / Kotlin
- **Interface:** XML (Material Design)
- **Ferramenta:** Android Studio
---
## Funcionalidades
- [x] Cálculo personalizado por peso.
- [x] Ajuste por nível de atividade física.
- [x] Contador de ingestão restante.
- [x] Validação de campos numéricos.
