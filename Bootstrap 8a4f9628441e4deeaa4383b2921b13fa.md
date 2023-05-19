# Bootstrap

Bootstrap is a free and open-source front-end development framework that enables developers to create responsive, mobile-first web pages and applications quickly and easily. It includes pre-designed HTML, CSS, and JavaScript components, such as forms, buttons, and navigation bars, that can be easily customized and combined to create complex and responsive user interfaces.

Bootstrap was created by a designer and a developer at Twitter in 2010, and has since become one of the most popular frameworks used for web development. Bootstrap 5, the latest version, was released in May 2021 and includes new features such as a simpler and cleaner codebase and improved grid system.

One of the main benefits of Bootstrap is that it allows developers to create professional-looking web pages quickly and efficiently, without having to write huge amounts of custom CSS or JavaScript. Additionally, Bootstrap is highly customizable, allowing developers to adjust the default settings to better fit their specific project needs.

# Bootstrap Containers

The container class is one of the most important Bootstrap classes.

It provides margins, padding, alignments, and more, to HTML elements.

# Example

```html
<div class="container">
  <h1>This is a paragraph</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</div>
```

# **Bootstrap Colors**

```html
<div class="container bg-primary text-white p-4">
<p>London is the most populous city in the United Kingdom, with a metropolitan area of over 9 million inhabitants.</p>
</div>

<div class="container bg-success text-white p-4">
<p>London is the most populous city in the United Kingdom, with a metropolitan area of over 9 million inhabitants.</p>
</div>
```

# Bootstrap Text Colors

This text is muted.

This text is important.

This text indicates success.

This text represents some information.

This text represents a warning.

This text represents danger.

```html
<div class="container">
  <p class="text-muted">This text is muted.</p>
  <p class="text-primary">This text is important.</p>
  <p class="text-success">This text indicates success.</p>
  <p class="text-info">This text represents some information.</p>
  <p class="text-warning">This text represents a warning.</p>
  <p class="text-danger">This text represents danger.</p>
</div><div class="container">
  <p class="text-muted">This text is muted.</p>
  <p class="text-primary">This text is important.</p>
  <p class="text-success">This text indicates success.</p>
  <p class="text-info">This text represents some information.</p>
  <p class="text-warning">This text represents a warning.</p>
  <p class="text-danger">This text represents danger.</p>
</div>
```

# Bootstrap Columns

Three equal-width columns, on all devices and screen widths:

# Example

```html
<div class="row">
  <div class="col">.col</div>
  <div class="col">.col</div>
  <div class="col">.col</div>
</div>
```

# Responsive Columns

Three equal-width columns scaling to stack on top of each other on small screens:

# Example

```html
<div class="row">
  <div class="col-sm-4">.col-sm-4</div>
  <div class="col-sm-4">.col-sm-4</div>
  <div class="col-sm-4">.col-sm-4</div>
</div>
```

# Bootstrap Tables

A boredered zebra-striped table:

| Firstname | Lastname | Email |
| --- | --- | --- |
| John | Doe | john@example.com |
| Mary | Moe | mary@example.com |
| July | Dooley | july@example.com |

```html
<table class="table table-striped table-bordered">
  <thead>
    <tr>
      <th>Firstname</th>
      <th>Lastname</th>
      <th>Email</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>John</td>
      <td>Doe</td>
      <td>john@example.com</td>
    </tr>
    <tr>
      <td>Mary</td>
      <td>Moe</td>
      <td>mary@example.com</td>
    </tr>
    <tr>
      <td>July</td>
      <td>Dooley</td>
      <td>july@example.com</td>
    </tr>
  </tbody>
</table>
```

# Bootstrap Alerts

Bootstrap provides an easy way to create predefined alert messages:

**Success!**  This alert box indicates a successful or positive action.

**Warning!**  This alert box indicates a warning that might need attention.

**Danger!**  This alert box indicates a dangerous or potentially negative action.

**Primary!**  This alert box indicates an important action.

# Example

```html
<div class="alert alert-success">
  <strong>Success!</strong> Indicates a successful or positive action.
</div>
<div class="alert alert-warning">
  <strong>Success!</strong> Indicates a successful or positive action.
</div>
<div class="alert alert-danger">
  <strong>Success!</strong> Indicates a successful or positive action.
</div>
<div class="alert alert-primary">
  <strong>Success!</strong> Indicates a successful or positive action.
</div>
```

# Bootstrap Buttons

Bootstrap provides different styles of buttons:

Basic :  Primary Secondary Success Info Warning Danger Dark

# Example

```html
<button type="button" class="btn">Basic</button>
<button type="button" class="btn btn-primary">Primary</button>
<button type="button" class="btn btn-secondary">Secondary</button>
<button type="button" class="btn btn-success">Success</button>
<button type="button" class="btn btn-info">Info</button>
<button type="button" class="btn btn-warning">Warning</button>
<button type="button" class="btn btn-danger">Danger</button>
<button type="button" class="btn btn-dark">Dark</button>
```

# Bootstrap Cards

![https://www.w3schools.com/whatis/img_avatar1.png](https://www.w3schools.com/whatis/img_avatar1.png)

### John Doe

Some example text some example text. John Doe is an architect and engineer.

See Profile

**Example**

```html
<div class="card" style="width:400px">
  <img src="img_avatar1.png" alt="Card image">
  <div class="card-body">
    <h4 class="card-title">John Doe</h4>
    <p class="card-text">Some example text.</p>
    <a href="#" class="btn btn-primary">See Profile</a>
  </div>
</div>
```