# Components

## Alert Information

> Alert usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>
  <body>
    <div class="alert" role="alert">This is alert!</div>
  </body>
</html>
```

> Alert outset usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>
  <body>
    <div class="alert alert-outset" role="alert">This is alert outset!</div>
  </body>
</html>
```

> Alert colors

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>
  <body>
    <div class="alert" role="alert">This is alert!</div>
    <div class="alert alert-primary" role="alert">This is alert!</div>
    <div class="alert alert-secondary" role="alert">This is alert!</div>
    <div class="alert alert-success" role="alert">This is alert!</div>
    <div class="alert alert-danger" role="alert">This is alert!</div>
    <div class="alert alert-warning" role="alert">This is alert!</div>
  </body>
</html>
```

> Alert dismissing

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>
  <body>
    <div class="alert" id="Alt">
      <span
        ><strong>Well done!</strong> You successfully read this important alert
        message.</span
      >
      <button class="alt-close">X</button>
    </div>

    <script type="text/javascript" src="../src/neomo.js"></script>
  </body>
</html>
```

## Badge Information

> Badge usage

```html
<html>
  <head>
    <meta charset="utf-8" />
    <title></title>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>
  <body>
    <div class="mt-5">
      <span class="badge">NEOMO</span>
    </div>
  </body>
</html>
```

> Badge background colors

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title></title>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>
  <body>
    <div class="mt-5">
      <span class="badge badge-primary">NEOMO</span>
      <span class="badge badge-secondary">NEOMO</span>
      <span class="badge badge-success">NEOMO</span>
      <span class="badge badge-danger">NEOMO</span>
      <span class="badge badge-warning">NEOMO</span>
    </div>
  </body>
</html>
```

> Badge size

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title></title>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>
  <body>
    <div class="mt-5">
      <span class="badge badge-sm">NEOMO</span>
      <span class="badge badge-md">NEOMO</span>
      <span class="badge badge-rg">NEOMO</span>
    </div>
  </body>
</html>
```

## Button Information

> Simple Button usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>

  <body>
    <div class="container bg-gray">
      <br />
      <button class="button outset-gray m-10">기본 버튼</button>
      <br />
      <button class="button outset-gray square m-10">사각형 버튼</button>
      <br />
    </div>
    <br />
    <div class="container bg-dark">
      <br />
      <button class="button outset-dark small m-10">small</button>
      <button class="button outset-dark normal m-10">normal</button>
      <button class="button outset-dark medium m-10">medium</button>
      <button class="button outset-dark large m-10">large</button>
      <br />
    </div>
    <br />
    <div class="container bg-blue">
      <br />
      <button class="button blue m-10">파란색 기본 버튼</button>
      <br />
      <button class="button blue square blue m-10">파란색 사각형 버튼</button>
      <br />
    </div>
  </body>
</html>
```

## Select Information

> Select usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>
  <body>
    <div class="mt-2 ml-2">
      <select>
        <option selected>This is select menu</option>
        <option value="1">One</option>
        <option value="2">Two</option>
        <option value="3">Three</option>
      </select>
    </div>
  </body>
</html>
```

> Select colors

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>

  <body>
    <div class="mt-2 ml-2">
      <select>
        <option selected>This is select menu</option>
        <option value="1">One</option>
        <option value="2">Two</option>
        <option value="3">Three</option>
      </select>
      <select class="slt-primary">
        <option selected>This is select menu</option>
        <option value="1">One</option>
        <option value="2">Two</option>
        <option value="3">Three</option>
      </select>
      <select class="slt-success">
        <option selected>This is select menu</option>
        <option value="1">One</option>
        <option value="2">Two</option>
        <option value="3">Three</option>
      </select>
      <select class="slt-danger">
        <option selected>This is select menu</option>
        <option value="1">One</option>
        <option value="2">Two</option>
        <option value="3">Three</option>
      </select>
      <select class="slt-warning">
        <option selected>This is select menu</option>
        <option value="1">One</option>
        <option value="2">Two</option>
        <option value="3">Three</option>
      </select>
    </div>
  </body>
