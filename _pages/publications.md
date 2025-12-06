---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

<style>
/* --- General Layout --- */
.research-area {
    margin-bottom: 25px;
    border-radius: 8px;
    overflow: hidden;
    background-color: #ffffff;
    box-shadow: 0 1px 3px rgba(0,0,0,0.08);
    border: 1px solid #e1e4e8;
}

/* --- Header Styling --- */
.area-header {
    padding: 20px 25px;
    cursor: pointer;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #f8f9fa;
    transition: background-color 0.2s;
    border-bottom: 1px solid transparent;
}
.area-header:hover {
    background-color: #f1f3f4;
}
.area-header h2 {
    margin: 0;
    color: #1a73e8;
    font-weight: 600;
    font-size: 1.4em;
    letter-spacing: -0.01em;
}
.area-subtitle {
    color: #5f6368;
    font-style: normal;
    margin-top: 4px;
    font-size: 0.9em;
    line-height: 1.4;
    max-width: 90%;
}

/* --- Collapse Icon Logic --- */
.collapse-icon {
    font-size: 18px;
    color: #1a73e8;
    transition: transform 0.3s;
    opacity: 0.7;
}
.collapsed .collapse-icon {
    transform: rotate(-90deg);
}

/* --- Content Area --- */
.area-content {
    padding: 0 25px 25px 25px;
    max-height: 10000px; /* Arbitrary large height for animation */
    transition: max-height 0.4s ease-out, padding 0.4s ease;
    background-color: #ffffff;
    border-top: 1px solid #e1e4e8;
}
.collapsed .area-content {
    max-height: 0;
    padding: 0 25px;
    overflow: hidden;
    border-top: none;
}

/* --- Individual Paper Card --- */
.paper {
    margin-top: 20px;
    padding-bottom: 20px;
    border-bottom: 1px solid #f0f0f0;
}
.paper:last-child {
    border-bottom: none;
    padding-bottom: 0;
}
.paper-title {
    font-size: 1.05em;
    font-weight: 600;
    margin-bottom: 6px;
    line-height: 1.4;
    color: #202124;
}
.paper-meta {
    font-size: 0.9em;
    color: #444;
    margin-bottom: 8px;
}
.paper-meta a {
    color: #1a73e8;
    text-decoration: none;
    font-weight: 500;
    margin-left: 5px;
}
.paper-meta a:hover {
    text-decoration: underline;
}
.paper-description {
    font-size: 0.95em;
    line-height: 1.5;
    color: #5f6368;
}

/* --- Badges for Authorship --- */
.badge {
    display: inline-block;
    padding: 2px 8px;
    border-radius: 12px;
    font-size: 0.7em;
    font-weight: 700;
    margin: 0 2px;
    vertical-align: middle;
    text-transform: uppercase;
    letter-spacing: 0.3px;
}
.badge-first {
    background-color: #e8f0fe;
    color: #1967d2;
    border: 1px solid #d2e3fc;
}
.badge-corr {
    background-color: #fce8e6;
    color: #c5221f;
    border: 1px solid #fad2cf;
}

/* --- Intro Box --- */
.intro-box {
    background-color: #e8f0fe;
    padding: 20px 25px;
    border-radius: 8px;
    margin-bottom: 30px;
    border-left: 5px solid #1a73e8;
}
.intro-box p {
    font-size: 1.05em;
    line-height: 1.6;
    color: #3c4043;
    margin: 0;
}

/* --- Special Style for Highlights --- */
.highlight-section {
    border-left: 5px solid #fbbc04 !important;
    background-color: #fff !important;
}
.highlight-section .area-header {
    background-color: #fffcf5 !important;
}
.highlight-paper {
    background-color: #fffcf5;
    padding: 15px;
    border-radius: 8px;
    border: 1px solid #fef0cd;
    margin-top: 15px;
}
.commentary-link {
    display: inline-block;
    background-color: #e8f0fe;
    color: #1967d2;
    padding: 1px 8px;
    border-radius: 4px;
    font-size: 0.75em;
    margin-left: 8px;
    font-weight: 500;
    text-decoration: none;
    vertical-align: middle;
}
</style>

<script>
function toggleSection(sectionId) {
    const section = document.getElementById(sectionId);
    section.classList.toggle('collapsed');
}
</script>

<div class="intro-box">
<p>
My research investigates the fundamental principles governing host-pathogen interactions across model systems. By integrating evolutionary biology, molecular virology, and systems approaches, we uncover how viruses evolve, impact host biology, and interact with environmental factors to shape infection outcomes.
</p>
</div>

