# Welcome
Introduction
package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{
		"- ⚡ Bbio:":                    "Hi and welcome to my portfolio. Here you will find some basic information about me in addition to several data science oriented projects that I have worked on (both academic and personal projects). You can navigate this page as you would for any GitHub profile, and my projects can be found within the repository.",
		"- 🔭 I’m currently working on":      "Junior Data Analyst",
		"- 🌱 I’m currently learning":        "R and Python",
		"- 👯 I’m looking to collaborate on": "TBA",
		"- 🤔 I’m looking for help with":     "TBA",
		"- 💬 Ask me about":                  "TBA",
		"- 📫 How to reach me:":              "https://github.com/AnhellO#you-can-reach-me-at-alien",
	}
}