</html>
```

> multiple select example

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>
  <body>
    <div class="mt-2 ml-2">
      <select multiple>
        <option selected>This is select menu</option>
        <option value="1">One</option>
        <option value="2">Two</option>
        <option value="3">Three</option>
      </select>
    </div>
  </body>
</html>
```

## Spinners Information

> Simple Spinners usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>

  <body>
    <div class="container bg-gray">
      <br />
      <button class="button outset-gray m-10">
        <div class="loader"></div>
      </button>
      <br />
    </div>
    <br />
    <div class="container bg-dark">
      <br />
      <button class="button outset-dark small m-10">
        small&nbsp;
        <div class="loader-gray"></div>
      </button>
      <button class="button outset-dark normal m-10">
        normal&nbsp;
        <div class="loader-gray"></div>
      </button>
      <button class="button outset-dark medium m-10">
        medium&nbsp;
        <div class="loader-gray"></div>
      </button>
      <button class="button outset-dark large m-10">
        large&nbsp;
        <div class="loader-gray"></div>
      </button>
      <br />
    </div>
    <br />
    <div class="container bg-blue">
      <br />
      <button class="button outset-blue m-10">
        <div class="loader-blue"></div>
      </button>
      <br />
    </div>
  </body>
</html>
```

## Navigation Information

> Naviagtion type1 usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" href="../src/neomo.css" />
  </head>
  <body>
    <ul class="nav">
      <li class="nav-item">
        <a class="nav-link active" href="#">Active</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled">Disabled</a>
      </li>
    </ul>
  </body>
</html>
```

> Naviagtion type1-animation usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" href="../src/neomo.css" />
  </head>
  <body>
    <ul class="nav">
      <li class="nav-item">
        <a class="nav-link--animation" href="#">Active</a>
      </li>
      <li class="nav-item">
        <a class="nav-link--animation" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link--animation" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link--animation" href="#">Disabled1</a>
      </li>
      <li class="nav-item">
        <a class="nav-link--animation disabled">Disabled</a>
      </li>
    </ul>
  </body>
</html>
```

> Naviagtion type2 usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" href="../src/neomo.css" />
  </head>
  <body>
    <ul class="nav2">
      <li class="nav-item2">
        <a class="nav-link2 active" href="#">Active</a>
      </li>
      <li class="nav-item2">
        <a class="nav-link2 active" href="#">Active</a>
      </li>
      <li class="nav-item2">
        <a class="nav-link2 active" href="#">Active</a>
      </li>
      <li class="nav-item2">
        <a class="nav-link2 active" href="#">Active</a>
      </li>
    </ul>
  </body>
</html>
```

> Naviagtion column usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" href="../src/neomo.css" />
  </head>

  <body>
    <ul class="nav-column">
      <li class="nav-item--column">
        <a class="nav-link--column" href="#">Active</a>
      </li>
      <li class="nav-item--column">
        <a class="nav-link--column" href="#">Link</a>
      </li>
      <li class="nav-item--column">
        <a class="nav-link--column" href="#">Link</a>
      </li>
      <li class="nav-item--column">
        <a class="nav-link--column" href="#">Disabled1</a>
      </li>
      <li class="nav-item--column">
        <a class="nav-link--column disabled">Disabled</a>
      </li>
    </ul>
  </body>
</html>
```

## Card Information

> Simple card usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <meta charset="utf-8" />
    <title>test.html</title>
    <link rel="stylesheet" type="text/css" href="src/neomo.css" />
  </head>
  <body>
    <div class="card" style="width: 18rem;">
      <header class="card-header">
        <p class="card-header-title">Component</p>
      </header>
      <div class="card-image">
        <img
          src="https://bulma.io/images/placeholders/1280x960.png"
          alt="Placeholder image"
        />
      </div>
      <div class="card-content">
        <div>
          <div class="media-left">
            <img
              src="https://bulma.io/images/placeholders/96x96.png"
              alt="Placeholder image"
            />
          </div>
          <div>
            <p>John Smith</p>
            <p>@johnsmith</p>
          </div>
        </div>

        <div class="content">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec
          iaculis mauris. <a>@bulmaio</a>. <a href="#">#css</a>
          <a href="#">#responsive</a>
          <br />
          <time datetime="2016-1-1">11:09 PM - 1 Jan 2016</time>
        </div>
      </div>
      <footer class="card-footer">
        <a href="#" class="card-footer-item">Save</a>
        <a href="#" class="card-footer-item">Edit</a>
        <a href="#" class="card-footer-item">Delete</a>
      </footer>
    </div>
  </body>
</html>
```

