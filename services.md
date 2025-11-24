---
layout: page
title: Services 
description: English-speaking relocation and legal-support services for expats moving to Spain — visas, NIE, property, banking, autónomo, and more. Delivered with trusted lawyer partners.
permalink: /services/
---
<!-- Centralized styles (inline so nothing else needed) -->
<style>
  /* Brand colours */
  :root { --juro-red:#E30613; --juro-yellow:#FFD700; --soft-bg:#fff8f0; --muted:#666; }

  /* Page layout */
  .services-grid { display:flex; flex-wrap:wrap; gap:18px; margin:18px 0 30px; }
  .service-box { flex:1 1 320px; border:2px solid var(--juro-red); background:var(--soft-bg); border-radius:10px; padding:16px; box-sizing:border-box; }
  .service-icon { font-size:28px; margin-bottom:8px; display:inline-block; width:44px; height:44px; line-height:44px; text-align:center; border-radius:8px; background:#fff; border:1px solid rgba(0,0,0,0.06); }
  .service-title { font-size:1.05rem; margin:6px 0 8px; font-weight:700; }
  .muted { color:var(--muted); font-size:0.95rem; }
  .divider { height:8px; background:linear-gradient(90deg,var(--juro-red),var(--juro-yellow)); border-radius:4px; margin:22px 0; }

  /* CTA */
  .cta-box { border:2px solid var(--juro-red); background:var(--soft-bg); padding:18px; border-radius:10px; text-align:center; margin:20px 0; }
  .cta-button { background:var(--juro-red); color:#fff; padding:10px 16px; border-radius:6px; text-decoration:none; font-weight:700; display:inline-block; }

  /* FAQ styles + arrow */
  details.service-faq { margin-bottom:12px; border:1px solid #ddd; border-radius:8px; padding:12px; background:var(--soft-bg); }
  summary.service-sum { font-weight:700; cursor:pointer; list-style:none; position:relative; padding-left:28px; }
  summary.service-sum .arrow { position:absolute; left:6px; top:50%; transform:translateY(-50%); transition: transform .25s; display:inline-block; }
  details[open] summary.service-sum .arrow { transform: rotate(90deg) translateY(-50%); }
  summary.service-sum::-webkit-details-marker { display:none; }

  /* Responsive */
  @media (max-width:700px) {
    .services-grid{ flex-direction:column; }
  }

  /* Small highlight for 'we are not a law firm' */
  .note { background:#fff; border-left:4px solid var(--juro-red); padding:12px; border-radius:6px; margin:12px 0; }
</style>

<!-- Page content -->
<h1><span style="color:var(--juro-red);">J</span><span style="color:var(--juro-yellow);">U</span><span style="color:var(--juro-red);">R</span><span style="color:var(--juro-yellow);">O</span> Spain — Services for Expats</h1>

<p class="muted">Clear, English-first support for relocating to Spain: visas & residency, NIE numbers, property transactions, banking, autónomo registration, and practical onboarding — delivered via trusted, specialist lawyer partners when legal representation is required.</p>

<div class="note">
  <strong>Not a law firm.</strong> We coordinate relocation, documents, and process management and connect you with vetted Spanish lawyers who specialise in the exact area you need (immigration, property, tax, civil matters). You’ll always know if and when a lawyer is involved.
</div>

<div class="divider" aria-hidden="true"></div>

<!-- Services grid -->
<h2>Core Services</h2>
<div class="services-grid">

  <div class="service-box" aria-labelledby="immigration-title">
    <div class="service-icon">🛂</div>
    <div id="immigration-title" class="service-title">Immigration & Residency</div>
    <div class="muted">
      NIE applications, residency activation, document checks and in-person support. We coordinate police, consulate and administrative steps for English-speaking expats.
    </div>
  </div>

  <div class="service-box" aria-labelledby="digital-title">
    <div class="service-icon">💻</div>
    <div id="digital-title" class="service-title">Digital Nomad Visa Support</div>
    <div class="muted">
      Eligibility assessment, income & employment documentation, insurance checks and residency activation guidance for remote workers and founders.
    </div>
  </div>

  <div class="service-box" aria-labelledby="nlv-title">
    <div class="service-icon">🏝️</div>
    <div id="nlv-title" class="service-title">Non-Lucrative Residency</div>
    <div class="muted">
      Financial planning, consulate preparation, insurance review and renewal roadmaps for long-term residency without local employment.
    </div>
  </div>

  <div class="service-box" aria-labelledby="property-title">
    <div class="service-icon">🏡</div>
    <div id="property-title" class="service-title">Property Transactions</div>
    <div class="muted">
      Reservation & contract review, nota simple and registry searches, notary attendance and post-purchase filings — coordinated with partner property lawyers.
    </div>
  </div>

  <div class="service-box" aria-labelledby="mortgage-title">
    <div class="service-icon">🏦</div>
    <div id="mortgage-title" class="service-title">Mortgages for Expats</div>
    <div class="muted">
      Bank comparisons, LTV guidance, application packaging and translations — we prepare everything to optimise your mortgage outcome.
    </div>
  </div>

  <div class="service-box" aria-labelledby="poa-title">
    <div class="service-icon">✍️</div>
    <div id="poa-title" class="service-title">Power of Attorney (POA)</div>
    <div class="muted">
      Bilingual POAs, apostille coordination and representation at notary signings so you can act in Spain when needed.
    </div>
  </div>

  <div class="service-box" aria-labelledby="banking-title">
    <div class="service-icon">💳</div>
    <div id="banking-title" class="service-title">Banking Support</div>
    <div class="muted">
      Non-resident account setup, KYC preparation, branch introductions and online banking walkthroughs.
    </div>
  </div>

  <div class="service-box" aria-labelledby="autonomo-title">
    <div class="service-icon">📑</div>
    <div id="autonomo-title" class="service-title">Autónomo Registration</div>
    <div class="muted">
      Hacienda & Social Security onboarding, IVA guidance, accounting tool recommendations and compliance reminders.
    </div>
  </div>

</div> <!-- end services-grid -->

<div class="divider" aria-hidden="true"></div>

<!-- Why choose -->
<h2>Why choose <span style="color:var(--juro-red);">J</span><span style="color:var(--juro-yellow);">U</span><span style="color:var(--juro-red);">R</span><span style="color:var(--juro-yellow);">O</span> Spain?</h2>

<ul>
  <li><strong>English-first</strong> — clear instructions and support in English throughout the process.</li>
  <li><strong>Specialist partners</strong> — we match you to vetted lawyers only when legal representation is needed.</li>
  <li><strong>Fixed-fee clarity</strong> — transparent pricing where possible and clear quotes when partner fees are required.</li>
  <li><strong>Nationwide coverage</strong> — we coordinate remotely and arrange in-person meetings through local partners as needed.</li>
  <li><strong>Fast, practical</strong> — we manage paperwork, appointments and deadlines so you can get on with moving.</li>
</ul>

<div class="cta-box">
  <h3 style="margin:0 0 8px 0;">Not sure which service fits?</h3>
  <p class="muted" style="margin:0 0 12px 0;">Book a short call and we’ll recommend the exact mix of services for your move — no obligation.</p>
  <a class="cta-button" href="https://calendly.com/hello-jurospain/30min">Book a call — 30 minutes</a>
</div>

<div class="divider" aria-hidden="true"></div>

<!-- Large FAQ section (human-friendly + structured for Google) -->
<h2 id="faq">Frequently Asked Questions</h2>

<details class="service-faq">
  <summary class="service-sum"><span class="arrow">►</span> Are you a law firm?</summary>
  <div class="muted">No. <span style="color:var(--juro-red);">J</span><span style="color:var(--juro-yellow);">U</span><span style="color:var(--juro-red);">R</span><span style="color:var(--juro-yellow);">O</span> Spain is a relocation and coordination service. We work with vetted, specialist Spanish lawyers depending on the area — immigration, property, tax, or civil matters. If your case needs legal representation, we introduce and coordinate with the right lawyer and manage the process end-to-end.</div>
</details>

<details class="service-faq">
  <summary class="service-sum"><span class="arrow">►</span> Why not contact a lawyer directly?</summary>
  <div class="muted">
    Many expats benefit from a one-stop coordinator who:
    <ul>
      <li>speaks fluent English</li>
      <li>prepares paperwork correctly</li>
      <li>pre-screens lawyers and matches the best specialist</li>
      <li>handles translations, bookings and follow-ups so the legal work is efficient</li>
    </ul>
  </div>
</details>

<details class="service-faq">
  <summary class="service-sum"><span class="arrow">►</span> How does your lawyer partnership work?</summary>
  <div class="muted">
    We maintain relationships with vetted lawyers across Spain. For each case we:
    <ol>
      <li>assess your needs</li>
      <li>select the best-fit lawyer partner</li>
      <li>coordinate documents, translations and appointments</li>
      <li>oversee progress and communicate updates to you in English</li>
    </ol>
  </div>
</details>

<details class="service-faq">
  <summary class="service-sum"><span class="arrow">►</span> How do you charge for partner lawyer work?</summary>
  <div class="muted">
    We provide transparent quotes. Where partner lawyer fees are required, we present a clear breakdown before you proceed. Wherever possible we offer fixed-fee packages for coordination and standard processes.
  </div>
</details>

<details class="service-faq">
  <summary class="service-sum"><span class="arrow">►</span> Do you operate nationwide?</summary>
  <div class="muted">Yes — we coordinate remotely across Spain and arrange in-person meetings through our local partners when necessary (Barcelona, Valencia, Málaga, Alicante and other locations as needed).</div>
</details>

<details class="service-faq">
  <summary class="service-sum"><span class="arrow">►</span> Can you help families and couples?</summary>
  <div class="muted">Absolutely. We regularly work with families, partners and groups relocating together — from school certificates and empadronamiento to family residency and property purchases.</div>
</details>

<details class="service-faq">
  <summary class="service-sum"><span class="arrow">►</span> What documents will I need for NIE / visas?</summary>
  <div class="muted">Documents vary by process. Typically: passport, proof of address, appointment confirmations, proof of funds for visas, employment or contract letters. We supply a tailored checklist for your case and help collect, translate and validate documents.</div>
</details>

<details class="service-faq">
  <summary class="service-sum"><span class="arrow">►</span> How long does the process take?</summary>
  <div class="muted">Timing depends on the service. NIEs can be weeks; visa processes depend on consulate workloads; property purchases vary with transaction complexity. We set expectations up front and manage timelines actively to reduce delays.</div>
</details>

<!-- FAQ arrow behavior (reused from homepage pattern) -->
<style>
  details[open] summary.service-sum .arrow { transform: rotate(90deg) translateY(-50%); }
  summary.service-sum::-webkit-details-marker { display:none; }
</style>

<!-- FAQPage JSON-LD for rich results -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "Are you a law firm?",
      "acceptedAnswer": { "@type": "Answer", "text": "No. JURO Spain is a relocation and coordination service. We work with vetted, specialist Spanish lawyers depending on the area — immigration, property, tax, or civil matters. If your case needs legal representation, we introduce and coordinate with the right lawyer and manage the process end-to-end." }
    },
    {
      "@type": "Question",
      "name": "Why not contact a lawyer directly?",
      "acceptedAnswer": { "@type": "Answer", "text": "Many expats benefit from a one-stop coordinator who speaks fluent English, prepares paperwork correctly, pre-screens lawyers and matches the best specialist, and handles translations, bookings and follow-ups so the legal work is efficient." }
    },
    {
      "@type": "Question",
      "name": "How does your lawyer partnership work?",
      "acceptedAnswer": { "@type": "Answer", "text": "We assess your needs, select the best-fit lawyer partner, coordinate documents, translations and appointments, and oversee progress while communicating updates in English." }
    },
    {
      "@type": "Question",
      "name": "How do you charge for partner lawyer work?",
      "acceptedAnswer": { "@type": "Answer", "text": "We provide transparent quotes. Where partner lawyer fees are required, we present a clear breakdown before you proceed. Wherever possible we offer fixed-fee packages for coordination and standard processes." }
    },
    {
      "@type": "Question",
      "name": "Do you operate nationwide?",
      "acceptedAnswer": { "@type": "Answer", "text": "Yes — we coordinate remotely across Spain and arrange in-person meetings through our local partners when necessary (Barcelona, Valencia, Málaga, Alicante and other locations as needed)." }
    },
    {
      "@type": "Question",
      "name": "Can you help families and couples?",
      "acceptedAnswer": { "@type": "Answer", "text": "Yes. We regularly work with families, partners and groups relocating together — from school certificates and empadronamiento to family residency and property purchases." }
    },
    {
      "@type": "Question",
      "name": "What documents will I need for NIE / visas?",
      "acceptedAnswer": { "@type": "Answer", "text": "Documents vary by process. Typically: passport, proof of address, appointment confirmations, proof of funds for visas, employment or contract letters. We supply a tailored checklist for your case and help collect, translate and validate documents." }
    },
    {
      "@type": "Question",
      "name": "How long does the process take?",
      "acceptedAnswer": { "@type": "Answer", "text": "Timing depends on the service. NIEs can be weeks; visa processes depend on consulate workloads; property purchases vary with transaction complexity. We set expectations up front and manage timelines actively to reduce delays." }
    }
  ]
}
</script>

<!-- Bottom CTA -->
<div style="margin-top:22px;">
  <p><strong>Ready to plan your move?</strong></p>
  <p><a class="cta-button" href="https://calendly.com/hello-jurospain/30min">Book a call — 30 minutes</a></p>
</div>
