- What does a **doctype** do?
  - In HTML, the doctype tells the browser what version of HTML is being used.

- How do you serve a page with content in multiple languages?
  - Declare language being used in HTML, &lt;html lang='en'&gt;

- What kind of things do you need to be wary of when developing/designing multilingual sites?
  - Difference between ltr, rtl languages.
  - Color perception in different areas
  - Format of dates and times

- What are data- attributes good for?
  - Data attributes are good for attaching custom attributes to tags. They can then be used in JS to give interactive experiences.

- Consider HTML5 as an open web platform. What are the building blocks of HTML5?
  - The new semantic elements in HTML5 like article, section, main, header, nav, etc.
  - New API's like geolocation, canvas, web workers, etc.

- Describe the difference between a cookie, sessionStorage and localStorage.
  - LocalStorage has no expiration date, and it is only cleared by Javascript or clearing browser cache, locally stored data. read on client side only
  - sessionStorage is cleared when the browser window is closed. read on client side only
  - cookie stores data that has to be sent back to the server with subsequent requests. Its expiration varies based on the type and the expiration duration can be set from either server-side or client-side

- Why is it generally a good idea to position CSS &lt;link&gt; between &lt;head&gt;&lt;/head&gt; and JS &lt;script&lt; just before &lt;/body&gt;? Do you know any exceptions?
  - CSS is put in the head of a document to avoid FOUC.
  - JS is put at the end because it usually requires the elements to be loaded in. Javascript also blocks rendering by default.