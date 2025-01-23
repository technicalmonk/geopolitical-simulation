# Geopolitical Simulation System

A modular system for simulating complex geopolitical scenarios through the combination of regional conditions, situational modifiers, and infrastructure states. This system enables the creation of rich, multi-layered simulations for analyzing and understanding complex socio-political dynamics.

This is an LLM-based simulation system. While the generated results are promising - we acknowledge the current state of LLM technology is not as it's peak technological potential - as LLM technology improves - so too shall it's ability to leverage this simulation project.

Remember, unless you have full access to the training data of the underlying LLM system - please do not take these results as facts. Every system is biased - only those with complete access to the system know the truth of the results. Please use responsibly.

## 🌟 Features

- **Modular Lorebook System**: Combine different regional, situational, and infrastructure modifiers
- **Rich Contextual Layers**: Detailed environmental, social, and behavioral parameters
- **Flexible Scenario Creation**: Stack and combine different modifiers for complex situations
- **Comprehensive Parameter Sets**: Each lorebook contains detailed specifications for:
  - Environmental Parameters
  - Social Dynamics
  - Communication Modifiers
  - Risk Factors
  - Resource Availability
  - Cultural Contexts
  - Behavioral Modifiers

## 📁 Project Structure

```
geopolitical-simulation/
├── lorebooks/
│   ├── regional/         # Geographic and regional modifiers
│   ├── situational/      # Event and circumstance modifiers
│   ├── infrastructure/   # Infrastructure and system modifiers
│   └── README.md         # Lorebook system documentation
├── examples/             # Example scenarios and combinations
│   ├── refugee_crisis_response.md
│   ├── disputed_territory_unrest.md
│   └── sanctions_economic_adaptation.md
└── personas/             # Character and actor definitions
```

## 🔧 Components

### Regional Lorebooks
- Technology Hubs
- Special Economic Zones
- Refugee Settlements
- Cultural Heritage Sites
- Agricultural Heartlands
- Trade Route Nexus
- Disputed Territories
- And more...

### Situational Lorebooks
- Cyber Warfare
- Information Warfare
- Climate Change Impact
- Cultural Revolution
- Economic Sanctions
- Demographic Shift
- Resource Depletion
- Civil Disobedience
- And more...

### Infrastructure Lorebooks
- Smart City Systems
- Digital Payment Systems
- Underground Infrastructure
- Alternative Currency Networks
- Renewable Energy Transition
- Data Center Hubs
- Emergency Response Systems
- Critical Resource Storage
- And more...

## 📖 Usage

1. **Select Base Region**
   - Choose a regional lorebook that defines the geographic and cultural foundation
   - Example: `refugee_settlement.md`

2. **Add Situational Modifiers**
   - Layer situational lorebooks to represent current events or circumstances
   - Example: `climate_change_impact.md`

3. **Include Infrastructure States**
   - Add infrastructure lorebooks to define available systems and services
   - Example: `emergency_response_systems.md`

4. **Apply to Personas**
   - Combine with character personas to simulate specific actor behaviors
   - Example: `resilient_community_leader.md`

## 🛠️ System Prompt

The System Prompt is essential for directing the Language Model (LLM) within the simulation environment. It establishes the context and sets the parameters for the LLM's operations, ensuring that the outputs generated are consistent with the desired objectives. Below is a generated example of a System Prompt for this simulation:

### System Prompt
- **Context**: Define the overarching scenario and environment.
- **Parameters**: Specify the key variables and constraints.
- **Objectives**: Outline the goals and expected outcomes.
- **Instructions**: Provide clear guidelines for the LLM's behavior and interactions.


## 🎯 Example Scenarios

### Refugee Crisis Response
```markdown
Required Files:
- /lorebooks/regional/refugee_settlement.md
- /lorebooks/infrastructure/emergency_response_systems.md
- /personas/resilient_community_leader.md
```

### Disputed Territory Unrest
```markdown
Required Files:
- /lorebooks/regional/disputed_territories.md
- /lorebooks/situational/civil_disobedience.md
- /personas/religious-community-leader.md
```

### Economic Sanctions Adaptation
```markdown
Required Files:
- /lorebooks/situational/economic_sanctions.md
- /lorebooks/infrastructure/alternative_currency_networks.md
- /personas/local-market-vendor.md
```

## 🤝 Contributing

Contributions are welcome! You can help by:
- Adding new regional, situational, or infrastructure lorebooks
- Creating new example scenarios
- Developing additional personas
- Improving existing documentation
- Suggesting new combinations and use cases

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.