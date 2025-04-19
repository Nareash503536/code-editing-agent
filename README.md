# Conversational AI Agent with Memory using Go and Anthropic API

Built a conversation agent with memory using the **Go programming language**.  
The agent uses the **Anthropic API** (Claude models) for natural language interaction.

> ⚠️ The program execution requires a **paid tier** on Anthropic.  
> Free-tier or trial accounts may receive errors like `credit balance too low`.

---

## 🔐 Set Your API Key

Before running the program, set your API key as an environment variable:

```bash
export ANTHROPIC_API_KEY="<create an anthropic api key and use here>"
```

## ⚙️ Install and run
```bash
# Download dependencies
go mod tidy

# Run the program
go run main.go
```

## 💬 Example Output
```bash
$ go run main.go

Chat with Claude (use 'ctrl-c' to quit)

You: Hello! Can you help me come up with a team name for a robotics competition?
Claude: Of course! Here are some fun and creative team name ideas for a robotics competition:

* RoboRangers
* Circuit Breakers
* ByteForce
* The Gearheads
* CodeBotics
* Neural Ninjas
* Mech Masters
* Autonomous Avengers
* Iron Algorithms
* Botzilla Squad

Let me know if you want names with a specific theme or pun!

You: Could you suggest names based on space and technology themes?
Claude: Absolutely! Here are some space-and-tech-themed team names:

* AstroMechs
* Quantum Launch
* Stellar Circuits
* Nebula Navigators
* Mechtronauts
* Galaxy Bots
* Orbitronix
* Solar Sync
* CyberCosmos
* RocketBytes

Hope one of these sparks an idea!

```

