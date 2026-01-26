<!-- PROFILE HEADER -->
<h1 align="center">Hello! 👋 I'm Gabriel Piassa</h1>
<p align="center">
  Software Engineer • Go lover • Linux daily user • Building scalable stuff 🚀
</p>

<p align="center">
  <a href="https://github.com/piassa157">
    <img src="https://img.shields.io/badge/GitHub-@piassa157-181717?style=for-the-badge&logo=github" />
  </a>
  <a href="https://www.linkedin.com/in/gabriel-g-piassa/">
    <img src="https://img.shields.io/badge/LinkedIn-gabrielpiassa-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://discord.gg/4NqhuhmQ">
    <img src="https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://img.icons8.com/clouds/64/000000/github.png"/>
</p>

---

## 👨‍💻 About me

- 🧠 **Role:** Software Engineer  
- 🌎 **Languages:** pt-BR, en-US  
- 🎯 **Goal:** Becoming a great developer to teach the world how a line of code can change your future  
- ⚡ **Focus:** Backend, data, automation, and cloud-native tools  

---

## 🧩 A bit of me in Go

```go
package me

import "fmt"

func main() {
    myName := "Gabriel Piassa"
    myRole := "Software Engineer"
    myLanguages := []string{"pt_BR", "en_US"}

    myDream("Becoming a great developer to teach the world how a line of code can change your future")

    fmt.Printf("Hello! Welcome to my profile 👋\n")
    fmt.Printf("Name: %s | Role: %s | Languages: %v\n", myName, myRole, myLanguages)
}

func myDream(message string) {
    fmt.Println("Dream:", message)
}
