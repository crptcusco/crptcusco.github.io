---
layout: default
---

<script>
  const userLang = navigator.language || navigator.userLanguage;
  if (userLang.startsWith("es")) {
    window.location.href = "/README";
  } else {
    window.location.href = "/README_en";
  }
</script>

<p>Redirecting…</p>
