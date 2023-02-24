# AutoClicker
<h1>How to Use -<h1>

<h3>1.Copy the code by hovering  below code</h3><br>

![image](https://user-images.githubusercontent.com/83860778/221115711-aa3c0704-e71c-43a7-8247-45779a796d54.png)

```bash
javascript: var DELAY=1,autoClickerStyleElement=document.createElement("style");function addClicker(t){t.isTrusted&&(t.target.classList.contains("auto-clicker-target")?t.target.classList.remove("auto-clicker-target"):t.target.classList.add("auto-clicker-target"),document.body.removeChild(autoClickerStyleElement),document.body.removeEventListener("click",addClicker),t.preventDefault(),autoClick(t.target))}function autoClick(t){t.classList.contains("auto-clicker-target")&&(t.click(),setTimeout(function(){autoClick(t)},DELAY))}autoClickerStyleElement.innerHTML="*{cursor: cell !important;}",document.body.appendChild(autoClickerStyleElement),document.body.addEventListener("click",addClicker,0);
```

<br>
<br>
<h3>2.Copy code by clicking the box<br></h3>

![image](https://user-images.githubusercontent.com/83860778/221111950-35e25f59-9fe2-4d3a-b843-a4f18eab88e1.png)
<br>
<br>
3.Create a bookmark<br>
<br>
<br>
![image](https://user-images.githubusercontent.com/83860778/221113597-a02d719c-f42c-46d9-8893-c406433606e1.png)
<br>
<br>
4.During creating bookmark press more and give A name and paste the code in url<br>
<br>
<br>
![image](https://user-images.githubusercontent.com/83860778/221114022-c9834edf-b4ee-402e-a18b-bb8a99fb871f.png)
![image](https://user-images.githubusercontent.com/83860778/221114497-cfc3b693-fe01-492b-9f9f-cbd1adecfe42.png)



---------------------------------------------------------------------------------------------------------------------------
https://user-images.githubusercontent.com/83860778/221111161-b97d5de6-199a-440b-b30c-e9aedbe3bc43.mp4
