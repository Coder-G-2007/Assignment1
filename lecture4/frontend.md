transform: translate(-50%,-50%);
transform translate apne box ke height width ke hisab se kam karta hai

 transform: rotate(25deg); z axis me ghuma
 you can directly use rotate also
 transform: rotateY(70deg);
 transform: rotateX(70deg);

 transform: skew(70deg); stretch the corner of element and make it in parallelogram
 skewX,skewY distort element size

 body{
    perspective: 1000px;
}how the user see your website from which it is how far or how near to you

transform: scale(4); transform size of element by four times

position:absolute; is powerful property and it get independent not follow its parent
but when position relative is given to parent then it get absolute with respect to its parent

relative:have its core position but in absolute it get up from its position other element capture that position in absolute but not in relative

it is a selector:for selecting a box out of multiple
.box:nth-child(2n){
    height: 200px;
    width: 200px;
    background-color: crimson;
}e.g:3n,2n-1,1,2,3,4
from last to three
.box:nth-last-child(3){
    background-color: yellow;
}it have some error in css

position:fixed; if used that particular elenment not get move from it position on screen

position:sticky;
top:50%;
it get stick from top by 50% not move it is combination of relative and fixed


display: flex; it take all element alongrow
align-items: flex-start;work on y axis
justify-content:work along x-axis
align-items: flex-start;
justify-content: flex-end;
align-items: center;
justify-content: center;

align-item and justify-content:work with display flex

justify-content:space-between;
bich se space aa jayega corner element stick with body
space-around:form corner space is less and from other element it is more
like
wall<-|-><-|->wall
space-evenly:equal space from all side of the boxes

Y-axes:cross axis align-item
X-axes:main axis justify-content
you can change main axes and cross axes
 flex-direction: column; now align item and justify content work reversely now for cross and main
flex work best for one dimensional layout

gap: 20px; when display flex is used it apace between the element
Note:flex parent apen child ko address karta hai
flex used for making flexible layout

Downside of flex:
if no of child get incresed then the child get shrink to adjusted in that screen size

for fixing this:
flex-wrap:wrap;
flex-wrap:wrap-reverse;
flex-shrink: 0; jis child ko dege wo shrink nahi hoga

align-content:center;
overflow: auto;pevent shrinkage and adjust element accordingly

column-gap:20px;

froogy flex:webside to paly with flex box and learn it