## Dropdown Information

> Simple Dropdown usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>
  <body class="p-2">
    <div class="dropdown">
      <button class="dropdown-button gray">Dropdown</button>
      <div class="dropdown-content">
        <a href="#">HTML</a>
        <a href="#">CSS</a>
        <a href="#">JAVA</a>
        <a href="#">C++</a>
      </div>
    </div>
  </body>
</html>
```

## Pagination Information

> Simple Pagination usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>
  <body class="p-2">
    <div class="pagination">
      <ul class="pagination-list">
        <li><a href="#">Previous</a></li>
        <li><a href="#">1</a></li>
        <li><a href="#">2</a></li>
        <li><a href="#">3</a></li>
        <li><a href="#">4</a></li>
        <li><a href="#">5</a></li>
        <li><a href="#">6</a></li>
        <li><a href="#">7</a></li>
        <li><a href="#">8</a></li>
        <li><a href="#">Next</a></li>
      </ul>
    </div>
  </body>
</html>
```

## Modal Information

> Simple Ouset Modal usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>
  <body class="p-2">
    <button id="ModalBtn" class="button outset-gray" onclick="ModalOpen()">Open outset modal</button>
    <div id="Modal" class="modal">
      <div class="modal-content outset-gray">
        <span class="modal-close">&times;</span>
        <p>Any other element you want</p>
      </div>
    </div>

    <script type="text/javascript" src="../src/neomo.js"></script>
  </body>
</html>
```

> Simple Inset Modal usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>
  <body class="p-2">
    <button id="ModalBtn" class="button outset-gray" onclick="ModalOpen()">Open inset modal</button>
    <div id="Modal" class="modal">
      <div class="modal-content inset-gray">
        <span class="modal-close">&times;</span>
        <p>Any other element you want</p>
      </div>
    </div>

    <script type="text/javascript" src="../src/neomo.js"></script>
  </body>
</html>
```

> Ouset Image Modal usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>
  <body class="p-2">
    <button id="ModalBtn" class="button outset-gray" onclick="ModalOpen()">
      Open outset image modal
    </button>
    <div id="Modal" class="modal">
      <div class="modal-content outset-gray">
        <span class="modal-close">&times;</span>
        <p class="image">
          <img
            src="https://images.unsplash.com/photo-1593642634315-48f5414c3ad9?ixid=MXwxMjA3fDF8MHxlZGl0b3JpYWwtZmVlZHwxfHx8ZW58MHx8fA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60"
            alt=""
          />
        </p>
      </div>
    </div>

    <script type="text/javascript" src="../src/neomo.js"></script>
  </body>
</html>
```

> Outset Card Modal usage

```html
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>
  <body class="p-2">
    <button id="ModalBtn" class="button outset-gray" onclick="ModalOpen()">
      Open outset card modal
    </button>
    <div id="Modal" class="modal">
      <div class="modal-card-sm outset-gray">
        <span class="modal-close">&times;</span>
        <img
          class="card-img-top"
          src="http://t1.daumcdn.net/friends/prod/editor/dc8b3d02-a15a-4afa-a88b-989cf2a50476.jpg"
          alt="Card image cap"
        />
        <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">here is an card contents write some texts</p>
          <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
      </div>
    </div>

    <script type="text/javascript" src="../src/neomo.js"></script>
  </body>
