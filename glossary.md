---
layout: page
title: Spanish Expat Glossary - Immigration, Property, and Tax Terms
permalink: /glossary/
description: Comprehensive glossary of Spanish immigration, property, and tax terms for expats. Understand NIE, TIE, Golden Visa, IRPF, Escritura, and essential Spanish legal terminology.
---

<style>
:root {
    --primary-red: #b31b1b;
    --primary-blue: #003366;
    --text-dark: #1a1a1a;
    --text-medium: #4a4a4a;
    --bg-light: #f9f9f9;
    --border-light: #e0e0e0;
}

.glossary-search {
    margin: 30px 0;
    text-align: center;
}

.glossary-search input {
    width: 100%;
    max-width: 600px;
    padding: 15px 20px;
    font-size: 1rem;
    border: 2px solid var(--border-light);
    border-radius: 8px;
    transition: border-color 0.3s ease;
}

.glossary-search input:focus {
    outline: none;
    border-color: var(--primary-red);
}

.section-header {
    display: flex;
    align-items: center;
    gap: 12px;
    margin: 50px 0 30px 0;
    padding-bottom: 15px;
    border-bottom: 2px solid var(--border-light);
}

.section-icon {
    font-size: 2rem;
}

.section-title {
    font-size: 1.8rem;
    color: var(--primary-blue);
    font-weight: 700;
    margin: 0;
}

.glossary-section details {
    margin-bottom: 1rem;
    border: 1px solid #ddd;
    border-left: 5px solid var(--primary-red);
    padding-left: 15px;
    background-color: var(--bg-light);
    border-radius: 4px;
    transition: all 0.3s ease;
}

.glossary-section details:hover {
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    transform: translateY(-2px);
}

.glossary-section details[open] {
    background-color: #fff;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.glossary-section summary {
    font-weight: 700;
    font-size: 1.25rem;
    cursor: pointer;
    color: var(--primary-blue);
    padding: 10px 0;
    list-style: none;
    user-select: none;
}

.glossary-section summary::-webkit-details-marker {
    display: none;
}

.glossary-section summary::before {
    content: '▶';
    display: inline-block;
    margin-right: 10px;
    transition: transform 0.3s ease;
    color: var(--primary-red);
    font-size: 0.9em;
}

.glossary-section details[open] summary::before {
    transform: rotate(90deg);
}

.glossary-section summary:hover {
    color: var(--primary-red);
}

.glossary-section details p {
    margin-top: 0.5rem;
    padding-bottom: 10px;
    color: var(--text-medium);
}

.glossary-link {
    color: var(--primary-red);
    text-decoration: none;
    font-weight: 500;
    border-bottom: 1px solid transparent;
    transition: border-color 0.2s ease;
}

.glossary-link:hover {
    border-bottom-color: var(--primary-red);
}

.glossary-link[target="_blank"]::after {
    content: ' ↗';
    font-size: 0.85em;
}

.no-results {
    display: none;
    text-align: center;
    padding: 40px 20px;
    color: var(--text-medium);
    font-size: 1.1rem;
}

.no-results.show {
    display: block;
}

.stats {
    text-align: center;
    margin: 20px 0;
    color: var(--text-medium);
    font-size: 0.95rem;
}

@media (max-width: 768px) {
    .section-title {
        font-size: 1.5rem;
    }
    
    .glossary-section summary {
        font-size: 1.1rem;
        padding: 15px 10px;
    }
}
</style>

<div class="glossary-search">
    <input type="text" id="searchInput" placeholder="🔍 Search terms... (e.g., NIE, visa, tax, property)" />
</div>

<div class="stats" id="stats">
    Showing <span id="visibleCount">110</span> of <span id="totalCount">110</span> terms
</div>

<div class="no-results" id="noResults">
    <p>No terms found matching your search.</p>
</div>

<div class="section-header">
    <span class="section-icon">🚀</span>
    <h2 class="section-title">1. Immigration & Residency Terms</h2>
</div>

<div class="glossary-section">

<details data-terms="nie number identity extranjero foreigner identification administrative tax bank account property">
<summary>NIE (Número de Identidad de Extranjero)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The <strong>Foreigner's Identity Number</strong>. This is the unique, essential identification code required for virtually all major administrative and tax activities, such as <strong>opening a Spanish bank account</strong>, <strong>buying a property</strong>, or signing utility contracts. It is a mandatory requirement for all non-resident transactions. <a href="{{ '/guides/how-to-get-your-nie-number-in-spain/' | relative_url }}" class="glossary-link">Read our NIE Guide.</a>
</p>
</details>

<details data-terms="tie tarjeta identity card extranjero foreigner residency biometric permit">
<summary>TIE (Tarjeta de Identidad de Extranjero)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The <strong>Foreigner's Identity Card</strong>. This is the physical, <strong>biometric card</strong> that serves as proof of your legal residency status (e.g., Non-Lucrative, Digital Nomad, or Family Member of an EU Citizen). It is applied for <em>after</em> your initial visa approval and is subject to renewal.
</p>
</details>

