---
title: "Contact Us"
author: Stuart Hertzog
date: '2018-06-14'
slug: ["contact"]
type: ["page"]
layout: "contactlayout"
categories: ["diabeticsbc"]
tags: ["diabeticsbc"]
---

<form name="contact" method="POST" netlify>
  <p>
    <label>Your Name: <input type="text" name="name" /></label>
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
<!--
  <p>
    <label>Your Health: <select name="health[]" multiple>
      <option value="diabetic">I have diabetes</option>
      <option value="non-diabetic">I do not have diabetes</option>
    </select></label>
  </p>
-->
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
