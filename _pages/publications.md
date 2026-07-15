---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
/* --- 1. GLOBAL VARIABLES & TYPOGRAPHY --- */
:root {
  --primary-color: #0f172a; 
  --accent-color: #0284c7; 
  --accent-light: #e0f2fe;
  --text-color: #334155; 
  --bg-light: #f8fafc; 
  --border-color: #e2e8f0;
}

.archive {
  font-size: 1.05em;
}

/* --- 2. AUTHORSHIP LEGEND --- */
.pub-legend {
  background-color: var(--bg-light);
  border: 1px solid var(--border-color);
  border-radius: 6px;
  padding: 12px 20px;
  margin-bottom: 30px;
  display: flex;
  gap: 20px;
  font-size: 0.9em;
  color: var(--text-color);
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
}

.pub-legend span {
  display: flex;
  align-items: center;
  gap: 6px;
}

.pub-legend strong {
  color: var(--primary-color);
}

/* --- 3. SECTION HEADERS --- */
.research-area {
  margin-bottom: 25px;
  background-color: transparent;
}

.area-header {
  padding: 22px 25px;
  cursor: pointer;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: var(--bg-light);
  border-radius: 8px; 
  transition: background-color 0.2s, transform 0.2s, box-shadow 0.2s;
  border-left: 6px solid var(--accent-color);
  border-top: 1px solid var(--border-color);
  border-right: 1px solid var(--border-color);
  border-bottom: 1px solid var(--border-color);
}

.area-header:hover {
  background-color: #ffffff;
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.04);
}

.area-header h2 {
  margin: 0;
  color: var(--primary-color);
  font-weight: 700;
  font-size: 1.4em;
  letter-spacing: -0.01em;
}

.area-subtitle {
  color: #64748b;
  font-size: 0.95em;
  margin-top: 6px;
  font-weight: 500;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
}

/* --- 4. PAPER "CARDS" --- */
.area-content {
  padding: 10px 5px;
  max-height: 5000px;
  transition: max-height 0.5s cubic-bezier(0, 1, 0, 1);
  overflow: hidden;
}

.collapsed .area-content {
  max-height: 0;
  padding: 0 5px;
}

.paper {
  background: #ffffff;
  margin-bottom: 15px;
  padding: 22px 25px;
  border-radius: 6px;
  border: 1px solid var(--border-color);
  box-shadow: 0 2px 4px rgba(0,0,0,0.02);
  transition: all 0.2s ease;
  position: relative;
}

.paper:hover {
  border-color: #cbd5e1;
  box-shadow: 0 6px 15px rgba(0, 0, 0, 0.05);
  transform: translateY(-2px); 
}

.paper-title {
  font-size: 1.15em;
  font-weight: 600;
  color: var(--primary-color);
  line-height: 1.4;
  margin-bottom: 8px;
}

.paper-authors {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  font-size: 0.95em;
  color: var(--text-color);
  margin-bottom: 6px;
  line-height: 1.5;
}

.paper-authors strong {
  color: var(--primary-color);
  font-weight: 700;
}

.paper-journal {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  font-size: 0.95em;
  color: #64748b;
}

.paper-journal em {
  color: var(--primary-color);
  font-weight: 500;
  font-style: normal;
}

.paper-commentary {
  margin-top: 10px;
  padding: 8px 12px;
  background-color: #fffbeb;
  border-left: 3px solid #f59e0b;
  font-size: 0.85em;
  color: #92400e;
  border-radius: 0 4px 4px 0;
}

/* --- 5. ICONS & UX --- */
.collapse-icon {
  font-size: 18px;
  color: var(--accent-color);
  transition: transform 0.3s ease;
}

.collapsed .collapse-icon {
  transform: rotate(-90deg);
}
</style>

<script>
function toggleSection(sectionId) {
  const section = document.getElementById(sectionId);
  section.classList.toggle('collapsed');
}
</script>

<div class="pub-legend">
  <span><strong>*</strong> Co-first author</span>
  <span><strong>†</strong> Corresponding author</span>
</div>

