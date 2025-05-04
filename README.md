## Hello there 👋

```golang
package main

import "fmt"

type SoftwareEngineer struct {
	Name           string
	Role           string
	LanguageSpoken []string
	Code           []string
	Technologies   map[string]interface{}
	Architecture   []string
	AWS            []string
	Tools          []string
}

func (se *SoftwareEngineer) SayHi() {
	fmt.Println("Thanks for dropping by! I'm currently focused on backend development with Go.")
}

func main() {
	me := &SoftwareEngineer{
		Name:           "Andrea Meneghello",
		Role:           "Backend Software Engineer",
		LanguageSpoken: []string{"it", "en"},
		Code:           []string{"Go", "TypeScript", "Javascript"},
		Technologies: map[string]interface{}{
			"backEnd": map[string]string{
				"go": "Gin",
				"js": "Nest.js, Express",
			},
			"frontEnd": map[string]string{
				"js":  "Vue.js, Nuxt.js",
				"css": "Sass, Tailwind",
			},
			"databases": "DynamoDB, MongoDB",
		},
		Architecture: []string{"Microservices", "Serverless", "Micro-frontends"},
		AWS: []string{
			"Lambda", "DynamoDB", "EventBridge", "Cloudwatch",
			"Step Functions", "ECS", "S3",
		},
		Tools: []string{"Git", "Docker"},
	}

	me.SayHi()
}
```
