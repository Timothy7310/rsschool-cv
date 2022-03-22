# Timothy Popovskiy

## Junior Frontend Developer

## Contacts:
* __Location__: Krasnodar, Russia
* __Telegram__: [@zipker](https://t.me/zipker)
* __WhatsApp__: [Contact Me](https://wa.me/79528304444)
* __Email__: penlist127@gmail.com

## About Me
Senior year student and Junior Frontend Developer, interested in web-performance and a11y issues. You can see my last projects on my [site](https://tpopovsky.ru/).

## Skills
* HTML and CSS
* CSS preprocessors
* JavaScript (Basic)
* Vue 3 (Basic)
* Figma
* Git

## Code Example
Second task of SberFight 2022
```
function getResult(nums, targets) {
  let sum;
  let counter = 0;

  let copyNums = [...nums];
  let copyTargets = [...targets];

  for(let n = 0; n < copyNums.length; n++){

    for(let i = 0; i < copyNums.length; i++){

      for(let z = 0; z < copyTargets.length; z++){
        sum = copyNums[n] + copyNums[i];
        if(n !== i && sum === copyTargets[z]){
          counter++;
          copyNums.push(sum);
          copyTargets.splice(z, 1);
        }
      }
      
    }

  }
  console.log(counter);
}
```

## Education
__Kuban State University__:
* Bachelor: Physicist.
* Master's degree: Information systems and technologies.

__Udemy__:
* [JavaScript](https://www.udemy.com/course/javascript_full/)
* [Vue](https://www.udemy.com/course/vue-and-vuex-writing-real-project-from-scratch/)