<details data-terms="non-lucrative visa nlv residency passive income pension savings retirement">
<summary>Non-Lucrative Visa (NLV)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> A Spanish residency visa for non-EU citizens who wish to relocate based on <strong>demonstrable passive income, pension, or substantial savings</strong>. The central requirement is committing to <strong>not engage in local professional activity</strong>. It is typically renewed annually for the first two cycles. <a href="{{ '/guides/spain-non-lucrative-visa-income-requirements-and-application-steps/' | relative_url }}" class="glossary-link">NLV Requirements Explained.</a>
</p>
</details>

<details data-terms="digital nomad visa dnv remote work freelance entrepreneur beckham">
<summary>Digital Nomad Visa (DNV)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> A specialized residency permit for <strong>remote workers, qualified professionals, or entrepreneurs</strong> whose work originates primarily outside of Spain. It provides a pathway to residency, along with access to the advantageous <strong>Beckham Law</strong> tax regime. It is initially granted for three years. <a href="{{ '/guides/spain-digital-nomad-visa-requirements-income-thresholds-and-taxes/' | relative_url }}" class="glossary-link">Digital Nomad Visa Guide.</a>
</p>
</details>

<details data-terms="golden visa investment property real estate investor residency 500000">
<summary>Golden Visa</summary>
<p>
<span style="font-weight: 600;">Definition:</span> A residency permit granted to investors who make a <strong>significant capital investment</strong> in the Spanish economy, most commonly through the acquisition of real estate valued at <strong>€500,000 or more</strong>. It offers expedited processing and flexible stay requirements. <a href="{{ '/guides/spain-golden-visa-the-complete-2025-guide/' | relative_url }}" class="glossary-link">Golden Visa Guide.</a>
</p>
</details>

<details data-terms="permiso residencia residence permit authorization oficina extranjeria">
<summary>Permiso de Residencia</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The formal Spanish term for a <strong>Residency Permit</strong> or authorization to live legally in the country, granted by the Ministry of Foreign Affairs or the <em>Oficina de Extranjería</em>. <a href="https://en.wikipedia.org/wiki/Spanish_nationality_law" target="_blank" rel="noopener noreferrer" class="glossary-link">See Spanish Immigration Law.</a>
</p>
</details>

<details data-terms="residencia larga duracion long-term permanent residency pr five years">
<summary>Residencia de Larga Duración</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The status of <strong>Long-term residency</strong>, granting permanent rights to reside in Spain. This is typically applied for after five continuous years of holding legal temporary residency status, such as NLV or DNV.
</p>
</details>

<details data-terms="certificado registro ciudadano union eu eea swiss green card registration">
<summary>Certificado de Registro de Ciudadano de la Unión</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The <strong>EU Citizen Registration Certificate</strong> (often referred to as the 'green card'). This is mandatory for EU, EEA, or Swiss citizens planning to reside in Spain for longer than three months, proving their right of free movement.
</p>
</details>

<details data-terms="oficina extranjeria foreigners office immigration tie renewal application">
<summary>Oficina de Extranjería</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The <strong>Foreigners' Office</strong>. This regional government department is responsible for processing many local immigration procedures, TIE applications, and renewals within the Spanish territory.
</p>
</details>

<details data-terms="autorizacion residencia authorization permit approval government">
<summary>Autorización de Residencia</summary>
<p>
<span style="font-weight: 600;">Definition:</span> Official <strong>Residency Authorization</strong> granted by the government, which is the legal permission that allows a TIE to be issued.
</p>
</details>

<details data-terms="schengen area travel europe passport border control visa">
<summary>Schengen Area</summary>
<p>
<span style="font-weight: 600;">Definition:</span> A zone comprising 26 European countries that have abolished passport and border controls at their mutual borders. Holding a Spanish TIE grants the right to <strong>travel freely</strong> throughout the Schengen Area for periods up to 90 days. <a href="https://en.wikipedia.org/wiki/Schengen_Area" target="_blank" rel="noopener noreferrer" class="glossary-link">Schengen Area on Wikipedia.</a>
</p>
</details>

<details data-terms="uge unidad grandes empresas large companies strategic sectors fast track">
<summary>Unidad de Grandes Empresas (UGE)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The <strong>Large Companies and Strategic Sectors Unit</strong>. This specialized government body processes certain business-related and investment visas (like the DNV and Golden Visa), often providing a faster administrative route than standard applications.
</p>
</details>

<details data-terms="reagrupacion familiar family reunification spouse children dependents">
<summary>Reagrupación Familiar</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Family Reunification</strong>. The legal process by which a non-EU citizen who already holds valid Spanish residency can bring dependent family members (spouse, children, dependent parents) to live with them in Spain.
</p>
</details>

<details data-terms="autorizacion regreso return authorization travel permit re-entry border">
<summary>Autorización de Regreso</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Return Authorization</strong>. A temporary permit that allows a foreigner with an expiring TIE or a pending renewal application to leave Spain and <strong>re-enter the country legally</strong> without problems at the border control.
</p>
</details>

<details data-terms="hoja solicitud ex form application ex-00 ex-15 ex-19 paperwork">
<summary>Hoja de Solicitud (EX-Form)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The <strong>Application Form</strong>. The official, numbered government forms (e.g., EX-00, EX-15, EX-19) that must be correctly filled out and submitted for virtually every immigration procedure in Spain.
</p>
</details>

