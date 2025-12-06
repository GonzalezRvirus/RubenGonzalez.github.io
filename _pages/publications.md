---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
---

<style>
/* --- CLEAN LAYOUT --- */
.research-area {
    margin-bottom: 20px;
    border-top: 1px solid #000;
}

/* --- HEADER --- */
.area-header {
    padding: 25px 0;
    cursor: pointer;
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    transition: opacity 0.2s;
}
.area-header:hover {
    opacity: 0.7;
}
.area-header h2 {
    margin: 0;
    color: #000;
    font-weight: 700;
    font-size: 1.3em;
    text-transform: uppercase;
    letter-spacing: 0.05em;
}
.area-subtitle {
    color: #555;
    font-size: 1.0em; /* Fixed: Increased size */
    margin-top: 5px;
    font-weight: 400; /* Made slightly heavier */
    max-width: 800px;
}

/* --- COLLAPSE ICON --- */
.collapse-icon {
    font-size: 14px;
    color: #999;
}
.collapsed .collapse-icon {
    transform: rotate(-90deg);
}

/* --- PAPER LIST --- */
.area-content {
    padding-bottom: 40px;
    max-height: 10000px;
    transition: max-height 0.4s ease-out;
    overflow: hidden;
}
.collapsed .area-content {
    max-height: 0;
    padding-bottom: 0;
}

/* --- INDIVIDUAL ENTRY --- */
.paper {
    margin-bottom: 25px;
    padding-left: 15px;
    border-left: 2px solid #f0f0f0;
    transition: border-color 0.2s;
}
.paper:hover {
    border-left: 2px solid #1a73e8;
}

.paper-title {
    font-size: 1.15em; /* Fixed: Increased size */
    font-weight: 600;
    color: #202124;
    line-height: 1.4;
    margin-bottom: 4px;
}

.paper-meta {
    font-family: sans-serif;
    font-size: 1.0em; /* Fixed: Increased from 0.9em */
    color: #555;
}

.paper-meta a {
    color: #1a73e8;
    text-decoration: none;
    margin-left: 8px;
    font-size: 0.9em;
    text-transform: uppercase;
    font-weight: 600;
    letter-spacing: 0.05em;
}

.paper-description {
    margin-top: 6px;
    font-size: 1.05em; /* Fixed: Increased size */
    color: #444;
    line-height: 1.6;
}
</style>

<script>
function toggleSection(sectionId) {
    const section = document.getElementById(sectionId);
    section.classList.toggle('collapsed');
}
</script>

