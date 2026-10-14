Organisation Paradigms

# Naming Paradigms & Definitions of Modules.

- Component
A constructed module that functions as one part in a larger module.

- Class
\nA constructed module that defines a new Object-Oriented Class.

- Manager
A constructed module that manages a wide variety of tasks in a given area. (e.g., AbilityManager)

- Handler
A central module that handles one specific aspect of the game. (e.g., SoundHandler, AnimationHandler, EnvironmentHandler, PhysicsHandler.)

# General Project Structure

- ServerScriptService
  - Components
		- Entity
			- HealthComponent.lua
			- PhysicalComponent.lua
			- InventoryComponent.lua
		- Props
			- MaterielComponent.lua
		- Weapon
			- ADS.lua
			- FireMode.lua
			- Magazine.lua
			- Melee.lua
	- Handlers
		- SoundHandler.lua
		- ClientHandler.lua
	- Managers
		- AbilityManager.lua
		- GameInventoryManager.lua
		- GlobalInventoryManager.lua
  - Objects
		- CharacterClass.lua
		- WeaponClass.lua
	- ServerMain.luau