<div class="research-area highlight-section">
    <div class="area-header" style="cursor: default;">
        <div>
            <h2 style="color: #202124;">Selected Highlights</h2>
            <p class="area-subtitle">Key contributions to aging, environmental modulation, and virus evolution</p>
        </div>
    </div>
    <div class="area-content" style="max-height: none; padding-bottom: 20px;">
        
        <div class="paper highlight-paper">
            <div class="paper-title">Viral infections reduce <em>Drosophila</em> lifespan through accelerated aging</div>
            <div class="paper-meta">González R <span class="badge badge-first">First</span> et al. • <em>bioRxiv</em> 2025 • <a href="https://doi.org/10.1101/2025.03.13.643076">Link</a></div>
            <div class="paper-description">We demonstrate that enteric viral infections trigger irreversible aging processes that persist even after the infection is cleared, providing a direct link between viral history and lifespan reduction.</div>
        </div>

        <div class="paper highlight-paper">
            <div class="paper-title">Natural monobacterial environments modulate viral infection in <em>C. elegans</em></div>
            <div class="paper-meta">González R <span class="badge badge-first">Co-First</span> <span class="badge badge-corr">Corr.</span> & Félix M-A <span class="badge badge-corr">Corr.</span> • <em>PLoS Pathog</em> 2024 • <a href="https://doi.org/10.1371/journal.ppat.1011947">Link</a></div>
            <div class="paper-description">Discovery that specific natural bacteria can reduce viral susceptibility in nematodes through a novel DRH-1-dependent mechanism, independent of virion degradation.</div>
        </div>

        <div class="paper highlight-paper">
            <div class="paper-title">Plant virus evolution under strong drought conditions results in a transition from parasitism to mutualism</div>
            <div class="paper-meta">González R <span class="badge badge-first">First</span> et al. • <em>PNAS</em> 2021 • <a href="https://doi.org/10.1073/pnas.2020990118">Link</a></div>
            <div class="paper-description">Showed that under severe environmental stress, virus evolution can shift from parasitic to mutualistic, conferring drought tolerance to the host.</div>
        </div>

    </div>
</div>

<div id="evolution" class="research-area">
    <div class="area-header" onclick="toggleSection('evolution')">
        <div>
            <h2>Virus evolution</h2>
            <p class="area-subtitle">Molecular evolutionary dynamics, selective pressures, and transmission bottlenecks</p>
        </div>
        <span class="collapse-icon">▼</span>
    </div>
    <div class="area-content">
        
        <div class="paper">
            <div class="paper-title">Experimental evolution of an RNA virus in <em>Caenorhabditis elegans</em></div>
            <div class="paper-meta">Castiglioni VG et al. • <em>Infect Genet Evol</em> 2024 • <a href="https://doi.org/10.1016/j.meegid.2024.105623">Link</a></div>
            <div class="paper-description">Identified genomic hotspots of nucleotide diversity important for Orsay virus evolution, establishing grounds for experimental virus evolution studies in nematodes.</div>
        </div>

        <div class="paper">
            <div class="paper-title">A brief view on factors that affect plant virus evolution</div>
            <div class="paper-meta">González R <span class="badge badge-first">Co-First</span> <span class="badge badge-corr">Corr.</span> & Butkovic A <span class="badge badge-first">Co-First</span> <span class="badge badge-corr">Corr.</span> • <em>Front Virol</em> 2022 • <a href="https://doi.org/10.3389/fviro.2022.994057">Link</a></div>
            <div class="paper-description">Comprehensive minireview of key factors driving plant virus evolution.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Defects in plant immunity modulate the rates and patterns of RNA virus evolution</div>
            <div class="paper-meta">Navarro R et al. • <em>Virus Evol</em> 2022 • <a href="https://doi.org/10.1093/ve/veac059">Link</a></div>
            <div class="paper-description">Different host defense signaling pathways constrain virus evolution in distinct ways.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Plant virus evolution under strong drought conditions results in a transition from parasitism to mutualism <a href="https://www.pnas.org/doi/10.1073/pnas.2100936118" class="commentary-link">Commentary</a></div>
            <div class="paper-meta">González R et al. • <em>PNAS</em> 2021 • <a href="https://doi.org/10.1073/pnas.2020990118">Link</a></div>
            <div class="paper-description">Demonstrated that environmental stress can drive viruses to evolve beneficial relationships with their hosts.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Revisiting <em>Orthotospovirus</em> phylogeny using full-genome data</div>
            <div class="paper-meta">Butkovic A et al. • <em>Arch Virol</em> 2021 • <a href="https://doi.org/10.1007/s00705-020-04902-1">Link</a></div>
            <div class="paper-description">Updated phylogenetic analysis incorporating selection, recombination, and reassortment.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Adaptation of turnip mosaic potyvirus to a specific niche reduces its genetic and environmental robustness</div>
            <div class="paper-meta">Butkovic A et al. • <em>Virus Evol</em> 2020 • <a href="https://doi.org/10.1093/ve/veaa041">Link</a></div>
            <div class="paper-description">Highly adapted viruses are more sensitive to random mutations and temperature changes.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Role of host genetic diversity for susceptibility-to-infection in the evolution of virulence of a plant virus</div>
            <div class="paper-meta">González R et al. • <em>Virus Evol</em> 2019 • <a href="https://doi.org/10.1093/ve/vez024">Link</a></div>
            <div class="paper-description">Viruses specialize faster in homogeneous host populations but become more pathogenic in heterogeneous ones.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Mutagenesis scanning uncovers evolutionary constraints on tobacco etch potyvirus membrane-associated 6K2 protein</div>
            <div class="paper-meta">González R <span class="badge badge-first">Co-First</span> et al. • <em>Genome Biol Evol</em> 2019 • <a href="https://doi.org/10.1093/gbe/evz069">Link</a></div>
            <div class="paper-description">Revealed evolutionary tradeoffs between within-host viral accumulation and symptom severity.</div>
        </div>
    </div>
