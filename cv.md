## Simon Antakov

### Contacts
__Location:__ Kirov, Russia\
__Phone:__ +7-953-674-01-93\
__Email:__ fortrancefor@gmail.com\
__GitHub__ [Simon Smirnov](https://github.com/Simon-Smirnov)

### About me
Briefly. I try to constantly learn something new. With this desire, I came to this project. Thanks more to this team that they provide an opportunity to learn, to make the lives of individuals and society as a whole better. 

At the moment I am working as a layout designer in a small web studio in Kirov. I love my job and consider it not a job anymore, but a hobby.

The short term goal is to become a fronted development specialist. Medium-term goal - Full Stack. There is no specific long-term goal, because I don’t know where the desire to learn new things can bring in the end. But my goal as a whole is to develop in the IT industry.

I don't smoke or drink. Spend most of your free time learning new things.

### My skills
* HTML5 & CSS3 (Adaptive layout)
* Bootstrap (basic)
* JavaScript (basic)
* Git, GitHub (basic)
* VS Code
* Figma (basic)
* CMS:
    * Jumla
    * Wordpress
    * Opencart
    * WebAssyst

### Сode example
Unfortunately, I haven’t had time to solve problems with codewars yet, so I’ll show you a snippet of code from connecting the mobile menu of my project with a little animation:
```
document.addEventListener("DOMContentLoaded", () => {
    let modal = document.querySelector(".modalMobil");
    let modalContent = document.querySelector(".modalMobil_content");
    let body = document.querySelector("body");
    document.querySelector(".iconMobilMenu").onclick = () => {
        modal.classList.add("openModal");
        modalContent.classList.remove("disappearModal");
        modalContent.classList.add("appearModal");
        body.style.overflow = "hidden";
    }
    document.querySelector(".iconCloseMenu").onclick = () => {
        modalContent.classList.remove("appearModal");
        modalContent.classList.add("disappearModal");
        function delayFunc() {
            modal.classList.remove("openModal");
            body.style.overflow = "auto";
        }
        setTimeout(delayFunc, 1950);
    }
});
```

### My experience
Since I am currently working in a web studio, so I have experience in website layout. Quite a lot of laid-out sites ranging from one-page sites to online stores.

I also have a little experience with the use of JS. But its application is simple from modals and mobile menus to simple calculators.

I would like to share my first combat layout experience uploaded to github. This is just about a year ago. Since then, I have never looked at that code, it's scary ... Here is a link not to it: [My first Work](https://simon-smirnov.github.io/-abbisianwell.github.io/)

### Completed courses
I don't have any courses like this. I learned how to type from three sources:
1. Book "CSS in Depth", Kit Grant
2. [Webref](https://webref.ru/)
3. YouTube videos from various bloggers

I also read several books on JS for beginners

### English proficiency
I haven't taken any English proficiency tests, but I assume reading is A2 and conversational A1




