<div align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00ADD8,100:0d1117&height=200&section=header&text=Hey,%20I'm%20Salim%20👾&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Backend%20Developer%20·%20Go%20·%20Building%20things%20that%20work&descAlignY=58&descSize=16" /></div><div align="center">
</div>

About me
package main

type Developer struct {
	Name   string
	Role   string
	Stack  []string
	Focus  string
	Status string
}

func main() {
	me := Developer{
		Name:   "Salim Bersirov",
		Role:   "Backend Developer",
		Stack:  []string{"Go", "PostgreSQL", "Docker", "HTTP", "REST API"},
		Focus:  "Clean architecture & reliable systems",
		Status: "Open to backend internships 🚀",
	}
	_ = me
}