</html>
```

> Column usage

```html
<html>
  <head>
    <meta charset="utf-8" />
    <title>test.html</title>
    <link rel="stylesheet" type="text/css" href="src/neomo.css" />
  </head>
  <body>
    <div class="container">
      <div class="columns">
        <div class="column">
          <p class="neomo-inset m-1 p-2" style="text-align:center;">
            First column
          </p>
        </div>
        <div class="column">
          <p class="neomo-inset m-1 p-2" style="text-align:center;">
            Second column
          </p>
        </div>
        <div class="column">
          <p class="neomo-inset m-1 p-2" style="text-align:center;">
            Third column
          </p>
        </div>
        <div class="column">
          <p class="neomo-inset m-1 p-2" style="text-align:center;">
            Fourth column
          </p>
        </div>
      </div>

      <div class="columns">
        <div class="column size-1">
          <p class="neomo-outset m-1 p-2" style="text-align:center;">size1</p>
        </div>
        <div class="column size-2">
          <p class="neomo-outset m-1 p-2" style="text-align:center;">size2</p>
        </div>
        <div class="column size-3">
          <p class="neomo-outset m-1 p-2" style="text-align:center;">size3</p>
        </div>
        <div class="column size-4">
          <p class="neomo-outset m-1 p-2" style="text-align:center;">size4</p>
        </div>
      </div>

      <div class="columns">
        <div class="column size-5">
          <p class="neomo-outset m-1 p-2" style="text-align:center;">size5</p>
        </div>
        <div class="column size-6">
          <p class="neomo-outset m-1 p-2" style="text-align:center;">size6</p>
        </div>
      </div>

      <div class="columns">
        <div class="column size-7">
          <p class="neomo-outset m-1 p-2" style="text-align:center;">size7</p>
        </div>
      </div>
      <div class="columns">
        <div class="column size-8">
          <p class="neomo-outset m-1 p-2" style="text-align:center;">size8</p>
        </div>
      </div>
      <div class="columns">
        <div class="column size-9">
          <p class="neomo-outset m-1 p-2" style="text-align:center;">size9</p>
        </div>
      </div>
      <div class="columns">
        <div class="column size-10">
          <p class="neomo-outset m-1 p-2" style="text-align:center;">size10</p>
        </div>
      </div>
      <div class="columns">
        <div class="column size-11">
          <p class="neomo-outset m-1 p-2" style="text-align:center;">size11</p>
        </div>
      </div>
      <div class="columns">
        <div class="column size-12">
          <p class="neomo-outset m-1 p-2" style="text-align:center;">size12</p>
        </div>
      </div>
    </div>
  </body>
</html>
```

> Progress Bar usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>
  <body class="p-2">
    <div class="columns">
      <div class="column size-3">
        <h2>Choose your color</h2>
        <span>success</span>
        <div class="progress">
          <div class="progress-bar success" style="width: 60%;"></div>
        </div>
        <span>info</span>
        <div class="progress">
          <div class="progress-bar info" style="width: 60%;"></div>
        </div>
        <span>danger</span>
        <div class="progress">
          <div class="progress-bar danger" style="width: 60%;"></div>
        </div>
        <span>dark</span>
        <div class="progress">
          <div class="progress-bar dark" style="width: 60%;"></div>
        </div>
        <span>gray</span>
        <div class="progress">
          <div class="progress-bar gray" style="width: 60%;"></div>
        </div>
      </div>
    </div>
  </body>
</html>
```

## Icon Information

> square-icon type1 usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" href="../neomo.css" />
  </head>

  <body>
    <div class="icon-square icon-xs">
      <i class="fas fa-home fa-xs"></i>
    </div>
  </body>
</html>
```

> square-icon type2 usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" href="../neomo.css" />
  </head>

  <body>
    <div class="icon-square2 icon-xs">
      <i class="fas fa-home fa-xs"></i>
    </div>
  </body>
</html>
```

> circle-icon type1 usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" href="../neomo.css" />
  </head>

  <body>
    <div class="icon-circle icon-sm">
      <i class="fas fa-home fa-sm"></i>
    </div>
  </body>
</html>
```

> circle-icon type2 usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" href="../neomo.css" />
  </head>

  <body>
    <div class="icon-circle2 icon-sm">
      <i class="fas fa-home fa-sm"></i>
    </div>
  </body>
</html>
```

## Tab Information

