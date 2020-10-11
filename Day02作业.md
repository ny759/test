# Day02作业

## 作业01

### BMI.js

```
//BMI = mass / height^2 = mass / (height * height)

//1.变量存储Mark和John的体重以及身高；

let M_height = 1.85,M_Mass = 65;//声明变量：存储Mark的身高，体重

let J_height = 1.80,J_Mass = 70;//声明变量：存储John的身高，体重

//2.变量存储Mark和John的体重以及身高；

let M_BMI = M_Mass / (M_height * M_height);

let J_BMI = J_Mass / (J_height * J_height);

console.log("Mark的BIM值为:",M_BMI);

console.log("John的BIM值为:",J_BMI);

//3.创建一个布尔变量，用来包含Mark的BMI是否比John更高；

let compare;

compare = (M_BMI > J_BMI) ? true : false;

console.log(compare);

//4. 打印一个字符串到控制台，包含第三步的变量（比如"Mark的BMI是否比John更高？true"）

console.log("Mark的BIM是否比John的更高？",String(compare));
```

## 作业02

### Ball.js

```
//1. 计算每队的平均分；
let JohnAvg = (89 + 120 + 103) / 3;
let MikeAvg = (116 + 94 + 123) / 3;
let MaryAvg = (97 + 134 + 105) / 3;
console.log("John的平均分是："+JohnAvg+"\n" +"Mike的平均分是："+MikeAvg+"\n"+"Mary的平均分是："+MaryAvg+"\n")
//2.决定哪支球队平均获胜（平均分最高），并将胜者打印到控制台。在输出中也包括平均分；
if((JohnAvg > MikeAvg) && (JohnAvg > MaryAvg)){    
console.log("John是获胜队伍！" + "John的平均分是："+JohnAvg);
}
else if ((MikeAvg>JohnAvg) && (MikeAvg>MaryAvg)){   
 console.log("Mike是获胜队伍！" + "Mike的平均分是："+MikeAvg);
 }
 else if((MaryAvg>JohnAvg) && (MaryAvg>MikeAvg)){  
   console.log("Mary是获胜队伍！" + "Mary的平均分是："+MaryAvg);
   }
   else{   
    console.log("平局！");
    }

//3、 然后改变分数来显示不同的赢家。
let JohnAvg1 = (101 + 120 +87) / 3;
let MikeAvg1 = (126 + 99 +96) / 3;
let MaryAvg1 = (100 + 113 +105) / 3;
console.log("John的平均分是："+JohnAvg1+"\n" +"Mike的平均分是："+MikeAvg1+"\n"+"Mary的平均分是："+MaryAvg1+"\n")
if((JohnAvg1 > MikeAvg1) && (JohnAvg1 > MaryAvg1)){    
console.log("John是获胜队伍！" + "John的平均分是："+JohnAvg1);
}
else if ((MikeAvg1>JohnAvg1) && (MikeAvg1>MaryAvg1)){    
console.log("Mike是获胜队伍！" + "Mike的平均分是："+MikeAvg1);
}
else if((MaryAvg1>JohnAvg1) && (MaryAvg1>MikeAvg1)){    
console.log("Mary是获胜队伍！" + "Mary的平均分是："+MaryAvg1);
}
else{   
 console.log("平局！");
 }
```

## 作业03

### star.js

```
let all ="";
for(let i=1; i<=4; i++){    
    let blank = " ";    
    let stars = " ";   
    for(let m = 1; m <= 4-i; m++){
    blank = blank + " ";
     }
    for(let n=1; n<=i;n++){
     stars = stars + "*" + " ";
     }    
     all = all +blank + stars +"\n";
     }
     for(let i=4-1; i>0; i--){    
     let blank = " ";    
     let stars = " ";    
     for(let m=1; m<=4-i; m++){        
     blank += " ";    
     }    
     for(let n=1; n<=i; n++){        
     stars += "*" + " ";    
     }     
     all += blank + stars + "\n";}console.log(all);
```

