## Get Smarter. Use templates

Why are you spending time on predictible fragments of code? Often happened to paste some code and replace few variables?

Now you can create a template and save it for later or share it with others. Make it simple and usefull!

Writting good templates makes you a better developer. Great minds develops simple solutions.

### Download for free

We can make a better world by sharing. I am happy to include your templates in this library. I can help you write your first templates. Using templates is addictive, like speacking a foreign language. You can't leave without templates! 

# Write your own templates

Here is a simple template. You can paste this template [here](https://profimedica.github.io/Templater/Advanced/index.html).

```
================= Vars begin
{
	"Greetings" : 
	[
    { "word" : "World" },
    { "word" : "There" },
    { "word" : "Kitty" }
	]
}
================= Vars end
		
!=========== Greetings ===========
Hello @{word}@!
===========!
```

For each word in Greetings a new line will be generate resulting in:

+Hello World!

+Hello There!

+Hello Kitty!