</div>

<div id="physiology" class="research-area collapsed">
    <div class="area-header" onclick="toggleSection('physiology')">
        <div>
            <h2>Viral impacts on host physiology</h2>
            <p class="area-subtitle">Developmental programs, metabolic homeostasis, and aging processes</p>
        </div>
        <span class="collapse-icon">▼</span>
    </div>
    <div class="area-content">
        
        <div class="paper">
            <div class="paper-title">Viral infections reduce <em>Drosophila</em> lifespan through accelerated aging</div>
            <div class="paper-meta">González R et al. • <em>bioRxiv</em> 2025 • <a href="https://doi.org/10.1101/2025.03.13.643076">Link</a></div>
            <div class="paper-description">Enteric viral infections trigger irreversible aging processes that persist even after infection clearance.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Persistent viral infections impact key biological traits in <em>Drosophila melanogaster</em></div>
            <div class="paper-meta">Castelló-Sanuán M et al. • <em>bioRxiv</em> 2025 • <a href="https://doi.org/10.1101/2025.03.12.642769">Link</a></div>
            <div class="paper-description">Comprehensive characterization of how persistent viral infections affect insect biology.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Transcriptional and hormonal profiling uncovers plant development-virus interactions</div>
            <div class="paper-meta">Melero I et al. • <em>J Gen Virol</em> 2024 • <a href="https://doi.org/10.1099/jgv.0.002023">Link</a></div>
            <div class="paper-description">Plants downregulate cell wall genes to facilitate viral spread but maintain fertility through resistance tradeoffs.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Host developmental stages shape the evolution of a plant RNA virus</div>
            <div class="paper-meta">Melero I et al. • <em>Phil Trans R Soc B</em> 2023 • <a href="https://doi.org/10.1098/rtsb.2022.0005">Link</a></div>
            <div class="paper-description">TuMV evolution differs across three developmental stages of <em>Arabidopsis thaliana</em>.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Viral strain-dependent impact of plant developmental stages on interaction networks</div>
            <div class="paper-meta">Melero I et al. • <em>microPubl Biol</em> 2023 • <a href="https://doi.org/10.17912/micropub.biology.000943">Link</a></div>
            <div class="paper-description">Ancestral viral adaptation history influences future evolution under developmental constraints.</div>
        </div>

        <div class="paper">
            <div class="paper-title">From foes to friends: viral infections expand host phenotypic plasticity</div>
            <div class="paper-meta">González R <span class="badge badge-first">Co-First</span> <span class="badge badge-corr">Corr.</span> et al. • <em>Adv Virus Res</em> 2020 • <a href="https://doi.org/10.1016/bs.aivir.2020.01.003">Link</a></div>
            <div class="paper-description">Review: viruses can enhance host survival under environmental stress by altering phenotypic plasticity.</div>
        </div>
    </div>
</div>

