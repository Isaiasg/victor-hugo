---
date: 2017-09-24
draft: false
title: Hey there
---
# Testing Hugo and Netlify

Installed blackburn theme throught git submodules.  
Added custom 404.  
For code highlighting:    
- Added requirements.txt to install pygments.  
- Added runtime.txt to control Python version.  

<!--more-->
{{< highlight go >}}
package main
import "fmt"

func main() {
    fmt.Println("hello world")
}
{{< / highlight >}}

{{< highlight csharp >}}
using System;

namespace HelloWorld
{
    class Hello 
    {
        static void Main() 
        {
            Console.WriteLine("Hello World!");

            // Keep the console window open in debug mode.
            Console.WriteLine("Press any key to exit.");
            Console.ReadKey();
        }
    }
}
{{< / highlight >}}