<details data-terms="antecedentes penales criminal record background check certificate police">
<summary>Antecedentes Penales</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Criminal Record</strong> certificate. A mandatory document required for most initial Spanish residency applications, proving that the applicant has no prior criminal convictions in their country of residence.
</p>
</details>

<details data-terms="visado estudios student visa university education study">
<summary>Visado de Estudios</summary>
<p>
<span style="font-weight: 600;">Definition:</span> A <strong>Student Visa</strong> for non-EU nationals enrolled in full-time, accredited educational programs in Spain lasting longer than 90 days. It is subject to renewal if the studies continue.
</p>
</details>

<details data-terms="arraigo social integration job offer residency unauthorized stay">
<summary>Arraigo Social</summary>
<p>
<span style="font-weight: 600;">Definition:</span> A specialized path to temporary residency based on <strong>long-term social integration</strong>. It typically requires proving continuous stay in Spain for at least three years (even if unauthorized) plus documented family ties or a formal job offer.
</p>
</details>

<details data-terms="visado residencia visa sticker passport consulate entry">
<summary>Visado de Residencia</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The <strong>Residency Visa</strong> sticker placed in your passport by a Spanish Consulate abroad. This document is valid for entry to Spain, after which the holder must apply for the physical TIE within 90 days.
</p>
</details>

<details data-terms="empadronamiento padron municipal registration census certificate address">
<summary>Empadronamiento</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Municipal Registration</strong> or census registration at your local town hall. This certificate proves your residential address in Spain and is required for many administrative procedures, including healthcare registration and school enrollment.
</p>
</details>

<details data-terms="apostille hague convention document legalization authentication consular">
<summary>Apostille</summary>
<p>
<span style="font-weight: 600;">Definition:</span> An international certification under the <strong>Hague Convention</strong> that authenticates documents for use in foreign countries. Required for many immigration documents like birth certificates, marriage certificates, and criminal records from your home country.
</p>
</details>

<details data-terms="arraigo laboral work permit employment contract unauthorized residence">
<summary>Arraigo Laboral</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Work-Based Social Integration</strong>. A residency path requiring proof of at least two years of continuous residence in Spain plus a valid employment contract of at least one year's duration.
</p>
</details>

<details data-terms="arraigo familiar family ties spanish citizenship blood relative">
<summary>Arraigo Familiar</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Family-Based Integration</strong>. A residency route available to parents of Spanish-born children or those with strong family connections to Spanish citizens, particularly when the family member depends on the applicant.
</p>
</details>

<details data-terms="carta invitacion invitation letter hosting private accommodation visitor">
<summary>Carta de Invitación</summary>
<p>
<span style="font-weight: 600;">Definition:</span> An <strong>Invitation Letter</strong> issued by a Spanish resident through the local police station, formally inviting a foreign visitor to stay at their private residence. Often required for tourist visa applications.
</p>
</details>

<details data-terms="tasa tax fee administrative charge immigration model 790">
<summary>Tasa</summary>
<p>
<span style="font-weight: 600;">Definition:</span> An <strong>Administrative Fee</strong> charged by the Spanish government for processing various procedures, particularly immigration applications. Paid via Modelo 790 forms at designated banks.
</p>
</details>

<details data-terms="nacionalidad citizenship naturalization spanish passport 10 years">
<summary>Nacionalidad Española</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Spanish Citizenship</strong> or nationality. Generally available after 10 years of legal continuous residence, though shorter periods apply for citizens of Ibero-American countries, Andorra, Philippines, Equatorial Guinea, Portugal, or Sephardic Jews.
</p>
</details>

<details data-terms="autorizacion trabajo work permit employment autorization job labor">
<summary>Autorización de Trabajo</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Work Authorization</strong> or work permit. Required for non-EU citizens to legally work in Spain. Can be tied to specific employers or be self-employment authorization (cuenta propia).
</p>
</details>

<details data-terms="cuenta ajena employee employed salaried work authorization">
<summary>Cuenta Ajena</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Employed Status</strong> or working for an employer. Refers to authorization to work as an employee for a Spanish company rather than being self-employed.
</p>
</details>

<details data-terms="cuenta propia self-employed freelance autonomo entrepreneur business">
<summary>Cuenta Propia</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Self-Employed Status</strong>. Authorization to work as a freelancer or business owner in Spain, requiring registration as an autónomo and different residency requirements than employed workers.
</p>
</details>

<details data-terms="renovacion renewal extension tie visa residency permit continuation">
<summary>Renovación</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Renewal</strong> of a residency permit or visa. Must typically be applied for 60 days before expiration and requires proving continued compliance with the original visa requirements.
</p>
</details>

<details data-terms="seguro medico health insurance healthcare private coverage sanitas adeslas">
<summary>Seguro Médico</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Health Insurance</strong>. Private health coverage is mandatory for many visa types (NLV, DNV) and must provide comprehensive coverage without copayments. Common providers include Sanitas, Adeslas, and Asisa.
</p>
</details>

<details data-terms="tarjeta sanitaria health card social security public healthcare ses">
<summary>Tarjeta Sanitaria</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The <strong>Public Health Card</strong> that provides access to Spain's public healthcare system. Issued by regional health authorities once you're registered in the Social Security system or as a resident.
</p>
</details>