<div id="genetics" class="research-area collapsed">
    <div class="area-header" onclick="toggleSection('genetics')">
        <div>
            <h2>Genetic architecture of host-virus interactions</h2>
            <p class="area-subtitle">Genetics of antiviral immunity and susceptibility factors</p>
        </div>
        <span class="collapse-icon">▼</span>
    </div>
    <div class="area-content">
        
        <div class="paper">
            <div class="paper-title">Genetic basis of <em>Arabidopsis thaliana</em> responses to turnip mosaic virus</div>
            <div class="paper-meta">Butkovic A <span class="badge badge-first">Co-First</span> et al. • <em>eLife</em> 2024 • <a href="https://doi.org/10.7554/eLife.89749.1">Link</a></div>
            <div class="paper-description">Identified genetic underpinnings of plant resistance to naïve and adapted viral isolates.</div>
        </div>

        <div class="paper">
            <div class="paper-title"><em>Caenorhabditis elegans</em> immune responses to intracellular pathogens</div>
            <div class="paper-meta">González R <span class="badge badge-corr">Corr.</span> & Félix M-A • <em>Dev Comp Immunol</em> 2024 • <a href="https://doi.org/10.1016/j.dci.2024.105148">Link</a></div>
            <div class="paper-description">Review of nematode responses to microsporidia and viruses.</div>
        </div>

        <div class="paper">
            <div class="paper-title"><em>C. elegans</em> pharynx mutants resist Orsay virus infection</div>
            <div class="paper-meta">González R <span class="badge badge-corr">Corr.</span> & Félix M-A • <em>microPubl Biol</em> 2024 • <a href="https://doi.org/10.17912/micropub.biology.001166">Link</a></div>
            <div class="paper-description">Identified specific mutants conferring viral resistance.</div>
        </div>

        <div class="paper">
            <div class="paper-title">GWAS identifies <em>Arabidopsis</em> genes affecting TuMV infection outcomes</div>
            <div class="paper-meta">Butković A et al. • <em>Virus Evol</em> 2021 • <a href="https://doi.org/10.1093/ve/veab063">Link</a></div>
            <div class="paper-description">Genome-wide study revealing new host genes involved in plant defense and virus replication.</div>
        </div>
    </div>
</div>

<div id="environment" class="research-area collapsed">
    <div class="area-header" onclick="toggleSection('environment')">
        <div>
            <h2>Environmental modulation of host-virus interactions</h2>
            <p class="area-subtitle">Impact of abiotic factors and microbiome on infection dynamics</p>
        </div>
        <span class="collapse-icon">▼</span>
    </div>
    <div class="area-content">
        
        <div class="paper">
            <div class="paper-title">Microgravity and low muon radiation affect viral pathogenesis in <em>C. elegans</em></div>
            <div class="paper-meta">Villena-Giménez A et al. • <em>bioRxiv</em> 2024 • <a href="https://doi.org/10.1101/2024.10.03.616447">Link</a></div>
            <div class="paper-description">Space-like conditions impact fecundity and developmental success in infected animals.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Natural monobacterial environments modulate viral infection in <em>C. elegans</em></div>
            <div class="paper-meta">González R <span class="badge badge-corr">Corr.</span> & Félix M-A <span class="badge badge-corr">Corr.</span> • <em>PLoS Pathog</em> 2024 • <a href="https://doi.org/10.1371/journal.ppat.1011947">Link</a></div>
            <div class="paper-description">Natural bacteria reduce viral susceptibility through novel DRH-1-dependent mechanisms.</div>
        </div>

        <div class="paper">
            <div class="paper-title">The interplay between the host microbiome and pathogenic viral infections</div>
            <div class="paper-meta">González R <span class="badge badge-corr">Corr.</span> & Elena SF • <em>mBio</em> 2021 • <a href="https://doi.org/10.1128/mBio.02496-21">Link</a></div>
            <div class="paper-description">Integrative review of microbiome impacts on viral infections across pathosystems.</div>
        </div>
    </div>
</div>

<div id="other" class="research-area collapsed">
    <div class="area-header" onclick="toggleSection('other')">
        <div>
            <h2>Other contributions</h2>
            <p class="area-subtitle">Additional research and scientific communications</p>
        </div>
        <span class="collapse-icon">▼</span>
    </div>
    <div class="area-content">
        
        <div class="paper">
            <div class="paper-title">Institut Pasteur Virology Days meeting report</div>
            <div class="paper-meta">González R <span class="badge badge-first">Co-First</span> et al. • <em>J Mol Cell Biol</em> 2025 • <a href="https://doi.org/10.1093/jmcb/mjae052">Link</a></div>
            <div class="paper-description">Report on the Journées Départementales de Virologie at Institut Pasteur.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Natural variation in <em>Arabidopsis</em> rosette area unveils new developmental genes</div>
            <div class="paper-meta">González R <span class="badge badge-first">Co-First</span> <span class="badge badge-corr">Corr.</span> et al. • <em>Sci Rep</em> 2020 • <a href="https://doi.org/10.1038/s41598-020-74723-4">Link</a></div>
            <div class="paper-description">GWAS identifying new genes involved in plant growth.</div>
        </div>

        <div class="paper">
            <div class="paper-title">The scale-of-choice effect in assortative mating estimates</div>
            <div class="paper-meta">Rolán-Alvarez E <span class="badge badge-corr">Corr.</span> et al. • <em>Evolution</em> 2015 • <a href="https://doi.org/10.1111/evo.12691">Link</a></div>
            <div class="paper-description">Sampling biases affect observations of negative assortative mating frequency.</div>
        </div>
    </div>
</div>

<div style="text-align: center; margin-top: 40px; color: #5f6368;">
<p><em>Exploiting model systems to understand the fundamental principles of host-pathogen interactions</em></p>
</div>
<p style="text-align: center; margin-bottom: 30px; color: #9aa0a6;">Updated January 2025</p>
