<h1 style="text-align: center">...</h1>

> Hy, this is a wonderful and beautiful description. Don't you think so as well? I've been wondering what I am currently even doing, but might as well do something I'm probably never going to finish anyway or scrap halfway through.

<br>
<br>

<h3 style="text-align: center"><br>CSS / SCSS</h3>
<hr style="width: 60%;"/>

<br>

<div style="display: flex; justify-content: flex-start">
    <h4>Naming Convention</h4>
</div>
<div style="display: flex; justify-content: flex-start; width: 100%">
    <p>This convention is a mix of different inspirations, such as BEM, kebab-case and others.
    </p>
   
</div>
<div style="display: flex; justify-content: flex-start; width: 100%">
 <ul>
    <li>use descriptive class/id names</li>
    <li>class/id names should be written in kebab-case</li>
    <li>sort the class names by priority: id | class | DOM element</li>
    <li>sub classes should carry the name of its parent class</li>
    <li>modifier classes should carry the name of its parent class and be recognized by the -- with either a comprehensible name or the value</li>
    <li>use variables to define colors and define them at the start</li>
    <li>use descriptive variable names or comments</li>
   
</ul>
</div>

<br>

<div style="display: flex; justify-content: flex-end">
    <h4>Naming Convention</h4>
   
</div>
<div style="display: flex; justify-content: flex-end">
     <h5>examples - written in scss syntax</h5>
</div>
<div style="display: flex; justify-content: flex-end; width: 100%">

```scss
/************************************************************/

$primaryBtnColor: #f2a3bc
$primaryBtnFontColor: #000000

$secondaryBtnColor: #000040
$secondaryBtnFontColor: #ffffff

.btn {
  &.btn--hg {
    height: value;
    font-size: value;
  }

  &.btn--sm {
    ...
  }

  &.btn--h30 {
    ...
  }

  &.btn--pink {
    ...
  }

  &.btn-icon {
    font-family: "Material Icons";
    font-size: value;
    content: "e5e1";

    &.btn-icon-right:after {
        ...
    }

    &.btn-icon-left:after {
        ...
    }
  }

  &.btn-primary {
    background-color: $primaryBtnColor;
    color: $primaryBtnFontColor;
  }

  &.btn-secondary {
    background-color: $secondaryBtnColor;
    color: $secondaryBtnFontColor;
  }
}

/************************************************************/
```

</div>

<br>

<h3 style="text-align: center"><br>Project / File Structure</h3>
<hr style="width: 60%;"/>

<br>

<div style="display: flex; justify-content: flex-start">
    <h4>Naming Convention</h4>
</div>
<div style="display: flex; justify-content: flex-start; width: 100%">
    <p>This convention is pretty standard, although a big timesink in the beginning, but it will make the project more overseeable in the future.
    </p>
   
</div>
<div style="display: flex; justify-content: flex-start; width: 100%">
 <ul>
    <li>Components should be named in PascalCase</li>
    <li>Components shoudl be selfcontained in a subfolder</li>
    <li>Global or extremely basic styling should be seperate in a CSS folder, each file marked by an _ at the start of it's name.</li>
   
</ul>
</div>

<br>

<div style="display: flex; justify-content: flex-end">
    <h4>Naming Convention</h4>
   
</div>
<div style="display: flex; justify-content: flex-end">
     <h5>example - written for component based js framework</h5>
</div>
<div style="display: flex; justify-content: flex-end;">

```tsx
/************************************************************/

my-app/
├─ node_modules/
├─ public/
│  ├─ favicon.ico
│  └─ index.html
├─ src/
│  ├─ components/
│  │  ├─button/
│  │  │  ├─index.js
│  │  │  ├─Button.js
│  │  │  └─Button.scss
│  │  ├─navgation/
│  │  └─ ...
│  ├─ css/
│  │  └─ index.css
│  ├─ services/
│  │  ├─serviceworkers/
│  │  └─data/
│  └─ index.js
├─ .gitignore
├─ package.json
└─ README.md

/************************************************************/
```

</div>
