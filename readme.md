# Project 1

## Original Output Image

![Original Image](./firstAssignmentImage/output%20-%20original.png)

## Task 1: Achieve the following Output using JavaScript DOM Manipulation

![Task 1 Output Image](./firstAssignmentImage/task1Output.png)

## JavaScript Code:

```js
const ul = document.getElementsByTagName("ul");
const project = document.createElement("li");
const hireMe = document.createElement("li");
const projectLink = document.createElement("a");
const hireMeLink = document.createElement("a");

ul[0].children[2].remove();
project.appendChild(projectLink);
projectLink.innerText = "Projects";
projectLink.href = "#";

hireMe.append(hireMeLink);
hireMeLink.innerText = "Hire Me";
hireMeLink.href = "#";

ul[0].append(project);
ul[0].append(hireMe);
ul[1].children[0].style.display = "none";
ul[1].children[1].style.display = "none";
ul[1].children[2].style.display = "none";
```

## Task 2: Achieve the following Output using JavaScript DOM Manipulation

![Task 2 Output Image](./firstAssignmentImage/task2Output.png)

## JavaScript Code:

```js
const ul = document.getElementsByTagName("ul");
const project = document.createElement("li");
const projectLink = document.createElement("a");
const input = document.getElementsByTagName("input");

ul[0].children[2].remove();
project.appendChild(projectLink);
projectLink.innerText = "Projects";
projectLink.href = "#";
ul[0].append(project);
input[0].placeholder = "Search My Project";
ul[1].children[0].style.display = "none";
ul[1].children[1].style.display = "none";
ul[1].children[2].style.display = "none";
```

## Task 3: Achieve the following Output using JavaScript DOM Manipulation

![Task 3 Output Image](./firstAssignmentImage/task3Output.png)

## JavaScript Code:

```js
const ul = document.getElementsByTagName("ul");
const project = document.createElement("li");
const projectLink = document.createElement("a");
const span = document.querySelector(".hero-left-section p");

ul[0].children[2].remove();
project.appendChild(projectLink);
projectLink.innerText = "Projects";
projectLink.href = "#";
ul[0].append(project);
span.children[2].innerText = "an Employee";
span.children[4].innerText = "iNeuron Intelligence Pvt Ltd";
```

## Task 4: Achieve the following Output using JavaScript DOM Manipulation

![Task 4 Output Image](./firstAssignmentImage/task4Output.png)

## JavaScript Code:

```js
const ul = document.getElementsByTagName("ul");
const project = document.createElement("li");
const projectLink = document.createElement("a");
const img = document.querySelector(".hero-right-section img");

ul[0].children[2].remove();
project.appendChild(projectLink);
projectLink.innerText = "Projects";
projectLink.href = "#";
ul[0].append(project);
img.src =
  "https://hiteshchoudhary.com/static/a8d73d1aac4c79e9bb689640e6090367/2eaab/person-image.jpg";
```

## Task 5: Achieve the following Output using JavaScript DOM Manipulation

![Task 5 Output Image](./firstAssignmentImage/task5Output.png)

## JavaScript Code:

```js
const ul = document.getElementsByTagName("ul");
const project = document.createElement("li");
const projectLink = document.createElement("a");
const btnContainer = document.querySelector(".hero-right-section-btns");
const btn = document.createElement("button");

ul[0].children[2].remove();
project.appendChild(projectLink);
projectLink.innerText = "Projects";
projectLink.href = "#";
ul[0].append(project);
btn.innerText = "Support Me";
btnContainer.append(btn);
```

---

---

# Project 2

## Original Image

![Original Image](./secondAssignmentImage/original%20output%20image.png)

## Task 1: Achieve the following Output using JavaScript DOM Manipulation

![Task 1 Output Image](./secondAssignmentImage/task1Output.png)

## JavaScript Code:

```js
const ul = document.getElementsByTagName("ul");
const project = document.createElement("li");
const projectLink = document.createElement("a");
const acco = document.querySelectorAll(".accordian h3");

ul[0].children[2].remove();
project.appendChild(projectLink);
projectLink.innerText = "Projects";
projectLink.href = "#";
ul[0].append(project);
acco[0].style.background = "#dadaf8";
acco[1].style.background = "#dadaf8";
acco[2].style.background = "#dadaf8";
acco[3].style.background = "#dadaf8";
```

## Task 2: Achieve the following Output using JavaScript DOM Manipulation

![Task 2 Output Image](./secondAssignmentImage/task2Output.png)

## JavaScript Code:

```js
const ul = document.getElementsByTagName("ul");
const project = document.createElement("li");
const projectLink = document.createElement("a");
const acco = document.querySelectorAll(".accordian h3");
const accoWrapper = document.querySelector(".accordian-wrapper");
const div = document.createElement("div");
const h3 = document.createElement("h3");
const p = document.createElement("p");

ul[0].children[2].remove();
project.appendChild(projectLink);
projectLink.innerText = "Projects";
projectLink.href = "#";
ul[0].append(project);
acco[0].style.background = "#dadaf8";
acco[1].style.background = "#dadaf8";
acco[2].style.background = "#dadaf8";
acco[3].style.background = "#dadaf8";

div.className = "accordian";
h3.innerText = "Skills";
h3.style.background = "#dadaf8";
p.innerText =
  "I posses a very good command over the Full Stack Development technologies like MERN which can be seen in my work over the Github.";
div.append(h3);
div.append(p);
accoWrapper.append(div);
```

---

---

# Project 3

## Original Image

![Original Image](./thirdAssignmentImage/original%20output%20image.png)

## Task 1: Achieve the following Output using JavaScript DOM Manipulation

![Task 1 Output Image](./thirdAssignmentImage/task1Output.png)

`## JavaScript Code:`

```js
const userName = document.querySelector(".userName");
const userEmail = document.querySelector(".userEmail");
const userMessage = document.querySelector(".userMessage");
const submit = document.querySelector(".mainRight form");
const enterName = document.querySelector(".enterName");
const enterMail = document.querySelector(".enterMail");
const enterMeassage = document.querySelector(".enterMessage");

submit.addEventListener("submit", (e) => {
  e.preventDefault();
  enterName.value = userName.value;
  enterMail.value = userEmail.value;
  enterMeassage.value = userMessage.value;
});
```
