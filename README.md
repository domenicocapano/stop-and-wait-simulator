[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20401650.svg)](https://doi.org/10.5281/zenodo.20401650)

# Stop-and-Wait Simulator

**Version:** 2.1 — Zenodo Edition  
**Author:** Domenico Capano  
**Copyright holder:** Domenico Capano  
**Project reference:** LearningObjects.org  
**License:** PolyForm Noncommercial License 1.0.0  
**Zenodo DOI:** [10.5281/zenodo.20401650](https://doi.org/10.5281/zenodo.20401650)

## Description

Stop-and-Wait Simulator is an interactive educational software tool designed to support the study of ARQ protocols, flow control, acknowledgements (ACKs), timeouts, retransmissions and sequence numbers in computer networks.

The simulator provides a visual space-time diagram of the communication between sender A and receiver B, showing frames, ACKs, timers, timeouts, retransmissions and duplicate-frame handling. It includes configurable scenarios such as corrupted or lost frames, lost ACKs, delayed frames and random transmission errors.

The software is distributed as a standalone HTML5 file and works offline in any modern browser, without installation, server configuration or external dependencies.

This simulator is a digital educational resource published on LearningObjects.org as a free support tool for teachers. LearningObjects.org also hosts Learning Object Generator 6.3, the software connected to the book *Progettare l’Apprendimento con i Learning Objects*. The simulator should not be understood as a resource derived from the book, but as an additional educational tool available in the same web environment devoted to software, resources and materials for teachers.

## Main features

- Animated space-time diagram between sender A and receiver B.
- Configurable scenarios: corrupted or lost frame, lost ACK, delayed frame, random errors.
- Runtime annotations with improved readability.
- Step-by-step teaching mode with multiple-choice questions.
- Theory board with the Stop-and-Wait efficiency formula.
- Note on FCS/CRC, Ethernet and ARQ protocols.
- Event log modal with copy, TXT export and print/PDF through the browser.
- Responsive layout for desktop, tablet and smartphone.
- Offline use: no external dependencies.

## Theoretical efficiency formula

η = T_TX / (T_TX + 2·T_PROP) = 1 / (1 + 2a)

where `a = T_PROP / T_TX`.

## Note on FCS/CRC, Ethernet and ARQ protocols

FCS/CRC is used to detect whether a frame has arrived corrupted. After error detection, the behaviour depends on the protocol being used.

Classic wired Ethernet uses FCS/CRC to detect errors and discards corrupted frames, without automatically performing retransmissions at the Data Link layer.

Other link-layer protocols or technologies may use ARQ mechanisms with ACKs, timeouts and retransmissions. Stop-and-Wait is the simplest ARQ model and helps explain the general principle, later extended by more efficient protocols such as Sliding Window, Go-Back-N and Selective Repeat.

## How to use

Open `index.html` in a modern browser.

After enabling GitHub Pages, the simulator will be available online at:

```text
https://domenicocapano.github.io/stop-and-wait-simulator/
```

## Repository contents

```text
index.html      Main simulator file for GitHub Pages
README.md       GitHub README file
LICENSE         PolyForm Noncommercial License 1.0.0
CITATION.cff    Citation metadata
```

## Recommended citation

Capano, D. (2026). *Stop-and-Wait Simulator: An Interactive Educational Tool for ARQ Protocols* (2.1). Zenodo. https://doi.org/10.5281/zenodo.20401650

## BibTeX

```bibtex
@software{capano2026stopandwait,
  author    = {Capano, Domenico},
  title     = {Stop-and-Wait Simulator: An Interactive Educational Tool for ARQ Protocols},
  year      = {2026},
  version   = {2.1},
  publisher = {Zenodo},
  doi       = {10.5281/zenodo.20401650},
  url       = {https://doi.org/10.5281/zenodo.20401650}
}
```

## License and permitted use

Copyright © 2026 Domenico Capano.

This software is licensed under the **PolyForm Noncommercial License 1.0.0**.

The software may be used, copied, modified and distributed for non-commercial educational, training, personal and research purposes, provided that proper attribution is given to the author.

Commercial use requires prior written permission from the author.

See the `LICENSE` file for the full license text.

## Contact

Domenico Capano  
LearningObjects.org

---

## Italiano

**Stop-and-Wait Simulator** è un simulatore didattico interattivo per lo studio del protocollo Stop-and-Wait, dei protocolli ARQ, degli ACK, dei timeout, delle ritrasmissioni e dei numeri di sequenza nelle reti di calcolatori.

Il simulatore è pubblicato come risorsa digitale aggiuntiva su LearningObjects.org, come supporto gratuito per i docenti. Non deve essere inteso come risorsa derivata dal volume *Progettare l’Apprendimento con i Learning Objects*, ma come strumento didattico disponibile nello stesso ambiente web in cui sono presenti software, risorse e materiali per docenti.

Citazione consigliata:

Capano, D. (2026). *Stop-and-Wait Simulator: An Interactive Educational Tool for ARQ Protocols* (2.1). Zenodo. https://doi.org/10.5281/zenodo.20401650