<details data-terms="cita previa appointment booking online oficina extranjeria police">
<summary>Cita Previa</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Prior Appointment</strong>. The mandatory online booking system for appointments at immigration offices, police stations, and many government services. Often difficult to secure in major cities.
</p>
</details>

<details data-terms="justificante comprobante proof receipt payment submission document">
<summary>Justificante</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Proof</strong> or receipt. A document that evidences payment, submission, or completion of an administrative procedure. Essential to retain for all immigration applications.
</p>
</details>

<details data-terms="traduccion jurada sworn translation official translator certified documents">
<summary>Traducción Jurada</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Sworn Translation</strong>. An official translation performed by a certified translator registered with the Spanish Ministry of Foreign Affairs. Required for all foreign documents submitted to Spanish authorities.
</p>
</details>

</div>

---

<div class="section-header">
    <span class="section-icon">🏡</span>
    <h2 class="section-title">2. Property & Conveyancing Terms</h2>
</div>

<div class="glossary-section">

<details data-terms="escritura publica public deed title sale notary ownership transfer">
<summary>Escritura Pública</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The <strong>Public Deed of Sale</strong> (Title Deed). This is the official, final legal document, executed and signed before a Notary, that formally and publicly transfers property ownership from the seller to the buyer.
</p>
</details>

<details data-terms="nota simple property registry extract land registry debts liens charges">
<summary>Nota Simple</summary>
<p>
<span style="font-weight: 600;">Definition:</span> A brief but <strong>vital extract</strong> from the Property Registry (<em>Registro de la Propiedad</em>). It is the single most important document for due diligence, as it confirms the owner, legal status, and, crucially, details any <strong>existing debts, liens, or charges</strong> on the property.
</p>
</details>

<details data-terms="registro propiedad land registry property register ownership records">
<summary>Registro de la Propiedad</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The <strong>Land Registry</strong>. The official public institution that is responsible for maintaining the records of all Spanish property ownership and registering all legal charges associated with real estate transactions and mortgages.
</p>
</details>

<details data-terms="notario notary public official authentication certificate documents">
<summary>Notario (Notary)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> A <strong>Public Official</strong> required by Spanish law to authenticate, certify, and give full legal validity to documents. Their mandatory presence ensures all parties understand and agree to the legal contents of the <em>Escritura Pública</em> and Power of Attorney (POA).
</p>
</details>

<details data-terms="poder notarial power attorney poa lawyer representative authorization">
<summary>Poder Notarial (Power of Attorney - POA)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> A formal legal document, signed before a Notary, that grants a trusted, designated person (e.g., your lawyer) the <strong>legal authority to act on your behalf</strong> for specific tasks like signing the deed or arranging utilities, crucial for buying property remotely. <a href="{{ '/guides/power-of-attorney-in-spain-buy-sell-or-manage-admin-from-abroad/' | relative_url }}" class="glossary-link">POA Guide.</a>
</p>
</details>

<details data-terms="contrato arras reservation contract deposit earnest money 10% penalty">
<summary>Contrato de Arras</summary>
<p>
<span style="font-weight: 600;">Definition:</span> A legally binding <strong>private reservation contract</strong> that secures a property sale, usually involving the buyer paying a deposit (typically 10%). It sets a deadline for the final <em>Escritura</em> and outlines penalties for backing out. <a href="https://en.wikipedia.org/wiki/Earnest_money_deposit" target="_blank" rel="noopener noreferrer" class="glossary-link">Arras Contract (Earnest Money) on Wikipedia.</a>
</p>
</details>

<details data-terms="contrato compraventa purchase contract sales agreement price terms">
<summary>Contrato de Compraventa</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The <strong>Private Purchase Contract</strong> (sales contract). This is the detailed agreement used to formalize the terms of the sale, price, and conditions between the buyer and seller <em>before</em> the final public deed is signed at the Notary.
</p>
</details>

<details data-terms="due diligence legal investigation lawyer check title ownership debts">
<summary>Due Diligence</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The exhaustive <strong>legal investigation</strong> carried out by the buyer's lawyer to check the property's legal history, title ownership, zoning permissions, outstanding debts, and tax compliance before a purchase is finalized.
</p>
</details>

<details data-terms="cedula habitabilidad licencia primera ocupacion habitation certificate occupation">
<summary>Cédula de Habitabilidad / Licencia de Primera Ocupación</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The <strong>Habitation Certificate</strong> or <strong>First Occupation License</strong>. A document issued by the local council certifying that a property is legally constructed and <strong>fit for human habitation</strong>, crucial for registering utilities.
</p>
</details>

<details data-terms="catastro cadastral register cadastre valor catastral property tax ibi">
<summary>Catastro</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The <strong>Cadastral Register</strong>. An administrative register detailing the physical, economic, and legal characteristics of properties. This register determines the <em>Valor Catastral</em>, which is the base for property taxes (IBI).
</p>
</details>

<details data-terms="valor catastral cadastral value tax base ibi property tax assessment">
<summary>Valor Catastral</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The <strong>Cadastral Value</strong>. The official administrative value of a property set by the <em>Catastro</em>. It is almost always lower than the market value and serves as the <strong>tax base for IBI</strong> and often other regional taxes.
</p>
</details>

