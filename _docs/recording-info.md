---
layout: page
title: Recording info
permalink: /docs/recording-info/
---

Do you need more info about recording? We have some variables for you, which have some recording indentificators. The most useful one will be URL for sure, thanks to which you can play any given recording.

<table class="table">
  <thead class="thead-light">
    <th>Variable</th>
    <th>Description</th>
    <th>Example</th>
  </thead>
  <tbody>
    <tr>
      <td>
        <code>playUrl</code>
      </td>
      <td>Recording URL</td>
      <td>https://www.smartlook.com/app/12a3bcd45678efa90123b4567/play/a12bCDEfg</td>
    </tr>
    <tr>
      <td>
        <code>projectId</code>
      </td>
      <td>Project ID</td>
      <td>12a3bcd45678efa90123b4567</td>
    </tr>
    <tr>
      <td>
        <code>sessionId</code>
      </td>
      <td>Session ID</td>
      <td>a12bCDEfg</td>
    </tr>
    <tr>
      <td>
        <code>visitorId</code>
      </td>
      <td>Visitor ID</td>
      <td>AbcDeFGhi</td>
    </tr>
    <tr>
      <td>
        <code>recordId</code>
      </td>
      <td>Recording ID</td>
      <td>A1B2c345dE</td>
    </tr>
    <tr>
      <td>
        <code>key</code>
      </td>
      <td>Project key</td>
      <td>a123bcd4e56ab123b3456789b12ab1234abcde1a</td>
    </tr>
  </tbody>
</table>

See how to access variables. Below is an example how it can look in a console.

```javascript
<script>
  smartlook(
    function () {
      console.log(smartlook.playUrl);
      console.log(smartlook.visitorId);
    }
  );
</script>
```

Let's say you want to save recording URL in your own service. Such a code can look like this.

```javascript
<script>
  smartlook(
    function () {
      MyServiceToLogUrl.sendToApi(smartlook.playUrl);
    }
  );
</script>
```