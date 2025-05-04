## Hi, I'm Andrea 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Andrea%20Meneghello-blue?logo=linkedin&style=flat-square)](https://www.linkedin.com/in/andrea-meneghello-4a554b295)
[![Gmail](https://img.shields.io/badge/Gmail-Andrea%20Meneghello-red?logo=gmail&style=flat-square)](mailto:andreameneghello828@gmail.com)

<p><em>🎓 Graduated in Computer Science from the University of Padua <br> 💼 Software Engineer at <a href="https://www.thron.com/it/">THRON
</a><img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> 
</em></p>

### 🧑‍💻 Me, in Go
Ever wondered what a software engineer looks like in Go code? Let me show you.

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

### 🌱 I'm currently learning:  
  Backend development with Go, focusing on microservices architecture and serverless patterns.

### ✨ Fun facts:  
  🇮🇹 Based in Italy  
  🧠 Always curious and passionate about learning new technologies  
  📚 Currently diving deep into backend development with Go