<details data-terms="comunidad propietarios community owners residents association fees hoa">
<summary>Comunidad de Propietarios</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The <strong>Community of Owners</strong> or Residents Association. It is the legal entity responsible for managing, maintaining, and setting fees for the common areas (pools, elevators, facades) of apartment buildings or housing developments.
</p>
</details>

<details data-terms="hipoteca mortgage loan secured ley hipotecaria bank financing">
<summary>Hipoteca</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The Spanish term for a <strong>Mortgage</strong> or secured loan on a property. <strong>Ley Hipotecaria</strong> refers to the specific Spanish law governing mortgages. <a href="https://www.rae.es/dh/hipoteca" target="_blank" rel="noopener noreferrer" class="glossary-link">Hipoteca definition (RAE).</a>
</p>
</details>

<details data-terms="plusvalia tax municipal capital gains land value increment seller">
<summary>Plusvalía Tax</summary>
<p>
<span style="font-weight: 600;">Definition:</span> A local <strong>Municipal Tax</strong> levied on the theoretical increase in the value of the land upon the sale or transfer of a property. By law, this tax is generally the <strong>responsibility of the seller</strong>.
</p>
</details>

<details data-terms="servidumbre easement right way access passage utility">
<summary>Servidumbre</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Easement</strong>. A legal right of access, passage, or use granted over one person's property for the benefit of another's property (e.g., an established right of way or utility access).
</p>
</details>

<details data-terms="nuda propiedad naked ownership bare ownership usufruct rights">
<summary>Nuda Propiedad</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Naked Ownership</strong>. The legal ownership of a property <em>without</em> the right to use or benefit from it. This right belongs to the <em>Usufructuario</em> (usufruct holder).
</p>
</details>

<details data-terms="usufructo usufruct life estate use rights income rental">
<summary>Usufructo</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The legal right to <strong>use and enjoy</strong> a property and receive its income (e.g., rent) without owning the actual title (the <em>Nuda Propiedad</em>).
</p>
</details>

<details data-terms="agente propiedad inmobiliaria api real estate agent licensed professional">
<summary>Agente de la Propiedad Inmobiliaria (API)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> A <strong>Registered Real Estate Agent</strong>. A professional, licensed title that requires passing an exam, although many working agents in Spain do not hold this specific accreditation.
</p>
</details>

<details data-terms="ibi impuesto bienes inmuebles property tax council rates annual">
<summary>IBI (Impuesto sobre Bienes Inmuebles)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Property Tax</strong> or council rates. An annual local tax paid by property owners, calculated based on the <em>Valor Catastral</em>. Rates vary significantly by municipality.
</p>
</details>

<details data-terms="itp impuesto transmisiones patrimoniales transfer tax stamp duty second-hand">
<summary>ITP (Impuesto sobre Transmisiones Patrimoniales)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Transfer Tax</strong> paid by buyers of <strong>second-hand properties</strong>. Rates vary by region (typically 6-10%) and are calculated on the higher of the declared price or official valuation. Not applicable to new builds, which pay IVA instead.
</p>
</details>

<details data-terms="iva impuesto valor añadido vat sales tax new build 10%">
<summary>IVA (Impuesto sobre el Valor Añadido)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Value Added Tax (VAT)</strong>. Set at <strong>10% for new build properties</strong> and 21% for most other goods and services. Paid by buyers of new construction instead of ITP.
</p>
</details>

<details data-terms="ajd actos juridicos documentados stamp duty legal documents notary">
<summary>AJD (Actos Jurídicos Documentados)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Stamp Duty on Legal Documents</strong>. An additional tax (typically 0.5-1.5%) paid on notarized property deeds and mortgages. Rates vary by autonomous community.
</p>
</details>

<details data-terms="referencia catastral cadastral reference property identifier number code">
<summary>Referencia Catastral</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The <strong>Cadastral Reference Number</strong>. A unique 20-character alphanumeric code that identifies every property in Spain. Essential for all property transactions and tax filings.
</p>
</details>

<details data-terms="obra nueva new build construction development off-plan primera transmision">
<summary>Obra Nueva</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>New Build</strong> or newly constructed property. Subject to IVA (10%) plus AJD instead of ITP. Includes off-plan purchases and first-time sales of newly completed properties.
</p>
</details>

<details data-terms="segunda mano second-hand resale used property existing">
<summary>Segunda Mano</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Second-Hand</strong> or resale property. Any property that has been previously owned and lived in. Subject to ITP (transfer tax) rather than IVA.
</p>
</details>

<details data-terms="tasacion valuation appraisal property value mortgage bank assessment">
<summary>Tasación</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Property Valuation</strong> or appraisal. A mandatory assessment by a certified valuer required by banks for mortgage applications. The valuation often determines the maximum loan amount.
</p>
</details>

<details data-terms="domiciliacion bancaria direct debit bank payment automatic ibi community">
<summary>Domiciliación Bancaria</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Direct Debit</strong> or automatic bank payment. Commonly used for recurring payments like IBI, community fees, utilities, and insurance premiums.
</p>
</details>

