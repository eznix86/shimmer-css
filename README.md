# shimmer-css
Easiest way to add shimmer effect to your page with css

### Usage:

via a cdn:
```html
<link href="https://unpkg.com/shimmer-css@1.0.0/shimmer.css" rel="stylesheet">
```
via a package manager:
```bash
yarn add shimmer-css
# or
npm install --save shimmer-css
```


```html
  <div class="shimmer-wrapper">
      <div class="shimmer-circle shimmer-circle-md shimmer-animate"></div>
      <div class="shimmer-line shimmer-line-br shimmer-line-80 shimmer-animate"></div>
      <div class="divider"><hr/></div>
      <div class="shimmer-line shimmer-line-br shimmer-line-full shimmer-animate"></div>
      <div class="shimmer-line shimmer-line-br shimmer-line-full shimmer-animate"></div>
      <div class="shimmer-line shimmer-line-br shimmer-line-full shimmer-animate"></div>
  </div>
```

### Example:

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <link href="https://unpkg.com/shimmer-css@1.0.0/shimmer.css" rel="stylesheet">
    <style>
                    
        :root {
            --horizontal-margin: 25%;
        }
        .center-things {
            display: flex;
            flex-direction: column;
            margin-left: var(--horizontal-margin);
            margin-right: var(--horizontal-margin);
            margin-top: 2em;
            padding: 2em;
            box-shadow: 0 0 0 1px rgba(130, 120, 120, 0.2);
            border-radius: 8px;
        }
        @media screen and (max-width: 992px) {
            :root {
                --horizontal-margin: 0;
            }
            .center-things:first-child {
                margin-top: 0;
            }
        }
        .profile {
            display: flex;
            flex-direction: row;
        }
        .profile-data {
            display: flex;
            flex-direction: column;
            width: 120px;
            padding: 0 0 10px 10px;
        }
        .profile-data .shimmer-line:first-child {
            margin-top: 15px;
        }
    </style>
</head>
<body>
<div class="center-things">
    <div class="shimmer-wrapper">
        <div class="profile">
            <div class="shimmer-circle shimmer-circle-md shimmer-animate"></div>
            <div class="profile-data">
                <div class="shimmer-line shimmer-line-br shimmer-line-60 shimmer-animate"></div>
                <div class="shimmer-line shimmer-line-br shimmer-line-full  shimmer-animate"></div>
            </div>
        </div>
        <div class="shimmer-line shimmer-line-br shimmer-line-full shimmer-animate"></div>
        <div class="shimmer-line shimmer-line-br shimmer-line-full shimmer-animate"></div>
    </div>
</div>
<div class="center-things">
    <div class="shimmer-wrapper">
        <div class="profile">
            <div class="shimmer-circle shimmer-circle-md shimmer-animate"></div>
            <div class="profile-data">
                <div class="shimmer-line shimmer-line-br shimmer-line-60 shimmer-animate"></div>
                <div class="shimmer-line shimmer-line-br shimmer-line-full  shimmer-animate"></div>
            </div>
        </div>
        <div class="shimmer-line shimmer-line-br shimmer-line-full shimmer-animate"></div>
        <div class="shimmer-line shimmer-line-br shimmer-line-full shimmer-animate"></div>
    </div>
</div>
<div class="center-things">
    <div class="shimmer-wrapper">
        <div class="profile">
            <div class="shimmer-circle shimmer-circle-md shimmer-animate"></div>
            <div class="profile-data">
                <div class="shimmer-line shimmer-line-br shimmer-line-60 shimmer-animate"></div>
                <div class="shimmer-line shimmer-line-br shimmer-line-full  shimmer-animate"></div>
            </div>
        </div>
        <div class="shimmer-line shimmer-line-br shimmer-line-full shimmer-animate"></div>
        <div class="shimmer-line shimmer-line-br shimmer-line-full shimmer-animate"></div>
    </div>
</div>
<div class="center-things">
    <div class="shimmer-wrapper">
        <div class="profile">
            <div class="shimmer-circle shimmer-circle-md shimmer-animate"></div>
            <div class="profile-data">
                <div class="shimmer-line shimmer-line-br shimmer-line-60 shimmer-animate"></div>
                <div class="shimmer-line shimmer-line-br shimmer-line-full  shimmer-animate"></div>
            </div>
        </div>
        <div class="shimmer-line shimmer-line-br shimmer-line-full shimmer-animate"></div>
        <div class="shimmer-line shimmer-line-br shimmer-line-full shimmer-animate"></div>
    </div>
</div>
</body>
</html>

```
