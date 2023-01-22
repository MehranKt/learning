selection ustune basib saxliyib mouse ni terpende o renge alsin
placae holder shown basmazdan qabagki halidir 
chekced qus qoyanda dizayn vermeycindi
class:invalid verdiyimiz sertlere uygun gelmirse bu dizayni al
developer mozilla advance seviyyede oyredir
background-origin: border box sekil borderi nezere almir icinden basliyir xetdin
transition -> delay duration (hovere istediyi ver) coxdu w3 de bax
cubic bezier
display none den inline ve ya blocka kecirende transition vermek olmur
transiton width verende ancaq width deyisende isdiyir verdylerimz
transition: width 2s linear 1s.
animation
animation-name:coders
animation-duration:2s;
@keyframes coders{
    from {
        opacity:0;
    }
    to {
        to: 1;
    }
}
saniyeni fazilernende bolmek olur{
    0% { background-color: red}
    25% { background-color: yellow}
    50% { background-color: green}
    000% { background-color: blue}
}
animation-iteration-count:3; 3 defe tekrarla,(infinite)sonsuz tekrar
animation-direction: reverse; tersine basdiyir hereketi
animation-direction: alternate; firranir gedir yolunu tezden qayidir (count mutleq en az 2 olmaludurju goresen)
animation-fill-mode: forwards; animasiya tamamlananda son veziyyetinde qalir, yeni to da qalir. backwards from da qalir

before after (google tanimir, inspectde html kimi dusmur)
div::before{
    content: "bla bla bla"  ( :) bele simvollarda elave ede bilersen kontentde)
} (butun divlerin onune ne istrsen yazib yada sekil qoya bilersen bir bir hamisina yazmag mecburiyetinde qalmirsan html de)
evveline soz yazmagcun afterde sorasina soz yazmagcin

bordere current color versey icindeki yazi coloru nedise onu goturub tetbiq edecek
@import url('')css de yazanda basqa css deki dizaynlari daxil ede bilirsen