<details data-terms="gastos compraventa purchase costs closing costs fees taxes notary registro">
<summary>Gastos de Compraventa</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Purchase Costs</strong> or closing costs. Total expenses beyond the property price, typically 10-15% for buyers, including taxes, notary fees, land registry fees, and legal costs.
</p>
</details>

<details data-terms="entrega llaves completion handover keys possession property">
<summary>Entrega de Llaves</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Handover of Keys</strong>. The completion moment when the buyer receives physical possession of the property after signing the <em>Escritura</em> and making final payment.
</p>
</details>

<details data-terms="defectos ocultos hidden defects latent faults warranty vicios">
<summary>Defectos Ocultos</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Hidden Defects</strong>. Latent faults in a property not visible during inspection that may entitle the buyer to compensation or contract cancellation under Spanish law.
</p>
</details>

<details data-terms="comprador buyer purchaser adquirente cliente">
<summary>Comprador</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The <strong>Buyer</strong> or purchaser in a property transaction. The party acquiring ownership and responsible for most transaction costs and taxes.
</p>
</details>

<details data-terms="vendedor seller vendor owner transmitente">
<summary>Vendedor</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The <strong>Seller</strong> or vendor in a property transaction. The party transferring ownership, typically responsible for Plusvalía municipal tax and clearing any property debts.
</p>
</details>

<details data-terms="obra mayor major works building permit structural renovation construction">
<summary>Obra Mayor</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Major Works</strong>. Significant structural renovations or construction requiring formal building permits from the local council. Includes changes to load-bearing walls, additions, or major installations.
</p>
</details>

<details data-terms="obra menor minor works small renovation maintenance permit simple">
<summary>Obra Menor</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Minor Works</strong>. Small-scale renovations or maintenance that require only a simple permit or notification to the town hall, such as painting, tiling, or minor repairs.
</p>
</details>

<details data-terms="licencia obras building permit construction authorization works permit">
<summary>Licencia de Obras</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Building Permit</strong> or works license. Required authorization from the local council before commencing any construction or major renovation work on a property.
</p>
</details>

</div>

---

<div class="section-header">
    <span class="section-icon">💰</span>
    <h2 class="section-title">3. Tax & Financial Terms</h2>
</div>

<div class="glossary-section">

<details data-terms="agencia tributaria hacienda tax agency revenue compliance fiscal">
<summary>Agencia Tributaria (Hacienda)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The <strong>Spanish Tax Agency</strong>, often colloquially called <em>Hacienda</em>. This is the central government body responsible for collecting state taxes and enforcing <strong>fiscal compliance</strong> across residents and non-residents.
</p>
</details>

<details data-terms="irpf income tax personal renta personas fisicas resident 183 days worldwide">
<summary>IRPF (Impuesto sobre la Renta de las Personas Físicas)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Personal Income Tax</strong>. The standard tax residents in Spain pay on their <strong>worldwide income</strong>. Tax residency is triggered by spending <strong>more than 183 days</strong> per year in Spain. This is a progressive tax. <a href="https://en.wikipedia.org/wiki/Personal_income_tax_in_Spain" target="_blank" rel="noopener noreferrer" class="glossary-link">IRPF on Wikipedia.</a>
</p>
</details>

<details data-terms="irnr non-resident income tax impuesto renta no residentes rental imputed">
<summary>IRNR (Impuesto sobre la Renta de No Residentes)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Non-Resident Income Tax</strong>. This flat-rate tax is paid by individuals who are <strong>not tax residents</strong> but earn income from specific Spanish sources, most commonly from <strong>imputed income</strong> on property they own, or from rental income.
</p>
</details>

<details data-terms="regimen impatriados beckham law expat tax 24% flat rate dnv">
<summary>Régimen de Impatriados (Beckham Law)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> A <strong>Special Expat Tax Regime</strong> that allows qualified foreigners moving to Spain (e.g., DNV holders) to choose to be taxed as a non-resident for up to six years, paying a flat <strong>24% rate</strong> on Spanish-sourced income, instead of the higher, progressive IRPF rates. <a href="{{ '/guides/spain-beckham-law-tax-guide-2025/' | relative_url }}" class="glossary-link">Beckham Law Guide.</a>
</p>
</details>

<details data-terms="modelo 720 overseas assets foreign property bank accounts declaration 50000">
<summary>Modelo 720</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The mandatory informative declaration form used by <strong>Spanish tax residents</strong> to declare <strong>overseas assets</strong> (property, bank accounts, investments) valued at over €50,000. Penalties for non-compliance are severe.
</p>
</details>

<details data-terms="impuesto patrimonio wealth tax assets net worth autonomous communities">
<summary>Impuesto sobre el Patrimonio</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Wealth Tax</strong>. An annual tax levied on a tax resident's net worldwide assets (assets minus debts). The minimum exemption thresholds and rates are set by the <strong>Autonomous Communities</strong>.
</p>
</details>

<details data-terms="impuesto sucesiones donaciones isd inheritance gift tax death estate">
<summary>Impuesto de Sucesiones y Donaciones (ISD)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Inheritance and Gift Tax</strong>. A tax on assets received through inheritance (succession) or as a gift (donation). This tax is heavily regulated by the <strong>Autonomous Communities</strong>, leading to massive differences in liability across Spain. <a href="{{ '/guides/spain-inheritance-tax-planning-for-expats/' | relative_url }}" class="glossary-link">Inheritance Tax Planning Guide.</a>
</p>
</details>

