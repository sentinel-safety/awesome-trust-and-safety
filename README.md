# Awesome Trust and Safety [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of tools, research, organizations, datasets, and frameworks for trust and safety, child protection, and content moderation. Maintained by the [SENTINEL Foundation](https://github.com/sentinel-safety).

## Contents

- [Detection and Moderation Tools](#detection-and-moderation-tools)
- [Child Safety Organizations](#child-safety-organizations)
- [Regulatory Frameworks](#regulatory-frameworks)
- [Research and Datasets](#research-and-datasets)
- [Academic Venues](#academic-venues)
- [Industry Coalitions](#industry-coalitions)
- [Learning Resources](#learning-resources)

---

## Detection and Moderation Tools

### Behavioral Detection

- [SENTINEL](https://github.com/sentinel-safety/SENTINEL) - Open-source behavioral intelligence platform for detecting child grooming through conversation patterns, relationship graphs, and temporal signals. Compliance-ready for DSA, UK Online Safety Act, and COPPA. Free for platforms under $100k revenue.
- [Google Perspective API](https://www.perspectiveapi.com/) - Machine learning API for detecting toxic content using a model trained on millions of comments.
- [Microsoft Azure Content Moderator](https://azure.microsoft.com/en-us/products/ai-services/content-moderator) - AI service for detecting offensive, risky, or undesirable content in text, images, and video.

### Hash Matching and CSAM Detection

- [IWF Image Intercept](https://www.iwf.org.uk/our-technology/image-intercept/) - Internet Watch Foundation API for detecting known child sexual abuse imagery via PhotoDNA hash matching.
- [Microsoft PhotoDNA](https://www.microsoft.com/en-us/photodna) - Technology for detecting known CSAM using robust image hashing. Available to qualifying organizations.
- [NCMEC CyberTipline](https://www.missingkids.org/gethelpnow/cybertipline) - US national clearinghouse for reports of child sexual exploitation online. Platforms operating in the US are legally required to report.
- [Project Arachnid](https://projectarachnid.ca/) - Canadian Centre for Child Protection crawler that detects child sexual abuse material across the web.

### Age Verification and Access Controls

- [k-ID](https://www.k-id.com/) - Age assurance platform for game developers, providing parental consent flows and age-appropriate feature gating.

### Content Classification

- [Jigsaw Harassment Manager](https://github.com/jigsaw-code/harassment-manager) - Open-source tool for researchers and journalists to document online harassment.
- [Cleanspeak](https://cleanspeak.com/) - Profanity filter and user moderation platform for games and social platforms.

---

## Child Safety Organizations

### International

- [Internet Watch Foundation (IWF)](https://www.iwf.org.uk/) - UK-based charity operating the global hotline for reporting online child sexual abuse content.
- [INHOPE](https://www.inhope.org/) - International Association of Internet Hotlines, coordinating 51 national hotlines for CSAM reporting.
- [WeProtect Global Alliance](https://www.weprotect.org/) - Global movement dedicated to protecting children from sexual exploitation and abuse online.
- [Thorn](https://www.thorn.org/) - Technology nonprofit building tools to defend children from sexual abuse, including Safer for detecting CSAM at upload.

### United States

- [National Center for Missing and Exploited Children (NCMEC)](https://www.missingkids.org/) - US clearinghouse for CyberTipline reports. US federal law requires electronic service providers to report CSAM to NCMEC.
- [Crimes Against Children Research Center (CCRC)](https://www.unh.edu/ccrc/) - Research center at University of New Hampshire studying crimes against children, including online grooming.
- [ConnectSafely](https://www.connectsafely.org/) - Non-profit focused on educating users about safety, privacy, and security online.

### United Kingdom

- [Childnet](https://www.childnet.com/) - UK charity working to make the internet safer for children.
- [Internet Matters](https://www.internetmatters.org/) - UK non-profit providing resources to help families navigate online safety.
- [5Rights Foundation](https://5rightsfoundation.com/) - Advocacy organization establishing children's rights in the digital world.
- [UK Safer Internet Centre](https://www.saferinternet.org.uk/) - Partnership of three organizations providing support for online safety in the UK.

### Australia

- [eSafety Commissioner](https://www.esafety.gov.au/) - World's first government regulator for online safety, with powers to require removal of harmful content.

---

## Regulatory Frameworks

### European Union

- [Digital Services Act (DSA)](https://digital-strategy.ec.europa.eu/en/policies/digital-services-act-package) - EU regulation requiring platforms to conduct risk assessments and take measures to protect minors.
- [GDPR Article 8](https://gdpr.eu/article-8-conditions-for-childs-consent/) - Special provisions for children's data requiring parental consent below age 16 (member states may lower to 13).

### United Kingdom

- [Online Safety Act 2023](https://www.legislation.gov.uk/ukpga/2023/50/contents/enacted) - UK legislation requiring platforms to protect users from illegal and harmful content, with enhanced duties toward children.
- [Ofcom Online Safety Guidance](https://www.ofcom.org.uk/online-safety) - Ofcom's codes of practice and guidance for platforms under the Online Safety Act.
- [Age Appropriate Design Code](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/childrens-information/childrens-code-guidance-and-resources/) - ICO code setting 15 standards for services likely to be accessed by children.

### United States

- [COPPA](https://www.ftc.gov/legal-library/browse/rules/childrens-online-privacy-protection-rule-coppa) - FTC rule requiring verifiable parental consent before collecting data from children under 13.
- [REPORT Act](https://www.congress.gov/bill/118th-congress/senate-bill/474) - US law strengthening reporting requirements for platforms detecting child sexual exploitation.

### Australia

- [Online Safety Act 2021](https://www.legislation.gov.au/Series/C2021A00076) - Australian legislation establishing the eSafety Commissioner's powers.

---

## Research and Datasets

### Key Papers

- [An et al. (2026)](https://arxiv.org/abs/2503.05727) - State-of-the-art grooming detection using multi-modal behavioral signals and NLP.
- [Leiva-Bianchi et al. (2025)](https://www.nature.com/srep/) - Meta-analysis of ML approaches to online grooming detection in Scientific Reports.
- [McKeever & Hamm (2025)](https://www.frontiersin.org/journals/pediatrics) - Comparing ML models with focus on tone in grooming chat logs, Frontiers in Pediatrics.
- [Michalopoulos & Mavridis (2011)](https://dl.acm.org/doi/10.1145/2030376.2030387) - Foundational work on automated detection of online predatory behavior.

### Datasets

- [PAN 2012 Sexual Predator Identification Dataset](https://pan.webis.de/clef12/pan12-web/sexual-predator-identification.html) - Benchmark dataset of chat conversations for grooming detection research.
- [SENTINEL Synthetic Dataset](https://github.com/sentinel-safety/SENTINEL/tree/main/datasets) - Open synthetic behavioral dataset for grooming signal research, v1.0.

---

## Academic Venues

- [WOAH (Workshop on Online Abuse and Harms)](https://www.workshopononlineabuse.com/) - Annual workshop co-located with major NLP conferences. Premier venue for online harm detection research.
- [ACM FAccT](https://facctconference.org/) - Conference on Fairness, Accountability, and Transparency. Relevant for demographic parity in content moderation.
- [ACM CCS](https://www.sigsac.org/ccs.html) - Conference on Computer and Communications Security. Relevant for privacy-preserving detection architectures.
- [IEEE S&P](https://www.ieee-security.org/TC/SP/) - IEEE Symposium on Security and Privacy.
- [ACM CHI](https://chi.acm.org/) - Human factors in computing, including user-facing safety systems.

---

## Industry Coalitions

- [Technology Coalition](https://www.technologycoalition.org/) - Alliance of technology companies committed to fighting online child sexual exploitation. Operates Project Protect.
- [ROOST](https://roost.tools/) - Open-source safety tooling ecosystem for platform operators.
- [Trust and Safety Professional Association (TSPA)](https://www.tspa.org/) - Professional community for trust and safety practitioners.
- [FOSI (Family Online Safety Institute)](https://www.fosi.org/) - International non-profit working to make the online world safer for children and families.

---

## Learning Resources

- [NCMEC NetSmartz](https://www.missingkids.org/netsmartz/home) - Educational resources for children, parents, and educators on online safety.
- [IWF Awareness Resources](https://www.iwf.org.uk/resources/) - Reports, guides, and awareness materials from the Internet Watch Foundation.
- [Oxford Internet Institute](https://www.oii.ox.ac.uk/) - Multidisciplinary research on the social implications of the internet.
- [LSE Media and Communications](https://www.lse.ac.uk/media-and-communications) - Research group studying children's digital lives and online safety (Prof. Sonia Livingstone).

---

## Contributing

Contributions welcome. Please open a PR with:
- A brief description of why the resource belongs on this list
- A direct link to the resource
- Confirmation the resource is actively maintained

All entries must be genuinely useful to trust and safety practitioners, researchers, or platform operators.

---

Maintained by the [SENTINEL Foundation](https://github.com/sentinel-safety/SENTINEL). CC0 1.0 Universal.
