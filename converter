package main

import (
	"fmt"
	"github.com/pdfcrowd/pdfcrowd-go"
)


func main(){

	Ic := pdfcrowd.NewHtmlToImageClient("YourUsername", "Your api")
    
	
    err := Ic.ConvertFileToFile("nameofyourimage.jpg", "nameofyourpdf.pdf")
	if err != nil{
		fmt.Println(err)
	}

	
}