# New Year Mission

**Original Design gathered from:** <br>
<https://github.com/ProgrammingHero1/B9A1-New-Year-New-Mission>


**Goal:**
- [x] Finish header section.
- [x] Finish middle/main section.
- [x] Finish footer section.

**Live View** <br>
<https://new-year-mission-fed03.netlify.app/>

**Issues:**
 1. While zoom out or in lerger display, some of images got smaller and background gradient appear vissible. *Maybe its because of responsive.*
 Example: 
 ![](images/issues/1.PNG)

Solution:
```css
background-size: 100% 100%;
background-repeat: no-repeat;
```
 2. **Working with circle**

Solution:
 ```html
 <div class="circle">
    <div class="inner"></div>
</div>
 ```
 ```css
 .circle {
    height: 200px;
    width: 200px;
    background-color: aquamarine;
    border-radius: 50%;
    border: 10px solid rebeccapurple;

    /* to center circle */
    display: flex;
    justify-content: center;
    align-items: center;
}
.inner {
    height: 150px;
    width: 150px;
    background-color: blue;
    border-radius: 50%;
}
 ```
 3. **Positioning** <br>
 Example:
 ![](images/issues/2.PNG)

 Solution:
  ```css
.section {
    width: 500px;
    border: 2px solid white;
}
.relative {
    width: 200px;
    height: 200px;
    border: 2px solid white;
    font-size: 30px;
    position: relative;
    left: 50%;
}
.absolute{
    border: 2px solid white;
    font-size: 30px;
    width: fit-content;
    position: absolute;
    top: 10px;
    left: 200px;

}
 ```
 ```html
<section class="section">
    <div class="relative">Relative</div>
    <div class="absolute">Absolute</div>
</section>
 ```

Farhan Sadik