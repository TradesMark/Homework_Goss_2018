<h1>Задание</h1>

<p>https://kodaktor.ru/super-class-15-02-2018.pdf   </p>

<h3> ИТОГ РАБОТЫ </h3>
  <p>
  <i>
  class Father {  <br>
    constructor(name = 'Darth') {   <br>
        this.name = name.toUpperCase();   <br>
    }   <br>
    get myName(){   <br>
        return this.name;  <br>
    }   <br>
}   <br>
const father1 = new Father();  <br>
console.log(father1.myName);   <br><br>

class Son extends Father{   <br>
    constructor(name){   <br> 
        super();    <br>
        const f = super.myName;    <br>
        this.name = `${name} ${f}'s son`;     <br>
    }   <br>
}    <br>
const son1 = new Son('Luke'); //darth      <br>
console.log(son1.myName); //luke darth`s son        <br>
   </i> 
  </p>