<div id="evolution" class="research-area collapsed">
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
            <div class="paper-meta">Castiglioni VG et al. • <em>Infect Genet Evol</em> 2024 • <a href="https://doi.org/10.1016/j.meegid.2024.105623">DOI</a></div>
            <div class="paper-description">Identified genomic hotspots of nucleotide diversity important for Orsay virus evolution, establishing grounds for experimental virus evolution studies in nematodes.</div>
        </div>

        <div class="paper">
            <div class="paper-title">A brief view on factors that affect plant virus evolution</div>
            <div class="paper-meta">González R & Butkovic A • <em>Front Virol</em> 2022 • <a href="https://doi.org/10.3389/fviro.2022.994057">DOI</a></div>
            <div class="paper-description">Comprehensive minireview of key factors driving plant virus evolution.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Defects in plant immunity modulate the rates and patterns of RNA virus evolution</div>
            <div class="paper-meta">Navarro R et al. • <em>Virus Evol</em> 2022 • <a href="https://doi.org/10.1093/ve/veac059">DOI</a></div>
            <div class="paper-description">Different host defense signaling pathways constrain virus evolution in distinct ways.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Plant virus evolution under strong drought conditions results in a transition from parasitism to mutualism</div>
            <div class="paper-meta">González R et al. • <em>PNAS</em> 2021 • <a href="https://doi.org/10.1073/pnas.2020990118">DOI</a> <a href="https://www.pnas.org/doi/10.1073/pnas.2100936118" style="color:#666;">[Commentary]</a></div>
            <div class="paper-description">Demonstrated that environmental stress can drive viruses to evolve beneficial relationships with their hosts, providing increased tolerance to adverse conditions.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Revisiting <em>Orthotospovirus</em> phylogeny using full-genome data</div>
            <div class="paper-meta">Butkovic A et al. • <em>Arch Virol</em> 2021 • <a href="https://doi.org/10.1007/s00705-020-04902-1">DOI</a></div>
            <div class="paper-description">Updated phylogenetic analysis incorporating selection, recombination, and reassortment.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Adaptation of turnip mosaic potyvirus to a specific niche reduces its genetic and environmental robustness</div>
            <div class="paper-meta">Butkovic A et al. • <em>Virus Evol</em> 2020 • <a href="https://doi.org/10.1093/ve/veaa041">DOI</a></div>
            <div class="paper-description">Highly adapted viruses are more sensitive to random mutations and temperature changes than non-adapted viruses.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Role of host genetic diversity for susceptibility-to-infection in the evolution of virulence of a plant virus</div>
            <div class="paper-meta">González R et al. • <em>Virus Evol</em> 2019 • <a href="https://doi.org/10.1093/ve/vez024">DOI</a></div>
            <div class="paper-description">Viruses specialize faster in homogeneous host populations but become more pathogenic in heterogeneous ones.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Mutagenesis scanning uncovers evolutionary constraints on tobacco etch potyvirus membrane-associated 6K2 protein</div>
            <div class="paper-meta">González R et al. • <em>Genome Biol Evol</em> 2019 • <a href="https://doi.org/10.1093/gbe/evz069">DOI</a></div>
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
            <div class="paper-meta">González R et al. • <em>bioRxiv</em> 2025 • <a href="https://doi.org/10.1101/2025.03.13.643076">DOI</a></div>
            <div class="paper-description">Enteric viral infections trigger irreversible aging processes that persist even after infection clearance, correlating with reduced lifespan.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Persistent viral infections impact key biological traits in <em>Drosophila melanogaster</em></div>
            <div class="paper-meta">Castelló-Sanuán M et al. • <em>bioRxiv</em> 2025 • <a href="https://doi.org/10.1101/2025.03.12.642769">DOI</a></div>
            <div class="paper-description">Comprehensive characterization of how persistent viral infections affect insect biology.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Transcriptional and hormonal profiling uncovers plant development-virus interactions</div>
            <div class="paper-meta">Melero I et al. • <em>J Gen Virol</em> 2024 • <a href="https://doi.org/10.1099/jgv.0.002023">DOI</a></div>
            <div class="paper-description">Plants downregulate cell wall genes to facilitate viral spread but maintain fertility through salicylic acid-mediated resistance tradeoffs.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Host developmental stages shape the evolution of a plant RNA virus</div>
            <div class="paper-meta">Melero I et al. • <em>Phil Trans R Soc B</em> 2023 • <a href="https://doi.org/10.1098/rtsb.2022.0005">DOI</a></div>
            <div class="paper-description">TuMV evolution differs across three developmental stages of <em>Arabidopsis thaliana</em>.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Viral strain-dependent impact of plant developmental stages on interaction networks</div>
            <div class="paper-meta">Melero I et al. • <em>microPubl Biol</em> 2023 • <a href="https://doi.org/10.17912/micropub.biology.000943">DOI</a></div>
            <div class="paper-description">Ancestral viral adaptation history influences future evolution under developmental constraints.</div>
        </div>

        <div class="paper">
            <div class="paper-title">From foes to friends: viral infections expand host phenotypic plasticity</div>
            <div class="paper-meta">González R et al. • <em>Adv Virus Res</em> 2020 • <a href="https://doi.org/10.1016/bs.aivir.2020.01.003">DOI</a></div>
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
            <div class="paper-meta">Butkovic A et al. • <em>eLife</em> 2024 • <a href="https://doi.org/10.7554/eLife.89749.1">DOI</a></div>
            <div class="paper-description">Identified genetic underpinnings of plant resistance to naïve and adapted viral isolates.</div>
        </div>

        <div class="paper">
            <div class="paper-title"><em>Caenorhabditis elegans</em> immune responses to intracellular pathogens</div>
            <div class="paper-meta">González R & Félix M-A • <em>Dev Comp Immunol</em> 2024 • <a href="https://doi.org/10.1016/j.dci.2024.105148">DOI</a></div>
            <div class="paper-description">Review of nematode responses to microsporidia and viruses.</div>
        </div>

        <div class="paper">
            <div class="paper-title"><em>C. elegans</em> pharynx mutants resist Orsay virus infection</div>
            <div class="paper-meta">González R & Félix M-A • <em>microPubl Biol</em> 2024 • <a href="https://doi.org/10.17912/micropub.biology.001166">DOI</a></div>
            <div class="paper-description">Identified specific mutants conferring viral resistance.</div>
        </div>

        <div class="paper">
            <div class="paper-title">GWAS identifies <em>Arabidopsis</em> genes affecting TuMV infection outcomes</div>
            <div class="paper-meta">Butković A et al. • <em>Virus Evol</em> 2021 • <a href="https://doi.org/10.1093/ve/veab063">DOI</a></div>
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
            <div class="paper-meta">Villena-Giménez A et al. • <em>bioRxiv</em> 2024 • <a href="https://doi.org/10.1101/2024.10.03.616447">DOI</a></div>
            <div class="paper-description">Space-like conditions impact fecundity and developmental success in infected animals.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Natural monobacterial environments modulate viral infection in <em>C. elegans</em></div>
            <div class="paper-meta">González R & Félix M-A • <em>PLoS Pathog</em> 2024 • <a href="https://doi.org/10.1371/journal.ppat.1011947">DOI</a></div>
            <div class="paper-description">Natural bacteria reduce viral susceptibility through novel DRH-1-dependent mechanisms without degrading virions or affecting nutrition.</div>
        </div>

        <div class="paper">
            <div class="paper-title">The interplay between the host microbiome and pathogenic viral infections</div>
            <div class="paper-meta">González R & Elena SF • <em>mBio</em> 2021 • <a href="https://doi.org/10.1128/mBio.02496-21">DOI</a></div>
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
            <div class="paper-meta">González R et al. • <em>J Mol Cell Biol</em> 2025 • <a href="https://doi.org/10.1093/jmcb/mjae052">DOI</a></div>
            <div class="paper-description">Report on the Journées Départementales de Virologie at Institut Pasteur.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Natural variation in <em>Arabidopsis</em> rosette area unveils new developmental genes</div>
            <div class="paper-meta">González R et al. • <em>Sci Rep</em> 2020 • <a href="https://doi.org/10.1038/s41598-020-74723-4">DOI</a></div>
            <div class="paper-description">GWAS identifying new genes involved in plant growth.</div>
        </div>

        <div class="paper">
            <div class="paper-title">The scale-of-choice effect in assortative mating estimates</div>
            <div class="paper-meta">Rolán-Alvarez E et al. • <em>Evolution</em> 2015 • <a href="https://doi.org/10.1111/evo.12691">DOI</a></div>
            <div class="paper-description">Sampling biases affect observations of negative assortative mating frequency.</div>
        </div>
    </div>
</div>

<p style="text-align: center; margin: 50px 0; color: #9aa0a6; font-size: 0.8em;">Updated January 2025</p>
