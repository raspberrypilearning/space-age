--- challenge ---
## Challenge: Age accuracy
In your project, the user enters their age in years. This isn't very accurate if it's been a while since your birthday.

Can you improve your project so that it asks you how old you are in months, years and days? Remember there are 365 days in a year and (on average) 30 days in a month.

Here are some code blocks that will help you:

```scratch
	set [age in days v] to [0]
	ask [How old are you in years?] and wait
	change [age in days v] by ( (answer) * (365) )
	ask [How many months since your last birthday?] and wait
	change [age in days v] by ( (answer) * (30) )
	set [age on Earth v] to ( (age in days) / (365) )
```



--- /challenge ---