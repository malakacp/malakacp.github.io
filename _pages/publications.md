---
layout: page
title: Patents
permalink: /publications/
nav: true
nav_order: 2
---

<style>
/* 1. Transform the ugly 'HTML' button into a sleek 'Google Patent' button */
.publications a[href*="patents.google.com"],
.publications a.btn[role="button"] {
  font-size: 0 !important; /* Hides the word 'HTML' */
  display: inline-flex !important;
  align-items: center !important;
  padding: 5px 14px !important;
  border-radius: 6px !important;
  background: rgba(30, 144, 255, 0.08) !important;
  border: 1px solid rgba(30, 144, 255, 0.3) !important;
  color: #1a73e8 !important;
  text-decoration: none !important;
  transition: all 0.2s ease-in-out !important;
  box-shadow: 0 1px 3px rgba(0,0,0,0.05) !important;
}

.publications a[href*="patents.google.com"]::before,
.publications a.btn[role="button"]::before {
  content: "Google Patent" !important;
  font-size: 0.82rem !important;
  font-weight: 600 !important;
  letter-spacing: 0.01em;
}

.publications a[href*="patents.google.com"]::after,
.publications a.btn[role="button"]::after {
  content: " ↗" !important;
  font-size: 0.9rem !important;
  margin-left: 5px !important;
}

.publications a[href*="patents.google.com"]:hover,
.publications a.btn[role="button"]:hover {
  background: rgba(30, 144, 255, 0.18) !important;
  color: #1557b0 !important;
  transform: translateY(-1px) !important;
  box-shadow: 0 3px 8px rgba(30, 144, 255, 0.25) !important;
}

/* 2. Style the patent badges and award sub-labels */
.publications abbr.badge {
  font-size: 0.85rem !important;
  padding: 6px 10px !important;
  border-radius: 6px !important;
  line-height: 1.3 !important;
  text-align: center !important;
  display: inline-block !important;
}

.publications .badge-award {
  display: block;
  font-size: 0.72rem;
  font-weight: 700;
  color: #d97706; /* Gold/Amber highlight */
  margin-top: 3px;
  text-transform: uppercase;
  letter-spacing: 0.03em;
}
</style>

<div class="publications">

{% bibliography %}

</div>