<details data-terms="renta imputada imputed income deemed rental phantom tax property">
<summary>Renta Imputada</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Imputed Income</strong>. A deemed rental income that non-residents must pay tax on for Spanish properties they own but don't rent out, calculated as a percentage of the cadastral value.
</p>
</details>

<details data-terms="autonomo self-employed freelance social security reta monthly payment">
<summary>Autónomo</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Self-Employed</strong> status. Freelancers and business owners must register as autónomos, paying monthly social security contributions (typically €250-400) regardless of income. <a href="https://en.wikipedia.org/wiki/Self-employment" target="_blank" rel="noopener noreferrer" class="glossary-link">Self-Employment on Wikipedia.</a>
</p>
</details>

<details data-terms="seguridad social social security system contributions healthcare pension">
<summary>Seguridad Social</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The <strong>Social Security System</strong>. Mandatory contributions by employees and employers that fund public healthcare, unemployment benefits, and pensions. Registration required for legal employment.
</p>
</details>

<details data-terms="numero seguridad social nss social security number affiliation">
<summary>Número de Seguridad Social (NSS)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Social Security Number</strong>. A unique identifier assigned to all workers in Spain, required for employment, healthcare access, and pension entitlements.
</p>
</details>

<details data-terms="declaracion renta tax return annual filing modelo 100 hacienda">
<summary>Declaración de la Renta</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Annual Tax Return</strong>. The yearly income tax filing (Modelo 100 for IRPF) required by tax residents, typically due between April and June. Can result in refunds or additional payments.
</p>
</details>

<details data-terms="modelo 210 non-resident tax return irnr quarterly annual rental">
<summary>Modelo 210</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The tax form used by <strong>non-residents</strong> to declare IRNR tax on Spanish income. Filed quarterly for rental income or annually for imputed income on owned properties.
</p>
</details>

<details data-terms="modelo 100 personal income tax return irpf residents annual">
<summary>Modelo 100</summary>
<p>
<span style="font-weight: 600;">Definition:</span> The standard <strong>annual IRPF tax return</strong> form for Spanish tax residents declaring their worldwide income. Filed between April and June each year.
</p>
</details>

<details data-terms="retencion withholding tax deduction advance payment source employment">
<summary>Retención</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Withholding Tax</strong>. Tax deducted at source from salaries, professional fees, or investment income as an advance payment toward annual tax liability. Rates vary by income type.
</p>
</details>

<details data-terms="certificado residencia fiscal tax residency certificate form 136 double taxation">
<summary>Certificado de Residencia Fiscal</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Tax Residency Certificate</strong>. An official document proving your tax residency status, essential for claiming benefits under double taxation treaties between Spain and other countries.
</p>
</details>

<details data-terms="convenio doble imposicion double taxation treaty dtt tax agreement">
<summary>Convenio de Doble Imposición</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Double Taxation Treaty (DTT)</strong>. Bilateral agreements between Spain and other countries that prevent the same income from being taxed twice. Essential for expats with international income sources.
</p>
</details>

<details data-terms="plusvalia ganancia patrimonial capital gains profit asset sale property">
<summary>Plusvalía / Ganancia Patrimonial</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Capital Gains</strong>. Profit from the sale of assets (property, stocks, etc.), subject to taxation. For property, rates vary between 19-26% for residents depending on gain amount.
</p>
</details>

<details data-terms="desgravacion fiscal tax deduction relief allowance expenses">
<summary>Desgravación Fiscal</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Tax Deduction</strong> or relief. Allowable expenses or circumstances that reduce taxable income, such as mortgage interest (for pre-2013 purchases), pension contributions, or donations.
</p>
</details>

<details data-terms="gestor gestoria administrative agent tax accountant paperwork bureaucracy">
<summary>Gestor / Gestoría</summary>
<p>
<span style="font-weight: 600;">Definition:</span> An <strong>Administrative Agent</strong> or agency specializing in handling bureaucratic procedures, tax filings, vehicle registrations, and business paperwork. Essential for navigating Spanish administration.
</p>
</details>

<details data-terms="asesor fiscal tax advisor accountant consultant gestor tributario">
<summary>Asesor Fiscal</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Tax Advisor</strong> or accountant. A qualified professional who provides tax planning advice, prepares tax returns, and represents clients before the tax authorities.
</p>
</details>

<details data-terms="numero identificacion fiscal nif tax identification number spanish dni cif">
<summary>NIF (Número de Identificación Fiscal)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Tax Identification Number</strong>. The general term for tax ID in Spain. For Spanish nationals, it's their DNI; for foreigners, it's their NIE; for companies, it's their CIF.
</p>
</details>

<details data-terms="cif codigo identificacion fiscal company tax number business vat">
<summary>CIF (Código de Identificación Fiscal)</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Company Tax Identification Code</strong>. The tax ID number assigned to Spanish companies and legal entities. Now technically replaced by NIF but still commonly used.
</p>
</details>

