- 👋 Hi, I’m @Cargo1214
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Cargo1214/Cargo1214 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
speed(3)

bgcolor("tan")
penup()
setposition(-100,40)
color("red")
pendown()
begin_fill()
circle(60,360,4)
end_fill()
penup()
goto(-100,0)
write("Red Square",font=("Arial", 20), align= "center")


setposition(-100,-160)
color("yellow")
pendown()
begin_fill()
circle(60,180)
end_fill()
penup()
left(180)
goto(-100,-180)
write("Yellow Semicircle",font=("Arial", 20), align= "center")


setposition(100,40)
color("blue")
pendown()
begin_fill()
circle(60)
end_fill()
penup()
goto(100,0)
write("Blue Circle",font=("Arial", 20), align= "center")


setposition(100,-150)
color("green")
pendown()
begin_fill()
circle(60,360,5)
end_fill()
penup()
goto(100,-180)
write("Green Pentagon",font=("Arial", 20), align= "center")
