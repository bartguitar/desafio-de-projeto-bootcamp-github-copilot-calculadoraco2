# 🌿 Calculadora de Emissão de CO₂

Aplicação web que calcula a emissão de CO₂ de uma viagem com base na distância e no meio de transporte utilizado.  
O projeto também compara diferentes transportes e estima a quantidade de créditos de carbono necessários para compensar a emissão.

🔗 **Acesse a aplicação online:**  
https://bartguitar.github.io/desafio-de-projeto-bootcamp-github-copilot-calculadoraco2/

---

## 📌 Funcionalidades

- Cálculo de emissão de CO₂ baseado na distância da viagem
- Comparação entre diferentes meios de transporte
- Cálculo de economia de CO₂ em relação ao uso de carro
- Estimativa de créditos de carbono necessários para compensação
- Estimativa de custo de créditos de carbono
- Sugestão automática de distância entre cidades
- Opção de inserir distância manualmente

---

## 🚗 Meios de transporte suportados

- 🚲 Bicicleta
- 🚗 Carro
- 🚌 Ônibus
- 🚚 Caminhão

Cada transporte possui um **fator de emissão de CO₂ por km**, utilizado para o cálculo da pegada de carbono.

---

## ⚙️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- GitHub Pages
- GitHub Actions

---

## 🧠 Lógica da aplicação

A aplicação utiliza fatores de emissão para calcular o impacto ambiental da viagem.

Exemplo simplificado:

Emissão = Distância (km) × Fator de emissão do transporte


Exemplo de fatores:

| Transporte | Emissão CO₂ |
|-------------|-------------|
| Bicicleta | 0 kg/km |
| Carro | 0.12 kg/km |
| Ônibus | 0.089 kg/km |
| Caminhão | 0.96 kg/km |

Também é calculado:

- Comparação entre transportes
- Economia de CO₂
- Créditos de carbono necessários para compensação

---

## 📂 Estrutura do projeto

```
project/
├── index.html
├── css/
│   └── style.css
├── js/
│   ├── app.js
│   ├── calculator.js
│   ├── config.js
│   ├── routes-data.js
│   └── ui.js
└── .github/
    └── workflows/
        └── deploy.yml
```

# 🎓 Projeto educacional

### Projeto desenvolvido como desafio prático do Bootcamp GitHub Copilot da DIO, com foco em:

- lógica em JavaScript

- organização modular do código

- Manipulação de DOM

- Cálculos ambientais