<details data-terms="iban international bank account number cuenta bancaria swift bic">
<summary>IBAN</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>International Bank Account Number</strong>. The standardized format for Spanish bank accounts (24 characters starting with ES), required for all domestic and international transfers, direct debits, and salary payments.
</p>
</details>

<details data-terms="certificado bancario bank certificate saldo balance account proof funds">
<summary>Certificado Bancario</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Bank Certificate</strong>. An official document from your bank confirming account ownership, balance, or transaction history. Required for many visa applications and property purchases.
</p>
</details>

<details data-terms="tributacion taxation tax system fiscal regime liability">
<summary>Tributación</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Taxation</strong> or the tax system. The overall framework of tax laws, regulations, and procedures that govern how individuals and entities pay taxes in Spain.
</p>
</details>

<details data-terms="tipo impositivo tax rate percentage bracket marginal progressive">
<summary>Tipo Impositivo</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Tax Rate</strong>. The percentage applied to taxable income or value. Spain uses progressive rates for IRPF (19-47%) and flat rates for certain taxes like IRNR (19-24%).
</p>
</details>

<details data-terms="base imponible taxable base income amount calculation deductions">
<summary>Base Imponible</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Taxable Base</strong>. The amount of income or value upon which tax is calculated, after applying allowable deductions and exemptions.
</p>
</details>

<details data-terms="comunidad autonoma autonomous community regional government taxes education healthcare">
<summary>Comunidad Autónoma</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Autonomous Community</strong>. Spain's 17 regional governments with significant powers over taxation (wealth tax, inheritance tax), healthcare, education, and other services. Rates and rules vary widely.
</p>
</details>

<details data-terms="embargo attachment seizure lien debt collection execution judicial">
<summary>Embargo</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Attachment or Seizure</strong>. Legal action to freeze or seize assets (bank accounts, property, salary) to satisfy unpaid debts, particularly tax debts or court judgments.
</p>
</details>

<details data-terms="aplazamiento pago payment plan installments deferral tax debt spread">
<summary>Aplazamiento de Pago</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Payment Deferral</strong> or installment plan. An arrangement with the tax authorities to spread payment of tax debts over time, typically requiring collateral for amounts over €30,000.
</p>
</details>

<details data-terms="prescripcion statute limitations tax debt expiry time limit four years">
<summary>Prescripción</summary>
<p>
<span style="font-weight: 600;">Definition:</span> <strong>Statute of Limitations</strong>. The time limit for tax authorities to audit or claim unpaid taxes (typically 4 years) or for taxpayers to claim refunds. Once expired, debts or claims are no longer valid.
</p>
</details>

</div>

<script>
(function() {
    const searchInput = document.getElementById('searchInput');
    const noResults = document.getElementById('noResults');
    const visibleCountSpan = document.getElementById('visibleCount');
    const totalCountSpan = document.getElementById('totalCount');
    const statsDiv = document.getElementById('stats');
    const allDetails = document.querySelectorAll('.glossary-section details');
    const allSections = document.querySelectorAll('.section-header');
    
    // Set total count on load
    const totalCount = allDetails.length;
    totalCountSpan.textContent = totalCount;
    
    function performSearch() {
        const searchTerm = searchInput.value.toLowerCase().trim();
        let visibleCount = 0;
        
        // Show all if search is empty
        if (searchTerm === '') {
            allDetails.forEach(detail => {
                detail.style.display = '';
            });
            allSections.forEach(section => {
                section.style.display = '';
            });
            noResults.classList.remove('show');
            statsDiv.style.display = 'block';
            visibleCountSpan.textContent = totalCount;
            return;
        }
        
        // Search through details
        allDetails.forEach(detail => {
            const summary = detail.querySelector('summary').textContent.toLowerCase();
            const content = detail.querySelector('p').textContent.toLowerCase();
            const dataTerms = detail.getAttribute('data-terms') || '';
            
            const matches = summary.includes(searchTerm) || 
                          content.includes(searchTerm) || 
                          dataTerms.includes(searchTerm);
            
            if (matches) {
                detail.style.display = '';
                visibleCount++;
            } else {
                detail.style.display = 'none';
            }
        });
        
        // Hide section headers if no results in that section
        allSections.forEach(section => {
            const nextSection = section.nextElementSibling;
            if (nextSection && nextSection.classList.contains('glossary-section')) {
                const visibleInSection = Array.from(nextSection.querySelectorAll('details'))
                    .some(detail => detail.style.display !== 'none');
                section.style.display = visibleInSection ? '' : 'none';
            }
        });
        
        // Update stats and show/hide no results message
        visibleCountSpan.textContent = visibleCount;
        if (visibleCount === 0) {
            noResults.classList.add('show');
            statsDiv.style.display = 'none';
        } else {
            noResults.classList.remove('show');
            statsDiv.style.display = 'block';
        }
    }
    
    // Debounce search for performance
    let searchTimeout;
    searchInput.addEventListener('input', function() {
        clearTimeout(searchTimeout);
        searchTimeout = setTimeout(performSearch, 300);
    });
    
    // Allow Enter key to search immediately
    searchInput.addEventListener('keypress', function(e) {
        if (e.key === 'Enter') {
            clearTimeout(searchTimeout);
            performSearch();
        }
    });
})();
</script>
