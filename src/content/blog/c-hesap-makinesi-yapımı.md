---
layout: ../../layouts/BlogPost.astro
title: C' HESAP MAKİNESİ YAPIMI
description: C' HESAP MAKİNESİ YAPIMI
publishDate: 2023-10-18T09:50:07.779Z
heroImage: https://www.hamitcandinc.com/wp-content/uploads/2020/03/c-programlama.png
---
**C﻿'de hesap makinesi** 

<!--StartFragment-->

\# include <stdio.h> int main() { char operator; double firstNumber,secondNumber; printf("bir işlem seçin (+, -, \*,): "); scanf("%c", &operator); printf("iki sayı girin: "); scanf("%lf %lf",&firstNumber, &secondNumber); switch(operator) { case '+': printf("%.1lf + %.1lf = %.1lf",firstNumber, secondNumber, firstNumber + secondNumber); break; case '-': printf("%.1lf - %.1lf = %.1lf",firstNumber, secondNumber, firstNumber - secondNumber); break; case '\*': printf("%.1lf \* %.1lf = %.1lf",firstNumber, secondNumber, firstNumber \* secondNumber); break; case '/': printf("%.1lf / %.1lf = %.1lf",firstNumber, secondNumber, firstNumber / secondNumber); break; // hiçbir operatör seçilmedi(+, -, *, /) default: printf("operatör doğru değil"); } return 0; }

<!--EndFragment-->

***i﻿nt main kullanmamın sebebi uygulamanın başka bir yerinde tekrardan fonksiyonu mu çağırabilmek içindi . Siz void mainde kullanabilirsiniz . Chardaki operatör tanımı sayesinde kullanıcın girdiği operatöre göre (+,-,/,*) tanımlayıp switch case ile sorgulattım if else ilede yapılabilir ama en kolay yöntem budur .***