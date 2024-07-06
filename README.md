# Shadow Division Developer Team - Arma Reforger Tools

## Naming Conventions

### General Naming Convention
- Use a first letter uppercase followed by all lowercase naming schema: `Test_development`
- Use underscores to separate words: `Name_test`
- Be explicit with your naming yet concise

## Testing Procedures
- **Local Testing:** Test changes locally on your development environment.
- **Team Testing:** Share changes with the team for collaborative testing.
- **Test Server:** Deploy changes to the test server for broader testing.
- **Dedicated Server:** Finally, deploy changes to the dedicated server for production use.

## World Editor Guidelines
When working in the world editor, follow these guidelines to ensure consistency and organization:

> **Recommendation:** Perform initial testing in the `Arland.et` world as it's smaller and loads faster.

### (World) Arland_dev
- **Layer: AI_behavior**
  - Description: Contains AI behavior scripts and configurations.
  - Example Prefabs: `SCR_AIWorld`, `PerceptionManager`
  
- **Layer: Arsenals**
  - Description: Includes arsenal setups and equipment configurations.
  - Example Prefabs: `ArsenalBox_USMC.et`

- **Layer: Factions**
  - Description: Manages faction settings and affiliations.
  - Example: `SCR_FactionManager`

- **Layer: Game_logic**
  - Description: Houses game logic scripts and modes.
  - Example: `SCR_GameMode_Editor`

- **Layer: Loadouts**
  - Description: Defines loadout configurations for units.
  - Example: `SCR_LoadoutManager`

- **Layer: Spawns**
  - Description: Specifies spawn points for players or AI units.
  - Example: `SCR_SpawnPoint`

### Zen of Python Integration

Remember to abide by the principles of the Zen of Python:
- **Explicit is better than implicit**: Clearly define the purpose and content of each layer and naming convention.
- **Readability counts**: Use clear, understandable names that reflect their purpose.
- **In the face of ambiguity, refuse the temptation to guess**: Ensure naming reflects exactly what the layer or element contains.
- **Namespaces are one honking great idea**: Use namespaces (like prefixes in naming conventions) to avoid name collisions and to organize elements logically.

### Example Usage
- When creating a new AI behavior layer, name it in the format `AI_behavior_DescriptiveName`.
- Use underscores (`_`) to separate words in names for consistency and readability.

By adhering to these conventions and principles, we maintain consistency across our projects and facilitate better collaboration and understanding.

## Contributing

We welcome contributions! If you have training materials, scenarios, or other resources to share, please fork the repository and submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

## License

This repository is licensed under the [CREATIVE COMMONS ATTRIBUTION-NON-COMMERCIAL-NODERIVS (CC BY-NC-ND)] license - see the below for brief explanation. 

*When incorporating any content from this source, kindly ensure proper attribution by including the following citations at the beginning of the materials:*
1. Please reference our current github: https://github.com/beardedeldo/shadow_dev
2. Shadow Division Milsim: https://discord.gg/neXcdGx7

<details>
  <summary><strong>CC BY-NC-ND</strong></summary>

Creative Commons Attribution-NonCommercial-NoDerivs (CC BY-NC-ND):
Users are free to:
Share — copy and redistribute the material in any medium or format for non-commercial purposes.
Under the following terms:
Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
NonCommercial — You may not use the material for commercial purposes.
NoDerivatives — If you remix, transform, or build upon the material, you may not distribute the modified material.

------
</details>











