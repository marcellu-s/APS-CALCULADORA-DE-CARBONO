# APS-CALCULADORA-DE-CARBONO

**Calculadora de Carbono: Uma Ferramenta para a Neutralidade Climática**

## 📋 Descrição

Aplicação desktop desenvolvida em Python com CustomTkinter para calcular emissões de CO² baseadas em consumo diário/mensal e fornecer sistema de compensação por créditos de carbono.

**Projeto APS - 2º Semestre - Ciência da Computação**

## 🚀 Como Executar

### Instalação
```bash
pip install -r requirements.txt
```

### Execução
```bash
cd src
python main.py
```

## 📊 Funcionalidades

### Cálculo de Emissões (7 Fatores)
- Eletricidade (kWh/Mês)
- Combustível/Gasolina (L/Dia)
- Viagens de Avião (KM/Mês)
- Transporte Público (KM/Dia)
- Gás Natural (m³/Mês)
- Água (m³/Mês)
- Resíduos (kg/Mês)

### Sistema de Compensação Interativo
- Créditos de Carbono Necessários
- Árvores para Plantar (estimativa)
- Valor de Compensação em R$
- **8 Ações Práticas de Compensação:**
  - Plantar Árvores (21.77 kg CO2/ano)
  - Andar de Bike (0.12 kg CO2/km)
  - Usar Transporte Público (0.08 kg CO2/km)
  - Reciclar Lixo (0.3 kg CO2/kg)
  - Energia Solar (0.038 kg CO2/kWh)
  - Reduzir Carne (46.62 kg CO2/mês)
  - Carona Solidária (0.15 kg CO2/km)
  - Compostagem (0.4 kg CO2/kg)

## 🛠️ Tecnologias

- Python 3.x
- CustomTkinter 5.2.2
- JSON (fatores de emissão)

## 📁 Estrutura

```
src/
├── main.py              # Entry point
├── view/index.py        # Interface gráfica
├── utils/index.py       # Lógica de cálculo
└── data/fatores.json    # Fatores de emissão
```

## 📖 Referências

- IPCC (Intergovernmental Panel on Climate Change)
- GHG Protocol Brasil
- Ministério do Meio Ambiente