<!-- SECTION 1: PHYSIOLOGY & AGING (Opened by default) -->
<div id="physiology" class="research-area">
  <div class="area-header" onclick="toggleSection('physiology')">
    <div>
      <h2>Viral impacts on host physiology</h2>
      <div class="area-subtitle">Aging processes, developmental programs, and metabolic homeostasis</div>
    </div>
    <span class="collapse-icon">▼</span>
  </div>
  <div class="area-content">
    
    <div class="paper">
      <div class="paper-title">Enteric viral infections promote systemic accelerated aging in <em>Drosophila</em></div>
      <div class="paper-authors"><strong>González R†</strong>, Castelló-Sanjuán M, Saleh MC†</div>
      <div class="paper-journal"><em>Science Advances</em> (2025) 12:eaec1735</div>
    </div>

    <div class="paper">
      <div class="paper-title">Persistent viral infections impact key biological traits in <em>Drosophila melanogaster</em></div>
      <div class="paper-authors">Castelló-Sanjuán M, <strong>González R</strong>, Romoli O, Blanc H, Nigg J, Saleh MC†</div>
      <div class="paper-journal"><em>PLoS Biology</em> (2025) 23:e3003437</div>
    </div>

    <div class="paper">
      <div class="paper-title">The pupal stage is a developmental window for RNA virus persistence in <em>Drosophila</em></div>
      <div class="paper-authors">Castelló-Sanjuán M, <strong>González R</strong>, Bergman A, Blanc H, Frangeul L, Nigg J, Saleh MC†</div>
      <div class="paper-journal"><em>bioRxiv</em> (2025) 2025.11.07.687216</div>
    </div>

    <div class="paper">
      <div class="paper-title">The interplay between <em>Caenorhabditis elegans</em> larval development and Orsay virus infection</div>
      <div class="paper-authors">Melero I†, Castiglioni VG, Olmo-Uceda MJ, Olmedo M, <strong>González R†</strong>, Elena SF†</div>
      <div class="paper-journal"><em>iScience</em> (2025) 28:114193</div>
    </div>

    <div class="paper">
      <div class="paper-title">Transcriptional and hormonal profiling uncovers the interactions between plant developmental stages and RNA virus infection</div>
      <div class="paper-authors">Melero I, Gómez-Cadenas A, <strong>González R†</strong>, Elena SF†</div>
      <div class="paper-journal"><em>Journal of General Virology</em> (2024) 105:002023</div>
    </div>

    <div class="paper">
      <div class="paper-title">Viral strain-dependent impact of plant developmental stages on the nestedness and modularity of plant-virus interaction matrices</div>
      <div class="paper-authors">Melero I, Elena SF, <strong>González R†</strong></div>
      <div class="paper-journal"><em>microPublication Biology</em> (2023) 10.17912/micropub.biology.000943</div>
    </div>

    <div class="paper">
      <div class="paper-title">Host developmental stages shape the evolution of a plant RNA virus</div>
      <div class="paper-authors">Melero I, <strong>González R†</strong>, Elena SF†</div>
      <div class="paper-journal"><em>Philosophical Transactions of the Royal Society B</em> (2023) 378:20220005</div>
    </div>

    <div class="paper">
      <div class="paper-title">From foes to friends: viral infections expand the limits of host phenotypic plasticity</div>
      <div class="paper-authors"><strong>González R*†</strong>, Butković A*, Elena SF†</div>
      <div class="paper-journal"><em>Advances in Virus Research</em> (2020) 106:85-121</div>
    </div>

  </div>
</div>

<!-- SECTION 2: ENVIRONMENT & MICROBIOME -->
<div id="environment" class="research-area collapsed">
  <div class="area-header" onclick="toggleSection('environment')">
    <div>
      <h2>Environmental modulation of infections</h2>
      <div class="area-subtitle">Impact of the microbiome, space conditions, and abiotic factors</div>
    </div>
    <span class="collapse-icon">▼</span>
  </div>
  <div class="area-content">

    <div class="paper">
      <div class="paper-title">Microbiome composition modulates the lethal outcome of <em>Drosophila</em> A virus infection</div>
      <div class="paper-authors"><strong>González R†</strong>, Castelló-Sanjuán M, Romoli O, Blanc H, Kobayashi H, Nigg J, Saleh MC†</div>
      <div class="paper-journal"><em>Cellular and Molecular Life Sciences</em> (2025) 83:61</div>
    </div>

    <div class="paper">
      <div class="paper-title">Cosmic silence and viral noise: transcriptomic crosstalk in <em>Caenorhabditis elegans</em> under simulated space conditions</div>
      <div class="paper-authors">Villena-Giménez A*, Legarda EG*, <strong>González R</strong>, Castiglioni VG, Elena SF†</div>
      <div class="paper-journal"><em>Frontiers in Microbiology</em> (2025) 17:1781245</div>
    </div>

    <div class="paper">
      <div class="paper-title">Reduced gravity and muon flux absence affect <em>Caenorhabditis elegans</em> life history traits and viral infection</div>
      <div class="paper-authors">Villena-Giménez A, Castiglioni VG, Legarda EG, Muñoz-Sánchez JC, <strong>González R</strong>, Elena SF†</div>
      <div class="paper-journal"><em>Microbiology Spectrum</em> (2024) 14:e03580-25</div>
    </div>

    <div class="paper">
      <div class="paper-title">Natural monobacterial environments modulate viral infection in <em>Caenorhabditis elegans</em></div>
      <div class="paper-authors"><strong>González R†</strong>, Félix M-A†</div>
      <div class="paper-journal"><em>PLoS Pathogens</em> (2024) 20:e1011947</div>
    </div>

    <div class="paper">
      <div class="paper-title">The interplay between the host microbiome and pathogenic viral infections</div>
      <div class="paper-authors"><strong>González R†</strong>, Elena SF</div>
      <div class="paper-journal"><em>mBio</em> (2021) 12:e02496-21</div>
    </div>

  </div>