> Tab usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>
  <body class="p-2" style="background-color: var(--neomo-gray)">
    <div class="tab">
      <ul class="tab-list gray">
        <li class="current" data-tab="tab1" onclick="TabToggle()">
          <a href="#">Tab1</a>
        </li>
        <li data-tab="tab2" onclick="TabToggle()"><a href="#">Tab2</a></li>
        <li data-tab="tab3" onclick="TabToggle()"><a href="#">Tab3</a></li>
        <li data-tab="tab4" onclick="TabToggle()"><a href="#">Tab4</a></li>
      </ul>

      <div id="tab1" class="tab-content current inset-gray">
        <div class="tab-content--title">Tab1</div>
        <p class="tab-content--text">wirte your text1</p>
      </div>

      <div id="tab2" class="tab-content inset-gray">
        <div class="tab-content--title">Tab2</div>
        <p class="tab-content--text">wirte your text2</p>
      </div>

      <div id="tab3" class="tab-content inset-gray">
        <div class="tab-content--title">Tab3</div>
        <p class="tab-content--text">wirte your text3</p>
      </div>

      <div id="tab4" class="tab-content inset-gray">
        <div class="tab-content--title">Tab4</div>
        <p class="tab-content--text">wirte your text4</p>
      </div>
    </div>

    <script src="http://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script type="text/javascript" src="../src/neomo.js"></script>
  </body>
</html>
```

## Tooltips Information

> tooltips usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>

  <body>
    <div class="container">
      <h1>Tooltip Example</h1>
      <br />
      <br />
      <br />
      <div class="tooltip">
        <span>Hover here!</span>
        <div class="tooltip-content bottom outset-blue">
          <p>bottom tooltip!</p>
        </div>
      </div>
      <br />
      <br />
      <br />
      <div class="tooltip">
        <span>Hover here!</span>
        <div class="tooltip-content top outset-dark">
          <p>top tooltip!</p>
        </div>
      </div>
      <br />
      <br />
      <br />
      <div class="tooltip">
        <span>Hover here!</span>
        <div class="tooltip-content left outset-gray">
          <p>left tooltip!</p>
        </div>
      </div>
      <br />
      <br />
      <br />
      <div class="tooltip">
        <span>Hover here!</span>
        <div class="tooltip-content right outset-gray">
          <p>right tooltip!</p>
        </div>
      </div>
    </div>
  </body>
</html>
```

## Navbar Information

> navbar-search usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" type="text/css" href="../src/neomo.css" />
  </head>
  <body>
    <form class="search-bar">
      <input type="text" class="search-bar--text" placeholder="Search" />
      <input type="submit" class="search-bar--button" value="Search" />
    </form>
  </body>
</html>
```

## Toast Information

> toast usage

```html
<!DOCTYPE html>
<html charset="utf-8">
  <head>
    <title>test</title>
    <link rel="stylesheet" href="../neomo.css" />
  </head>

  <body>
    <div class="columns m-5">
      <div class="columns m-5">
      <div class="column size-3">
        <div class="toast show inset-blue" role="alert" aria-live="assertive" aria-atomic="true">
            <div class="toast-header">
              <span class=""></span> 
              <strong class="mr-auto ml-2">Neumorphism</strong> 
              <small class="mr-2 ml-auto">11 mins ago</small> 
              <button type="button" class="" data-dismiss="toast" aria-label="Close" onclick="toast_button(this);">
                <span aria-hidden="true">×</span>
              </button>
            </div>
            <div class="toast-body">Hello, world! This is a toast message.</div>
        </div>
      </div>
      <div class="column size-3">
        <div class="toast show outset-blue" role="alert" aria-live="assertive" aria-atomic="true">
            <div class="toast-header">
              <span class=""></span> 
              <strong class="mr-auto ml-2">Neumorphism</strong> 
              <small class="mr-2 ml-auto">11 mins ago</small> 
              <button type="button" class="" data-dismiss="toast" aria-label="Close" onclick="toast_button(this);">
                <span aria-hidden="true">×</span>
              </button>
            </div>
            <div class="toast-body">Hello, world! This is a toast message.</div>
        </div>
      </div>
    </div>
  </body>
</html>

<script type="text/javascript" src="../src/components/toast.js"></script>
```
