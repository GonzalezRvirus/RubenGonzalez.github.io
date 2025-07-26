---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

<style>
.research-area {
    margin-bottom: 30px;
    border-radius: 10px;
    overflow: hidden;
}
.area-header {
    padding: 20px;
    cursor: pointer;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.area-header h2 {
    margin: 0;
    color: white;
}
.area-subtitle {
    color: rgba(255,255,255,0.9);
    font-style: italic;
    margin-top: 5px;
}
.collapse-icon {
    font-size: 24px;
    color: white;
    transition: transform 0.3s;
}
.collapsed .collapse-icon {
    transform: rotate(-90deg);
}
.area-content {
    padding: 0 20px 20px 20px;
    max-height: 10000px;
    transition: max-height 0.3s ease-out, padding 0.3s ease-out;
}
.collapsed .area-content {
    max-height: 0;
    padding: 0 20px;
    overflow: hidden;
}
.paper {
    margin-bottom: 15px;
    padding: 15px;
    border-radius: 5px;
}
.paper-title {
    font-size: 1.1em;
    font-weight: bold;
    margin-bottom: 5px;
    line-height: 1.3;
}
.paper-meta {
    font-size: 0.85em;
    color: #546e7a;
    margin-bottom: 8px;
}
.paper-description {
    font-size: 0.95em;
    line-height: 1.4;
    color: #37474f;
}
.award {
    display: inline-block;
    background-color: #1565c0;
    color: white;
    padding: 2px 8px;
    border-radius: 3px;
    font-size: 0.8em;
    margin-left: 10px;
}
.highlight-paper {
    border-left: 4px solid;
}

/* Professional Blue-based Color Palette */
.area-evolution { background-color: #1565c0; }
.area-evolution .paper { background-color: #f5f9fc; }
.area-evolution .highlight-paper { border-left-color: #1565c0; background-color: #e8f1f9; }

.area-physiology { background-color: #00838f; }
.area-physiology .paper { background-color: #f0f7f8; }
.area-physiology .highlight-paper { border-left-color: #00838f; background-color: #e0f2f4; }

.area-genetics { background-color: #2e7d32; }
.area-genetics .paper { background-color: #f1f8f4; }
.area-genetics .highlight-paper { border-left-color: #2e7d32; background-color: #e8f5e9; }

.area-environment { background-color: #5d4037; }
.area-environment .paper { background-color: #faf9f8; }
.area-environment .highlight-paper { border-left-color: #5d4037; background-color: #f5f2f0; }

.area-other { background-color: #455a64; }
.area-other .paper { background-color: #f8f9fa; }
</style>

<script>
function toggleSection(sectionId) {
    const section = document.getElementById(sectionId);
    section.classList.toggle('collapsed');
}
</script>

<div style="background-color: #e3f2fd; padding: 20px; border-radius: 10px; margin-bottom: 30px;">
<p style="font-size: 1.1em; line-height: 1.6; color: #1a237e;">
My research investigates the fundamental principles governing host-pathogen interactions across model systems. By integrating evolutionary biology, molecular virology, and systems approaches, we uncover how viruses evolve, impact host biology, and interact with environmental factors to shape infection outcomes.
</p>
</div>



<!-- VIRUS EVOLUTION -->
<div id="evolution" class="research-area area-evolution">
    <div class="area-header" onclick="toggleSection('evolution')">
        <div>
            <h2>Virus Evolution</h2>
            <p class="area-subtitle">Understanding evolutionary dynamics and constraints shaping viral adaptation</p>
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
            <div class="paper-meta">González R^† & Butkovic A^† • <em>Front Virol</em> 2022 • <a href="https://doi.org/10.3389/fviro.2022.994057">Link</a></div>
            <div class="paper-description">Comprehensive minireview of key factors driving plant virus evolution.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Defects in plant immunity modulate the rates and patterns of RNA virus evolution</div>
            <div class="paper-meta">Navarro R et al. • <em>Virus Evol</em> 2022 • <a href="https://doi.org/10.1093/ve/veac059">Link</a></div>
            <div class="paper-description">Different host defense signaling pathways constrain virus evolution in distinct ways.</div>
        </div>

        <div class="paper highlight-paper">
            <div class="paper-title">Plant virus evolution under strong drought conditions results in a transition from parasitism to mutualism</div>
            <div class="paper-meta">González R et al. • <em>PNAS</em> 2021 • <a href="https://doi.org/10.1073/pnas.2020990118">Link</a></div>
            <div class="paper-description">Demonstrated that environmental stress can drive viruses to evolve beneficial relationships with their hosts, providing increased tolerance to adverse conditions.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Revisiting <em>Orthotospovirus</em> phylogeny using full-genome data</div>
            <div class="paper-meta">Butkovic A et al. • <em>Arch Virol</em> 2021 • <a href="https://doi.org/10.1007/s00705-020-04902-1">Link</a></div>
            <div class="paper-description">Updated phylogenetic analysis incorporating selection, recombination, and reassortment.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Adaptation of turnip mosaic potyvirus to a specific niche reduces its genetic and environmental robustness</div>
            <div class="paper-meta">Butkovic A et al. • <em>Virus Evol</em> 2020 • <a href="https://doi.org/10.1093/ve/veaa041">Link</a></div>
            <div class="paper-description">Highly adapted viruses are more sensitive to random mutations and temperature changes than non-adapted viruses.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Role of host genetic diversity for susceptibility-to-infection in the evolution of virulence of a plant virus</div>
            <div class="paper-meta">González R et al. • <em>Virus Evol</em> 2019 • <a href="https://doi.org/10.1093/ve/vez024">Link</a></div>
            <div class="paper-description">Viruses specialize faster in homogeneous host populations but become more pathogenic in heterogeneous ones.</div>
        </div>

        <div class="paper highlight-paper">
            <div class="paper-title">Mutagenesis scanning uncovers evolutionary constraints on tobacco etch potyvirus membrane-associated 6K2 protein
            <span class="award">Best Student Paper Award</span></div>
            <div class="paper-meta">González R^ et al. • <em>Genome Biol Evol</em> 2019 • <a href="https://doi.org/10.1093/gbe/evz069">Link</a></div>
            <div class="paper-description">Revealed evolutionary tradeoffs between within-host viral accumulation and symptom severity.</div>
        </div>
    </div>
</div>

<!-- VIRAL IMPACTS ON HOST PHYSIOLOGY -->
<div id="physiology" class="research-area area-physiology collapsed">
    <div class="area-header" onclick="toggleSection('physiology')">
        <div>
            <h2>Viral Impacts on Host Physiology</h2>
            <p class="area-subtitle">How viral infections fundamentally alter host biology and development</p>
        </div>
        <span class="collapse-icon">▼</span>
    </div>
    <div class="area-content">
        
        <div class="paper">
            <div class="paper-title">Viral infections reduce <em>Drosophila</em> lifespan through accelerated aging</div>
            <div class="paper-meta">González R et al. • <em>bioRxiv</em> 2025 • <a href="https://doi.org/10.1101/2025.03.13.643076">Link</a></div>
            <div class="paper-description">Enteric viral infections trigger irreversible aging processes that persist even after infection clearance, correlating with reduced lifespan.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Persistent viral infections impact key biological traits in <em>Drosophila melanogaster</em></div>
            <div class="paper-meta">Castelló-Sanuán M et al. • <em>bioRxiv</em> 2025 • <a href="https://doi.org/10.1101/2025.03.12.642769">Link</a></div>
            <div class="paper-description">Comprehensive characterization of how persistent viral infections affect insect biology.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Transcriptional and hormonal profiling uncovers plant development-virus interactions</div>
            <div class="paper-meta">Melero I et al. • <em>J Gen Virol</em> 2024 • <a href="https://doi.org/10.1099/jgv.0.002023">Link</a></div>
            <div class="paper-description">Plants downregulate cell wall genes to facilitate viral spread but maintain fertility through salicylic acid-mediated resistance tradeoffs.</div>
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
            <div class="paper-meta">González R^† et al. • <em>Adv Virus Res</em> 2020 • <a href="https://doi.org/10.1016/bs.aivir.2020.01.003">Link</a></div>
            <div class="paper-description">Review: viruses can enhance host survival under environmental stress by altering phenotypic plasticity.</div>
        </div>
    </div>
</div>

<!-- GENETIC ARCHITECTURE -->
<div id="genetics" class="research-area area-genetics collapsed">
    <div class="area-header" onclick="toggleSection('genetics')">
        <div>
            <h2>Genetic Architecture of Host-Virus Interactions</h2>
            <p class="area-subtitle">Uncovering the molecular basis of susceptibility and resistance</p>
        </div>
        <span class="collapse-icon">▼</span>
    </div>
    <div class="area-content">
        
        <div class="paper highlight-paper">
            <div class="paper-title">Genetic basis of <em>Arabidopsis thaliana</em> responses to turnip mosaic virus</div>
            <div class="paper-meta">Butkovic A^ et al. • <em>eLife</em> 2024 • <a href="https://doi.org/10.7554/eLife.89749.1">Link</a></div>
            <div class="paper-description">Identified genetic underpinnings of plant resistance to naïve and adapted viral isolates.</div>
        </div>

        <div class="paper">
            <div class="paper-title"><em>Caenorhabditis elegans</em> immune responses to intracellular pathogens</div>
            <div class="paper-meta">González R† & Félix M-A • <em>Dev Comp Immunol</em> 2024 • <a href="https://doi.org/10.1016/j.dci.2024.105148">Link</a></div>
            <div class="paper-description">Review of nematode responses to microsporidia and viruses.</div>
        </div>

        <div class="paper">
            <div class="paper-title"><em>C. elegans</em> pharynx mutants resist Orsay virus infection</div>
            <div class="paper-meta">González R† & Félix M-A • <em>microPubl Biol</em> 2024 • <a href="https://doi.org/10.17912/micropub.biology.001166">Link</a></div>
            <div class="paper-description">Identified specific mutants conferring viral resistance.</div>
        </div>

        <div class="paper">
            <div class="paper-title">GWAS identifies <em>Arabidopsis</em> genes affecting TuMV infection outcomes</div>
            <div class="paper-meta">Butković A et al. • <em>Virus Evol</em> 2021 • <a href="https://doi.org/10.1093/ve/veab063">Link</a></div>
            <div class="paper-description">Genome-wide study revealing new host genes involved in plant defense and virus replication.</div>
        </div>
    </div>
</div>

<!-- ENVIRONMENTAL MODULATION -->
<div id="environment" class="research-area area-environment collapsed">
    <div class="area-header" onclick="toggleSection('environment')">
        <div>
            <h2>Environmental Modulation of Host-Virus Interactions</h2>
            <p class="area-subtitle">How ecological context shapes viral infections</p>
        </div>
        <span class="collapse-icon">▼</span>
    </div>
    <div class="area-content">
        
        <div class="paper">
            <div class="paper-title">Microgravity and low muon radiation affect viral pathogenesis in <em>C. elegans</em></div>
            <div class="paper-meta">Villena-Giménez A et al. • <em>bioRxiv</em> 2024 • <a href="https://doi.org/10.1101/2024.10.03.616447">Link</a></div>
            <div class="paper-description">Space-like conditions impact fecundity and developmental success in infected animals.</div>
        </div>

        <div class="paper highlight-paper">
            <div class="paper-title">Natural monobacterial environments modulate viral infection in <em>C. elegans</em></div>
            <div class="paper-meta">González R† & Félix M-A† • <em>PLoS Pathog</em> 2024 • <a href="https://doi.org/10.1371/journal.ppat.1011947">Link</a></div>
            <div class="paper-description">Natural bacteria reduce viral susceptibility through novel DRH-1-dependent mechanisms without degrading virions or affecting nutrition.</div>
        </div>

        <div class="paper">
            <div class="paper-title">The interplay between the host microbiome and pathogenic viral infections</div>
            <div class="paper-meta">González R† & Elena SF • <em>mBio</em> 2021 • <a href="https://doi.org/10.1128/mBio.02496-21">Link</a></div>
            <div class="paper-description">Integrative review of microbiome impacts on viral infections across pathosystems.</div>
        </div>
    </div>
</div>

<!-- OTHER CONTRIBUTIONS -->
<div id="other" class="research-area area-other collapsed">
    <div class="area-header" onclick="toggleSection('other')">
        <div>
            <h2>Other Contributions</h2>
            <p class="area-subtitle">Additional research and scientific communications</p>
        </div>
        <span class="collapse-icon">▼</span>
    </div>
    <div class="area-content">
        
        <div class="paper">
            <div class="paper-title">Institut Pasteur Virology Days meeting report</div>
            <div class="paper-meta">González R^ et al. • <em>J Mol Cell Biol</em> 2025 • <a href="https://doi.org/10.1093/jmcb/mjae052">Link</a></div>
            <div class="paper-description">Report on the Journées Départementales de Virologie at Institut Pasteur.</div>
        </div>

        <div class="paper">
            <div class="paper-title">Natural variation in <em>Arabidopsis</em> rosette area unveils new developmental genes</div>
            <div class="paper-meta">González R^† et al. • <em>Sci Rep</em> 2020 • <a href="https://doi.org/10.1038/s41598-020-74723-4">Link</a></div>
            <div class="paper-description">GWAS identifying new genes involved in plant growth.</div>
        </div>

        <div class="paper">
            <div class="paper-title">The scale-of-choice effect in assortative mating estimates</div>
            <div class="paper-meta">Rolán-Alvarez E† et al. • <em>Evolution</em> 2015 • <a href="https://doi.org/10.1111/evo.12691">Link</a></div>
            <div class="paper-description">Sampling biases affect observations of negative assortative mating frequency.</div>
        </div>
    </div>
</div>

<div style="text-align: center; margin-top: 40px; color: #37474f;">
<p><em>Exploiting model systems to understand the fundamental principles of host-pathogen interactions</em></p>
</div>
<p style="text-align: center; margin-bottom: 30px; color: #546e7a;">Updated January 2025 </p>
