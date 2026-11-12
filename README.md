# HPE7-A12 Study Guide and Technical Reference (ACP-DCArc)

Static single-file HTML5 technical reference and preparation guide for the **HPE7-A12 exam** (*HPE Network Data Center Professional Architect Exam*), validating the **HPE Aruba Networking Certified Professional: Data Center Architect (`ACP-DCArc`)** credential.

## Exam Blueprint Overview

| Attribute | Verified Specification |
|---|---|
| Vendor | Hewlett Packard Enterprise (HPE Aruba Networking) |
| Exam Code | `HPE7-A12` |
| Official Title | HPE Network Data Center Professional Architect Exam |
| Credential | HPE Aruba Networking Certified Professional: Data Center Architect (`ACP-DCArc`) |
| Status | Active (Rev. 3, Nov 2025) |
| Delivery | Proctored (Pearson VUE test center or OnVUE) |
| Duration & Items | 2 hours, 70 questions (Single-response, Multiple-response, Matching) |
| Passing Score | 66% |
| Prerequisites | None required |

### Weighted Exam Domains

1. **Architect the Solution (39%):** CX 8325, CX 9300, CX 10000 DSS, and CX 6300 switch selection; dual-ToR VSX ISL port math; Two-Tier VSX vs. Layer 3 spine-and-leaf EVPN-VXLAN (`AFI=25/SAFI=70`, Route Types 2, 3, and 5, Active Gateway IRB, multi-fabric eBGP DCI); Fabric Composer and PSM logical AND micro-segmentation; CX 10000 border-leaf IPsec ESP/NAT; lossless RoCEv2 and GenAI GPU fabrics (PFC, ETS, DCBx, underlay-only ECN).
2. **Analyze Requirements (25%):** Constraint analysis (brownfield non-CX switches, fiber grades, rack airflow polarity, budgets, BGP fluency), Fabric Composer vs. HPE Aruba Networking Central selection, and separating verified requirements from assumptions.
3. **Determine Customer's Requirements (19%):** Stakeholder discovery across executive sponsors, security teams, and compute/storage leads; technical inventory collection covering rack speeds, cabling, ASNs, SPOCK compatibility, and OOBM iLO ports.
4. **Prepare and Present the Solution (17%):** High-level design (HLD) rationale, low-level design (LLD) transceiver/port/VNI/QoS matrices, design reviews, and handoff validation.

## Repository Contents

- `index.html`: Self-contained single-file HTML5 technical reference with embedded CSS and embedded Poppins (`woff2`) typography. Requires zero external stylesheets, scripts, CDNs, or JavaScript.
- `README.md`: Repository documentation, exam metadata, and GitHub Pages setup instructions.
- `.nojekyll`: Disables Jekyll processing on GitHub Pages so static HTML serves directly.
- `.gitignore`: Excludes common OS and editor artifacts.
- `robots.txt`: Standard crawler allow rule (`Allow: /`).

## Preview Locally

Open `index.html` directly in any browser, or run a lightweight local HTTP server from the repository root:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000/`.

## Deploy with GitHub Pages

1. Push this repository to GitHub on the `main` branch.
2. Open **Settings > Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose branch `main` and folder `/ (root)`, then click **Save**.
5. After GitHub Pages publishes the site, optionally add `<link rel="canonical" href="<published-url>">` and `<meta property="og:url" content="<published-url>">` inside `index.html`, plus a `Sitemap:` entry in `robots.txt` if you add a `sitemap.xml`.

## Reference Links Included in `index.html`

### Official HPE & Exam Delivery References

- [HPE Network Data Center Professional Architect Exam (HPE7-A12) Preparation Guide](https://certification-learning.hpe.com/tr/datasheet/exam/HPE7-A12)
- [HPE Aruba Networking Certified Professional Data Center Architect Certification Data Sheet](https://certification-learning.hpe.com/tr/datasheet/certification/ACP-DCArc)
- [Designing HPE Aruba Networking Data Center Solutions, Rev.25.41 (Course 0001214165)](https://certification-learning.hpe.com/tr/datasheet/course/0001214165)
- [HPE Aruba Networking Certified Professional Data Center Architect (HPE7-A12) Official Certification Study Guide](https://hpepress.hpe.com/product/HPE+Aruba+Networking+Certified+Professional+-+Data+Center+Architect+Official+Certification+Study+Guide+HPE7-A12-Hardcover-20610)
- [HPE Aruba Networking ESP Data Center Design Validated Solution Guide](https://arubanetworking.hpe.com/techdocs/VSG/docs/040-dc-design/esp-dc-design-000/)
- [ESP Data Center Connectivity Design Guide](https://arubanetworking.hpe.com/techdocs/VSG/docs/040-dc-design/esp-dc-design-020-network-design/)
- [ESP Data Center Policy Design Guide](https://arubanetworking.hpe.com/techdocs/VSG/docs/040-dc-design/esp-dc-design-024-policy-design/)
- [ESP Data Center Storage and Lossless Ethernet Design Guide](https://arubanetworking.hpe.com/techdocs/VSG/docs/040-dc-design/esp-dc-design-025-lossless-ethernet/)
- [ESP Data Center Secure Interconnect Design Guide](https://arubanetworking.hpe.com/techdocs/VSG/docs/040-dc-design/esp-dc-design-022-secure-dci/)
- [ESP Data Center Management Design Guide](https://arubanetworking.hpe.com/techdocs/VSG/docs/040-dc-design/esp-dc-design-027-management/)
- [HPE Certification Exams Policies](https://certification-learning.hpe.com/tr/certification-exams)
- [Pearson VUE HPE Certification Testing Information](https://www.pearsonvue.com/us/en/hpe.html)

### Independent Third-Party Practice Resource

- [CertsPrime](https://www.certsprime.com/) and the [CertsPrime HPE7-A12 preparation page](https://www.certsprime.com/hp/hpe7-a12) are referenced in `index.html` strictly as independent third-party practice resources unaffiliated with and unendorsed by Hewlett Packard Enterprise.

## Notice

This repository is an independent educational reference not affiliated with, sponsored by, or endorsed by Hewlett Packard Enterprise. Verify current exam blueprints, pricing, and policies directly with HPE prior to scheduling.
