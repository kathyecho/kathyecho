### Hi there 👋

<!--
**kathyecho/kathyecho** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
int a;
void setup(){
size(600,600);
background(a,a/2,a/3);
}
void draw(){
  fill(a,a/2,a/3,10);
  rect(0,0,width,height);
float c=5;
stroke(255-a,255-a/2,255-a/3);
line(a,0,0,a);
line(width-a,0,600,a);
line(0,height-a,a,600);
line(600,height-a,width-a,600);
line(a,0,a,600);
line(0,a,600,a);
line(0,width-a,600,width-a);
line(height-a,600,height-a,0);
a+=c;
if(a>width){
  a=0;
  a+=c;
}
saveFrame();
}