</div>

<!-- SECTION 3: VIRUS EVOLUTION -->
<div id="evolution" class="research-area collapsed">
  <div class="area-header" onclick="toggleSection('evolution')">
    <div>
      <h2>Virus evolution</h2>
      <div class="area-subtitle">Molecular evolutionary dynamics, selective pressures, and phylogenetics</div>
    </div>
    <span class="collapse-icon">▼</span>
  </div>
  <div class="area-content">

    <div class="paper">
      <div class="paper-title">Experimental evolution of an RNA virus in <em>Caenorhabditis elegans</em></div>
      <div class="paper-authors">Castiglioni VG, Olmo-Uceda MJ, Martín S, Félix M-A, <strong>González R†</strong>, Elena SF†</div>
      <div class="paper-journal"><em>Infection, Genetics and Evolution</em> (2024) 123:105623</div>
    </div>

    <div class="paper">
      <div class="paper-title">A brief view on factors that affect plant virus evolution</div>
      <div class="paper-authors">Butković A*†, <strong>González R*†</strong></div>
      <div class="paper-journal"><em>Frontiers in Virology</em> (2022) 2:994057</div>
    </div>

    <div class="paper">
      <div class="paper-title">Defects in plant immunity modulate the rates and patterns of RNA virus evolution</div>
      <div class="paper-authors">Navarro R, Ambrós S, Butković A, Carrasco JL, <strong>González R</strong>, Martínez F, Wu B, Elena SF†</div>
      <div class="paper-journal"><em>Virus Evolution</em> (2022) veac059</div>
    </div>

    <div class="paper">
      <div class="paper-title">Plant virus evolution under strong drought conditions results in a transition from parasitism to mutualism</div>
      <div class="paper-authors"><strong>González R</strong>, Butković A, Escaray F, Martínez-Latorre J, Melero I, Pérez-Parets E, Gómez-Cadenas A, Carrasco P, Elena SF†</div>
      <div class="paper-journal"><em>PNAS</em> (2021) 118:e2020990118</div>
      <div class="paper-commentary">Highlighted in PNAS Commentary: <em>Rapid emergence of virus-host mutualism under stress</em> (Dolja VV, e2100936118)</div>
    </div>

    <div class="paper">
      <div class="paper-title">Revisiting <em>Orthotospovirus</em> phylogeny using full-genome data and testing the contribution of selection, recombination and segments reassortment in the origin of new species</div>
      <div class="paper-authors">Butković A, <strong>González R</strong>, Elena SF†</div>
      <div class="paper-journal"><em>Archives of Virology</em> (2021) 166:491–499</div>
    </div>

    <div class="paper">
      <div class="paper-title">Adaptation of turnip mosaic potyvirus to a specific niche reduces its genetic and environmental robustness</div>
      <div class="paper-authors">Butković A, <strong>González R</strong>, Cobo I, Elena SF†</div>
      <div class="paper-journal"><em>Virus Evolution</em> (2020) 6:veaa041</div>
    </div>

    <div class="paper">
      <div class="paper-title">Role of host genetic diversity for susceptibility-to-infection in the evolution of virulence of a plant virus</div>
      <div class="paper-authors"><strong>González R</strong>, Butković A, Elena SF†</div>
      <div class="paper-journal"><em>Virus Evolution</em> (2019) 5:vez024</div>
    </div>

    <div class="paper">
      <div class="paper-title">Mutagenesis scanning uncovers evolutionary constraints on tobacco etch potyvirus membrane-associated 6K2 protein</div>
      <div class="paper-authors"><strong>González R*</strong>, Wu B*, Li X*, Martínez F†, Elena SF†</div>
      <div class="paper-journal"><em>Genome Biology and Evolution</em> (2019) 11:1207–1222</div>
    </div>

  </div>
