---
layout: page
title: CV
permalink: /cv/
nav: true
nav_order: 2
---

<script>
  document.addEventListener('DOMContentLoaded', function () {
    const pdf = '/assets/pdf/Hamza_Alshamy_CV.pdf';

    // Open PDF in a new tab
    window.open(pdf, '_blank', 'noopener');

    // Return the current tab to where the user came from (if on your site).
    const ref = document.referrer || '/';
    try {
      const sameOrigin = new URL(ref, window.location.origin).origin === window.location.origin;
      if (sameOrigin) { window.history.back(); } else { window.location.href = '/'; }
    } catch (_) {
      window.location.href = '/';
    }
  });
</script>

<p>Opening CV… If nothing happens, <a href="/assets/pdf/Hamza_Alshamy_CV.pdf" target="_blank" rel="noopener">click here</a>.</p>
