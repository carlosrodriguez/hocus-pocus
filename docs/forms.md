### Forms

Usage:

<div class="example">
  <form class="form-inline">
    <input type="email" placeholder="E-mail">
    <input type="password" placeholder="Password">

    <button type="submit">Submit</button>
  </form>
</div>

```html
<form class="form-inline">
  <input type="email" placeholder="E-mail">
  <input type="password" placeholder="Password">

  <button type="submit">Submit</button>
</form>
```

<div class="example">
  <form class="form-stacked">
    <label for="name">Name</label>
    <input id="name">

    <label for="email">E-mail</label>
    <input type="email" id="email">

    <label for="password">Password</label>
    <input type="password" id="password">

    <label for="search">Search</label>
    <input type="search" id="search">

    <label for="disabled">Disabled</label>
    <input type="text" id="disabled" disabled>

    <label>
      <input type="checkbox">Remember me</input>
    </label>

    <label for="gender">Gender</label>
    <select id="gender">
      <option selected></option>
      <option value="female">Female</option>
      <option value="male">Male</option>
    </select>

    <label for="comment">Comment</label>
    <textarea id="comment"></textarea>

    <button type="submit">Submit</button>
  </form>
</div>

```html
<form class="form-stacked">
  <label for="name">Name</label>
  <input id="name">

  <label for="email">E-mail</label>
  <input type="email" id="email">

  <label for="password">Password</label>
  <input type="password" id="password">

  <label>
    <input type="checkbox">Remember me</input>
  </label>

  <label for="gender">Gender</label>
  <select id="gender">
    <option selected></option>
    <option value="female">Female</option>
    <option value="male">Male</option>
  </select>

  <label for="comment">Comment</label>
  <textarea id="comment"></textarea>

  <button type="submit">Submit</button>
</form>
```

<div class="example">
  <form class="form-horizontal">
  <div class="form-item">
  <label for="email">E-mail</label>
  <input type="email" id="email">
  </div>

  <div class="form-item">
  <label for="password">Password</label>
  <input type="email" id="email">
  </div>

  <div class="form-group">
  <label>
  <input type="checkbox">Remember me</input>
  </label>

  <button type="submit">Submit</button>
  </div>
  </form>
</div>

```html
<form class="form-horizontal">
  <div class="form-item">
    <label for="email">E-mail</label>
    <input type="email" id="email">
  </div>

  <div class="form-item">
    <label for="password">Password</label>
    <input type="password" id="password">
  </div>

  <div class="form-group">
    <label>
      <input type="checkbox">Remember me</input>
    </label>

    <button type="submit">Submit</button>
  </div>
</form>
```