</div>

<!-- SECTION 4: GENETICS -->
<div id="genetics" class="research-area collapsed">
  <div class="area-header" onclick="toggleSection('genetics')">
    <div>
      <h2>Genetic architecture of host-virus interactions</h2>
      <div class="area-subtitle">Genetics of antiviral immunity and susceptibility factors</div>
    </div>
    <span class="collapse-icon">▼</span>
  </div>
  <div class="area-content">

    <div class="paper">
      <div class="paper-title"><em>Caenorhabditis elegans</em> immune responses to intracellular pathogens</div>
      <div class="paper-authors"><strong>González R†</strong>, Félix M-A</div>
      <div class="paper-journal"><em>Developmental & Comparative Immunology</em> (2024) 154:105148</div>
    </div>

    <div class="paper">
      <div class="paper-title"><em>Caenorhabditis elegans</em> defective-pharynx and constipated mutants are resistant to Orsay virus infection</div>
      <div class="paper-authors"><strong>González R†</strong>, Félix M-A†</div>
      <div class="paper-journal"><em>microPublication Biology</em> (2024) 10.17912/micropub.biology.001166</div>
    </div>

    <div class="paper">
      <div class="paper-title">Genetic basis of <em>Arabidopsis thaliana</em> responses to infection by naïve and adapted isolates of turnip mosaic virus</div>
      <div class="paper-authors">Butković A*, Ellis TJ*, <strong>González R*</strong>, Jaegle B, Nordborg M†, Elena SF†</div>
      <div class="paper-journal"><em>eLife</em> (2023) 12:RP89749</div>
    </div>

    <div class="paper">
      <div class="paper-title">A genome-wide association study identifies <em>Arabidopsis thaliana</em> genes that contribute to differences in the outcome of infection with two Turnip mosaic potyvirus strains</div>
      <div class="paper-authors">Butković A, <strong>González R</strong>, Rivarez MPS, Elena SF†</div>
      <div class="paper-journal"><em>Virus Evolution</em> (2020) veab063</div>
    </div>

  </div>
</div>

<!-- SECTION 5: OTHER -->
<div id="other" class="research-area collapsed">
  <div class="area-header" onclick="toggleSection('other')">
    <div>
      <h2>Other contributions</h2>
      <div class="area-subtitle">Additional research and scientific communications</div>
    </div>
    <span class="collapse-icon">▼</span>
  </div>
  <div class="area-content">

    <div class="paper">
      <div class="paper-title">A look back at the departmental Virology Days of the Institut Pasteur (Le Touquet, May 13-15, 2024)</div>
      <div class="paper-authors"><strong>González R*</strong>, Koh C*, Virlon B*, Merkling SH†, Vartanian JP†</div>
      <div class="paper-journal"><em>Journal of Molecular Cell Biology</em> (2025) mjae052</div>
    </div>

    <div class="paper">
      <div class="paper-title">Natural variation in <em>Arabidopsis thaliana</em> rosette area unveils new genes involved in plant development</div>
      <div class="paper-authors"><strong>González R†</strong>, Butković A, Rivarez MPS, Elena SF</div>
      <div class="paper-journal"><em>Scientific Reports</em> (2020) 10:17600</div>
    </div>

    <div class="paper">
      <div class="paper-title">The scale-of-choice effect and how estimates of assortative mating in the wild can be biased due to heterogeneous samples</div>
      <div class="paper-authors">Rolán-Alvarez E†, Carvajal-Rodríguez A, de Coo A, Cortés B, Estévez D, Ferreira M, <strong>González R</strong>, Briscoe AD</div>
      <div class="paper-journal"><em>Evolution</em> (2015) 69:1845–1857</div>
    </div>

  </div>
</div>

<p style="text-align: center; margin: 50px 0; color: #94a3b8; font-size: 0.85em;">Updated July 2026</p>

```
