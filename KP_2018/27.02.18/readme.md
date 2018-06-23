<h1>Задание</h1>
<p>
  <ul>
    <li>Создайте	веб-страницу	(борд)	на	Кодактор.ру	или	ином	онлайн-редакторе</li>
<li>Вставьте	элемент	script и	определение	функции</li>
    
function makeCanvas(x, y) {
 const canvas = document.createElement('canvas'),
 ctx = canvas.getContext('2d');
 canvas.setAttribute('width', x);
 canvas.setAttribute('height', y);
 return { canvas, ctx };
}

<li>Вызовите	функцию для	создания	переменных,	содержащих	холст	и	контекст
const { canvas, ctx } = makeCanvas(300, 120);</li>
<li>Добавьте	холст	в	дерево	DOM
document.body.appendChild(canvas);</li>
<li>Используя	методы	контекста,	изобразите	свои	инициалы,	использовав	в	качестве	
образца написание	в	стиле	почтового	индекса:</li>
<li>Используя	кривую	Безье,	нарисуйте	под	инициалами	 дугу	другого	цвета:</li>
<li>Используя	аффинные	преобразования (https://kodaktor.ru/affine ),	осуществите	поворот	
этого	изображения	на	90	градусов	против	часовой	стрелки.</li>
    
    </ul>
  
  </p>
