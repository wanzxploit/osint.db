# 🕵️‍♂️ OSINT Tool Collection

Daftar lengkap **ratusan tools OSINT** yang sudah teruji dan berfungsi untuk kebutuhan intelligence gathering, reconnaissance, forensic digital, dan threat intelligence. Setiap tools menyertakan **link resmi** (GitHub / Website) yang aktif.

---

## 📋 Daftar Isi

- [🛰️ Reconnaissance](#️-reconnaissance)
- [📧 Email Intelligence](#-email-intelligence)
- [👤 Username Intelligence](#-username-intelligence)
- [📱 Phone Intelligence](#-phone-intelligence)
- [🏢 Company Intelligence](#-company-intelligence)
- [💻 GitHub Intelligence](#-github-intelligence)
- [☁ Cloud Intelligence](#-cloud-intelligence)
- [🌐 Domain & IP Intelligence](#-domain--ip-intelligence)
- [🔗 URL & Link Analysis](#-url--link-analysis)
- [🗺 Geolocation](#-geolocation)
- [📸 Image Intelligence](#-image-intelligence)
- [🎥 Video Intelligence](#-video-intelligence)
- [📄 Document & Metadata Intelligence](#-document--metadata-intelligence)
- [📰 Archive & Search](#-archive--search)
- [🛡 Threat Intelligence](#-threat-intelligence)
- [🔒 Dark Web & Cryptocurrency](#-dark-web--cryptocurrency)
- [📡 Social Media Intelligence (SOCMINT)](#-social-media-intelligence-socmint)
- [🌍 News & Journalism](#-news--journalism)
- [🕸️ Framework & Automation](#️-framework--automation)
- [🧰 Utility & Helper Tools](#-utility--helper-tools)
- [📖 OSINT Resources & Guides](#-osint-resources--guides)

---

## 🛰️ Reconnaissance

### Passive Recon

| Tool | Deskripsi |
|------|-----------|
| [**theHarvester**](https://github.com/laramies/theHarvester) | Mengumpulkan email, subdomain, IP dari search engine, PGP keys, dan SHODAN |
| [**Amass**](https://github.com/owasp-amass/amass) | Framework OWASP untuk network mapping, subdomain enumeration, dan asset discovery |
| [**Subfinder**](https://github.com/projectdiscovery/subfinder) | Passive subdomain enumerator cepat dengan banyak sumber data |
| [**Assetfinder**](https://github.com/tomnomnom/assetfinder) | Mencari subdomain dan asset dari berbagai sumber publik |
| [**Findomain**](https://github.com/Findomain/Findomain) | Subdomain enumerator menggunakan Certificate Transparency logs dan API |
| [**Chaos**](https://chaos.projectdiscovery.io) | Dataset subdomain dari ProjectDiscovery yang bisa diquery |
| [**BBOT**](https://github.com/blacklanternsecurity/bbot) | OSINT automation tool modular untuk bug bounty dan recon |
| [**ReconFTW**](https://github.com/six2dez/reconftw) | Recon automation tool yang mengintegrasikan banyak tools |
| [**OneForAll**](https://github.com/shmilylty/OneForAll) | Subdomain enumeration tool dengan banyak sumber data |
| [**DNSRecon**](https://github.com/darkoperator/dnsrecon) | DNS enumeration script untuk berbagai record DNS |
| [**Fierce**](https://github.com/mschwager/fierce) | DNS subdomain scanner dengan wordlist |
| [**dnsx**](https://github.com/projectdiscovery/dnsx) | DNS query tool multi-threaded dari ProjectDiscovery |
| [**shuffledns**](https://github.com/projectdiscovery/shuffledns) | Mass DNS resolver dengan wordlist |
| [**puredns**](https://github.com/d3mondev/puredns) | DNS resolver akurat untuk wildcard filtering |
| [**crt.sh**](https://crt.sh) | Certificate Transparency log lookup |
| [**SecurityTrails**](https://securitytrails.com) | API historis DNS dan domain intelligence |
| [**VirusTotal**](https://virustotal.com) | Analisis file, URL, domain, dan IP dengan banyak engine |
| [**Censys**](https://censys.io) | Internet asset discovery dan certificate transparency |
| [**Shodan**](https://shodan.io) | Search engine untuk perangkat yang terhubung ke internet |
| [**FOFA**](https://fofa.info) | Cyberspace search engine berbasis aturan |
| [**ZoomEye**](https://zoomeye.org) | Search engine untuk perangkat jaringan dan service |
| [**Hunter How**](https://hunter.how) | Threat intelligence dan domain profiling |
| [**Netlas**](https://netlas.io) | Search engine untuk internet assets |
| [**LeakIX**](https://leakix.net) | Search engine untuk data leaks dan open ports |
| [**BinaryEdge**](https://binaryedge.io) | Threat intelligence dan internet scanning |
| [**RapidDNS**](https://rapiddns.io) | DNS query tool cepat dengan antarmuka web |
| [**DNSDumpster**](https://dnsdumpster.com) | DNS recon dan domain research tool |
| [**SubdomainCenter**](https://subdomain.center) | Database subdomain terpusat |
| [**Omnisint**](https://omnisint.io) | API pencarian subdomain dan IP terintegrasi |
| [**CertSpotter**](https://sslmate.com/certspotter) | Certificate Transparency log monitor dari SSLMate |
| [**Google Transparency Report**](https://transparencyreport.google.com) | Laporan transparansi Google untuk sertifikat |
| [**HackerTarget**](https://hackertarget.com) | Online vulnerability scanners dan network intelligence |
| [**FullHunt**](https://fullhunt.io) | Attack surface security platform |
| [**Onyphe**](https://onyphe.io) | Cyber defense search engine |
| [**CriminalIP**](https://criminalip.io) | Specialized Cyber Threat Intelligence search engine |

### Active Recon

| Tool | Deskripsi |
|------|-----------|
| [**Nmap**](https://nmap.org) | Network scanner legendaris untuk port scanning dan service detection |
| [**RustScan**](https://github.com/RustScan/RustScan) | Port scanner super cepat (dalam hitungan detik) ditulis di Rust |
| [**Naabu**](https://github.com/projectdiscovery/naabu) | Port scanner cepat dari ProjectDiscovery |
| [**Masscan**](https://github.com/robertdavidgraham/masscan) | Port scanner tercepat yang bisa memindai seluruh internet |
| [**httpx**](https://github.com/projectdiscovery/httpx) | HTTP probing tool untuk mendeteksi server web yang aktif |
| [**httprobe**](https://github.com/tomnomnom/httprobe) | Tool untuk memvalidasi domain yang merespon HTTP/HTTPS |
| [**WhatWeb**](https://github.com/urbanadventurer/WhatWeb) | Identifikasi teknologi website |
| [**Wappalyzer**](https://www.wappalyzer.com) | Ekstensi browser untuk identifikasi stack teknologi website |
| [**BuiltWith**](https://builtwith.com) | Profiler teknologi website yang komprehensif |
| [**Aquatone**](https://github.com/michenriksen/aquatone) | Screenshot otomatis untuk banyak website |
| [**GoWitness**](https://github.com/sensepost/gowitness) | Screenshot website dengan Golang, output dalam format report |
| [**Katana**](https://github.com/projectdiscovery/katana) | Web crawler cepat dari ProjectDiscovery |
| [**Hakrawler**](https://github.com/hakluke/hakrawler) | Fast web crawler untuk endpoint discovery |
| [**Photon**](https://github.com/s0md3v/Photon) | Crawler untuk extraction URL, email, social media, dll |
| [**gau**](https://github.com/lc/gau) | Get All URLs — mengambil URL dari Wayback, AlienVault, CommonCrawl |
| [**waybackurls**](https://github.com/tomnomnom/waybackurls) | Mengambil URL dari Wayback Machine |
| [**ParamSpider**](https://github.com/devanshbatham/ParamSpider) | Menemukan parameter GET/POST dari web crawling |
| [**Arjun**](https://github.com/s0md3v/Arjun) | Parameter discovery tool untuk endpoint web |
| [**Gospider**](https://github.com/jaeles-project/gospider) | Fast web spider yang fokus pada asset discovery |
| [**Feroxbuster**](https://github.com/epi052/feroxbuster) | Directory/file brute force tool dengan recursion |
| [**Dirb**](https://github.com/v0re/dirb) | Directory brute force scanner |
| [**Dirsearch**](https://github.com/maurosoria/dirsearch) | Advanced directory brute forcing tool |
| [**Gobuster**](https://github.com/OJ/gobuster) | Tool untuk directory/file dan DNS subdomain brute force |
| [**WFuzz**](https://github.com/xmendez/wfuzz) | Web fuzzer untuk parameter, directory, dan file brute force |
| [**FFuF**](https://github.com/ffuf/ffuf) | Fast web fuzzer yang sangat fleksibel |
| [**Nuclei**](https://github.com/projectdiscovery/nuclei) | Vulnerability scanner berbasis template dari ProjectDiscovery |
| [**Jaeles**](https://github.com/jaeles-project/jaeles) | Template-based web scanner untuk bug bounty |

---

## 📧 Email Intelligence

| Tool | Deskripsi |
|------|-----------|
| [**Holehe**](https://github.com/megadose/holehe) | Cek registrasi email di berbagai layanan online |
| [**h8mail**](https://github.com/khast3x/h8mail) | Email OSINT dan breach hunting tool |
| [**GHunt**](https://github.com/mxrch/GHunt) | Google account intelligence — dapatkan info dari email Google |
| [**Epieos**](https://epieos.com) | Email lookup tool untuk menemukan akun terdaftar |
| [**EmailRep**](https://emailrep.io) | API reputasi email — cek jika email terlibat spam/breach |
| [**Hunter.io**](https://hunter.io) | Mencari email terkait domain tertentu |
| [**Phonebook.cz**](https://phonebook.cz) | Search engine untuk email, domain, dan URL dari IntelX |
| [**DeHashed**](https://dehashed.com) | Search engine breach data untuk mencari email/username |
| [**LeakCheck**](https://leakcheck.io) | Database breach lookup untuk email dan password |
| [**Hudson Rock**](https://hudsonrock.com) | Infostealer malware intelligence — cek kompromi kredensial |
| [**IntelligenceX**](https://intelx.io) | Search engine untuk data leaks, email, domain dari dark web |
| [**HaveIBeenPwned**](https://haveibeenpwned.com) | Cek apakah email atau password pernah dibocorkan |
| [**Snusbase**](https://snusbase.com) | Database breach lookup multi-fitur |
| [**BreachDirectory**](https://breachdirectory.org) | Cari email dalam database breach publik |
| [**LeakPeek**](https://leakpeek.com) | Database leak lookup tool |
| [**IntelX**](https://intelx.io) | Dark web dan breach data search engine |
| [**LeakOSINT**](https://github.com/khast3x/LeakOSINT) | OSINT tool untuk mencari data breach |
| [**OTX (AlienVault OTX)**](https://otx.alienvault.com) | Threat intelligence dengan pencarian IOC termasuk email |
| [**Snov.io**](https://snov.io) | Email finder dan verifier untuk B2B |
| [**VoilaNorbert**](https://voilanorbert.com) | Email finder berdasarkan nama domain |
| [**Anymail Finder**](https://anymailfinder.com) | Prospecting email finder tool |
| [**Melissa**](https://melissa.com) | Email verification dan data quality tools |
| [**VerifyEmailAddress**](https://verifyemailaddress.org) | Free email verification service |
| [**MailTester**](https://mailtester.com) | Cek validitas alamat email |
| [**SpyDialer**](https://spydialer.com) | Reverse email lookup (juga support phone) |
| [**EmailFormat**](https://email-format.com) | Cari format email yang digunakan perusahaan |
| [**Skymem**](https://skymem.info) | Email address extractor dari web |
| [**EmailExtractor**](https://github.com/malbrain/EmailExtractor) | Extract email dari halaman web |
| [**RocketReach**](https://rocketreach.co) | Email dan contact discovery untuk profesional |
| [**Lusha**](https://lusha.com) | Contact intelligence untuk sales dan recruiting |
| [**ContactOut**](https://contactout.com) | Email finder dari profil LinkedIn |
| [**Tomba**](https://tomba.io) | Email finder dan verifier |
| [**ClearBit**](https://clearbit.com) | Email enrichment dan company data API |

---

## 👤 Username Intelligence

| Tool | Deskripsi |
|------|-----------|
| [**Sherlock**](https://github.com/sherlock-project/sherlock) | Cari username di ratusan social network sekaligus |
| [**Maigret**](https://github.com/soxoj/maigret) | Sherlock yang lebih modern — support 2500+ situs |
| [**WhatsMyName**](https://whatsmyname.app) | Database presisi tinggi untuk cek username di berbagai platform |
| [**Blackbird**](https://github.com/p1ngul1n0/blackbird) | Username lookup tool cepat dengan banyak platform |
| [**Nexfil**](https://github.com/thewhiteh4t/nexfil) | OSINT username checker dengan 350+ situs |
| [**Snoop**](https://github.com/snooppr/snoop) | Username reconnaissance tool |
| [**Social Analyzer**](https://github.com/qeeqbox/social-analyzer) | Analisis profil media sosial dari username |
| [**UserSearch**](https://usersearch.org) | Cari username di berbagai platform sekaligus |
| [**UserRecon**](https://github.com/thelinuxchoice/userrecon) | Tool untuk menemukan username di social media |
| [**User Scanner**](https://github.com/FlameOfIgnis/User-Scanner) | Scanner username di 300+ platform |
| [**InstantUsername**](https://instantusername.com) | Cek ketersediaan username di 100+ situs |
| [**Namechk**](https://namechk.com) | Cek ketersediaan username di banyak platform |
| [**Namecheckup**](https://namecheckup.com) | Username availability checker |
| [**KnowEm**](https://knowem.com) | Username search di 500+ platform sosial |
| [**IDCrawl**](https://idcrawl.com) | Search engine untuk username, email, dan nama |
| [**PeekYou**](https://peekyou.com) | People search engine berdasarkan username/nama |
| [**Webmii**](https://webmii.com) | Aggregator informasi publik dari username/nama |
| [**CheckUser**](https://checkuser.org) | Cek username di berbagai situs, fokus privacy |
| [**Alias**](https://github.com/JDemler/alias) | OSINT tool untuk mencari alias/screenname |
| [**SocialSearcher**](https://social-searcher.com) | Free social media search engine |
| [**Social Mention**](https://socialmention.com) | Real-time social media search dan analysis |
| [**Mention**](https://mention.com) | Social listening tool untuk username/brand monitoring |
| [**BrandSnitch**](https://brandsnitch.com) | Username availability checker di banyak platform |
| [**Namevine**](https://namevine.com) | Brand monitoring untuk username di sosial media |
| [**socid-extractor**](https://github.com/soxoj/socid-extractor) | Extract social media accounts dari berbagai sumber |

---

## 📱 Phone Intelligence

| Tool | Deskripsi |
|------|-----------|
| [**PhoneInfoga**](https://github.com/sundowndev/phoneinfoga) | Phone number OSINT — cari informasi dari nomor telepon |
| [**NumVerify**](https://numverify.com) | API validasi nomor telepon dengan lokasi dan carrier |
| [**Twilio Lookup**](https://twilio.com/lookup) | API untuk mendapatkan informasi nomor telepon |
| [**Sync.me**](https://sync.me) | Caller ID dan spam detection (crowdsourced) |
| [**Truecaller**](https://truecaller.com) | Caller ID, spam blocking, dan reverse phone lookup |
| [**LibPhoneNumber**](https://github.com/google/libphonenumber) | Library Google untuk parsing, formatting, dan validasi nomor |
| [**OpenCNAM**](https://opencnam.com) | Reverse phone lookup API untuk nama caller |
| [**EmobileTracker**](https://emobiletracker.com) | Mobile number tracker dan locator |
| [**CarrierLookup**](https://carrierlookup.com) | Cari provider/carrier dari nomor telepon |
| [**Local Area Code**](https://localareacode.com) | Informasi area code dan lokasi nomor telepon |
| [**FreeCarrierLookup**](https://freecarrierlookup.com) | Cari carrier dari nomor telepon gratis |
| [**PhoneValidator**](https://phonevalidator.com) | Validasi format dan tipe nomor telepon |
| [**ReversePhoneCheck**](https://reversephonecheck.com) | Reverse phone directory |
| [**SpyDialer**](https://spydialer.com) | Reverse phone lookup (juga support email) |
| [**Zlookup**](https://zlookup.com) | Free reverse phone lookup API |
| [**WhoCallsMe**](https://whocallsme.com) | Community-based phone number lookup |
| [**PhoneLookup**](https://phonelookup.com) | Identifikasi spam dan informasi nomor |
| [**CallFilter**](https://callfilter.app) | Caller ID dan phone tracking tool |
| [**NumLookup**](https://numlookup.com) | Free reverse phone number lookup |
| [**Whitepages**](https://whitepages.com) | Phone directory dan reverse lookup |
| [**AnyWho**](https://anywho.com) | Free people search dan reverse phone |
| [**Zero Eight**](https://github.com/wanzxploit/zero-eight) | Cari provider dan area registrasi nomor telepon Indonesia via CLI |

---

## 🏢 Company Intelligence

| Tool | Deskripsi |
|------|-----------|
| [**OpenCorporates**](https://opencorporates.com) | Database perusahaan terbuka terbesar di dunia |
| [**Crunchbase**](https://crunchbase.com) | Database startup, funding, dan profil perusahaan |
| [**ZoomInfo**](https://zoominfo.com) | B2B contact database dan company intelligence |
| [**RocketReach**](https://rocketreach.co) | Company dan employee email discovery |
| [**Apollo**](https://apollo.io) | Sales intelligence dengan data perusahaan |
| [**Hunter.io**](https://hunter.io) | Email perusahaan berbasis domain |
| [**WhoisXML**](https://whoisxmlapi.com) | WHOIS intelligence dan domain company data |
| [**BuiltWith**](https://builtwith.com) | Technology profiling untuk perusahaan |
| [**SecurityTrails**](https://securitytrails.com) | Corporate DNS dan infrastructure intelligence |
| [**LinkedIn Sales Navigator**](https://linkedin.com/sales) | Social selling dan company research |
| [**Owler**](https://owler.com) | Company competitive intelligence dan news |
| [**Kompass**](https://kompass.com) | B2B company directory global |
| [**Dun & Bradstreet**](https://dnb.com) | Business credit, risk, dan data perusahaan |
| [**Glassdoor**](https://glassdoor.com) | Company reviews, salary, dan culture info |
| [**The Org**](https://theorg.com) | Company org chart dan struktur organisasi |
| [**PitchBook**](https://pitchbook.com) | Financial data dan M&A intelligence |
| [**Mattermark**](https://mattermark.com) | Company growth intelligence |
| [**SimilarWeb**](https://similarweb.com) | Website traffic dan company digital analytics |
| [**Datanyze**](https://datanyze.com) | Technographic dan account intelligence |
| [**Clearbit**](https://clearbit.com) | Company API enrichment |
| [**LeadIQ**](https://leadiq.com) | Sales prospecting dengan company data |
| [**Wiza**](https://wiza.co) | Email extraction dari LinkedIn |
| [**SignalHire**](https://signalhire.com) | B2B contact database |
| [**CorporationWiki**](https://corporationwiki.com) | Corporate entity dan subsidiari data |
| [**EDGAR (SEC)**](https://sec.gov/edgar) | Filing perusahaan publik AS |
| [**Companies House**](https://gov.uk/companieshouse) | UK company registry |
| [**ASIC Connect**](https://asic.gov.au) | Australian company registry |
| [**OECD Corporate Tax**](https://oecd.org/tax) | Pajak dan struktur perusahaan global |
| [**OpenLEI**](https://openlei.com) | Legal Entity Identifier lookup |
| [**GLEIF**](https://gleif.org) | Global LEI foundation |

---

## 💻 GitHub Intelligence

| Tool | Deskripsi |
|------|-----------|
| [**GitLeaks**](https://github.com/gitleaks/gitleaks) | Deteksi hardcoded secrets di repositori Git |
| [**TruffleHog**](https://github.com/trufflesecurity/trufflehog) | Scan GitHub untuk exposed credentials dan secrets |
| [**GitDorker**](https://github.com/obheda12/GitDorker) | Tool untuk GitHub dorking dan exposed data |
| [**GitRecon**](https://github.com/GitRecon/GitRecon) | OSINT automation untuk GitHub |
| [**GitFive**](https://github.com/mxrch/GitFive) | Investigasi kontributor GitHub dan metadata |
| [**RepoSupervisor**](https://github.com/auth0/repo-supervisor) | Monitoring repositori GitHub untuk secrets |
| [**GitMiner**](https://github.com/UnkL4b/GitMiner) | Tool pencarian exposed data di GitHub |
| [**SecretFinder**](https://github.com/m4ll0k/SecretFinder) | Deteksi API keys, tokens, dan secrets di source code |
| [**RepoHunt**](https://github.com/0xPugazh/Repo-Hunt) | Mencari repositori GitHub yang relevan dengan keyword |
| [**GitHound**](https://github.com/tillson/git-hound) | Pattern-based GitHub secret detection |
| [**GitGot**](https://github.com/BishopFox/GitGot) | Semi-automated GitHub reconnaissance |
| [**TruffleHog v3**](https://github.com/trufflesecurity/trufflehog) | Versi terbaru dengan deteksi entropy dan regex |
| [**ShhGit**](https://github.com/eth0izzle/shhgit) | Deteksi secrets di Git repositori |
| [**GitGuardian**](https://gitguardian.com) | Platform secret detection dan remediation |
| [**GitHub Dorking Tool**](https://github.com/m4ll0k/GitDorker) | Automation untuk GitHub dork queries |
| [**CodeQL**](https://github.com/github/codeql) | Semantic code analysis engine dari GitHub |
| [**GitHub Search**](https://github.com/search) | Pencarian langsung via GitHub search |
| [**Github-profile-achievements**](https://github.com/ryo-ma/github-profile-achievements) | Cek achievements profil GitHub |
| [**Dependabot**](https://github.com/dependabot) | Dependency vulnerability scanner |

---

## ☁ Cloud Intelligence

| Tool | Deskripsi |
|------|-----------|
| [**S3Scanner**](https://github.com/sa7mon/S3Scanner) | Cari bucket S3 yang terbuka/misconfigured |
| [**CloudBrute**](https://github.com/0xsha/CloudBrute) | Cloud infrastructure discovery tool |
| [**CloudFail**](https://github.com/m0rtem/CloudFail) | Tool untuk menemukan IP asli di balik Cloudflare |
| [**MicroBurst**](https://github.com/NetSPI/MicroBurst) | Azure exploitation dan enumeration toolkit |
| [**DumpsterDiver**](https://github.com/securing/DumpsterDiver) | Analisis file untuk sensitive data di cloud storage |
| [**GCPBucketBrute**](https://github.com/RhinoSecurityLabs/GCPBucketBrute) | Brute force nama bucket Google Cloud Storage |
| [**AWSBucketDump**](https://github.com/jordanpotti/AWSBucketDump) | Dump file dari bucket S3 publik |
| [**AzureHound**](https://github.com/BloodHoundAD/AzureHound) | BloodHound untuk Azure — mapping hubungan dan permission |
| [**CloudEnum**](https://github.com/initstring/cloud_enum) | Cloud service enumeration tool |
| [**CloudScraper**](https://github.com/jordanpotti/CloudScraper) | Tool untuk scraping cloud storage |
| [**S3-Inspector**](https://github.com/clarketm/s3-inspector) | Cek permission bucket S3 |
| [**BucketFinder**](https://github.com/FooBallZ/bucket_finder) | Find open S3 buckets |
| [**CloudSploit**](https://github.com/aquasecurity/cloudsploit) | Open-source cloud security scanning |
| [**Prowler**](https://github.com/prowler-cloud/prowler) | AWS security best practices assessment tool |
| [**ScoutSuite**](https://github.com/nccgroup/ScoutSuite) | Multi-cloud security auditing tool |
| [**SkyArk**](https://github.com/cyberark/SkyArk) | AWS Shadow Admin discovery tool |
| [**CloudMapper**](https://github.com/duo-labs/cloudmapper) | AWS visual network mapping |
| [**Cartography**](https://github.com/lyft/cartography) | Graph-based cloud infrastructure mapping |
| [**Checkov**](https://github.com/bridgecrewio/checkov) | Infrastructure-as-code static analysis |
| [**Terrascan**](https://github.com/tenable/terrascan) | IaC security scanner |
| [**Trivy**](https://github.com/aquasecurity/trivy) | Vulnerability scanner untuk cloud dan container |
| [**CloudFox**](https://github.com/BishopFox/cloudfox) | Cloud pentesting toolkit |
| [**Grayhat Warfare**](https://buckets.grayhatwarfare.com) | Open bucket search engine |

---

## 🌐 Domain & IP Intelligence

| Tool | Deskripsi |
|------|-----------|
| [**Whois**](https://who.is) | Lookup informasi registrasi domain |
| [**WhoisXML API**](https://whoisxmlapi.com) | API whois intelligence komprehensif |
| [**RDAP**](https://rdap.net) | Registry Data Access Protocol untuk domain lookup |
| [**Reverse IP Lookup**](https://viewdns.info) | Cari domain lain yang menggunakan IP yang sama |
| [**IPinfo**](https://ipinfo.io) | Database informasi IP geolokasi dan ASN |
| [**MaxMind GeoIP**](https://maxmind.com) | GeoIP lookup database |
| [**ipapi**](https://ipapi.com) | IP geolocation dan threat intelligence API |
| [**ip2location**](https://ip2location.com) | IP geolocation database dan tools |
| [**IPVoid**](https://ipvoid.com) | IP address reputation checker |
| [**AbuseIPDB**](https://abuseipdb.com) | Database IP abusif dan threat intelligence |
| [**BGPView**](https://bgpview.io) | BGP routing data dan ASN lookup |
| [**PeeringDB**](https://peeringdb.com) | Network peering dan interconnection data |
| [**DNSlytics**](https://dnslytics.com) | Domain, IP, dan network intelligence |
| [**DomainTools**](https://domaintools.com) | Komprehensif domain research platform |
| [**Whoisology**](https://whoisology.com) | Whois history dan reverse whois |
| [**Domaintools Iris**](https://domaintools.com/iris) | Investigasi domain dengan visualisasi |
| [**SpyOnWeb**](https://spyonweb.com) | Cari domain yang berbagi IP, Google Analytics ID, dll |
| [**ViewDNS**](https://viewdns.info) | Multiple DNS tools dan reverse IP lookup |
| [**YouGetSignal**](https://yougetsignal.com) | Reverse IP domain lookup dan tools |
| [**MXToolbox**](https://mxtoolbox.com) | DNS lookup dan email server diagnostics |
| [**DNSWatch**](https://dnswatch.info) | DNS monitoring dan lookup tools |
| [**IntoDNS**](https://intodns.com) | DNS health check dan analisis |
| [**Robtex**](https://robtex.com) | DNS, IP, ASN intelligence dan routing data |
| [**URLScan.io**](https://urlscan.io) | Screenshot dan analisis keamanan website |
| [**Sucuri SiteCheck**](https://sitecheck.sucuri.net) | Website malware dan security scanner |
| [**ScanFactory**](https://scanfactory.io) | Web security scanner |
| [**Quttera**](https://quttera.com) | Malicious website scanner |
| [**DNSDB**](https://dnsdb.io) | Passive DNS database oleh FarSight |
| [**RIPEDomain**](https://ripedomain.net) | Tool analisis domain |

---

## 🔗 URL & Link Analysis

| Tool | Deskripsi |
|------|-----------|
| [**gau**](https://github.com/lc/gau) | Get All URLs dari multiple sources |
| [**waybackurls**](https://github.com/tomnomnom/waybackurls) | Ekstrak URL dari Wayback Machine |
| [**Katana**](https://github.com/projectdiscovery/katana) | Fast web crawler untuk URL extraction |
| [**Hakrawler**](https://github.com/hakluke/hakrawler) | URL discovery dari web crawling |
| [**Photon**](https://github.com/s0md3v/Photon) | Web crawler untuk extraction URL, email, dll |
| [**Gospider**](https://github.com/jaeles-project/gospider) | Spider untuk menemukan endpoint dan asset |
| [**ParamSpider**](https://github.com/devanshbatham/ParamSpider) | Menemukan parameter URL |
| [**Arjun**](https://github.com/s0md3v/Arjun) | Parameter discovery tool |
| [**Feroxbuster**](https://github.com/epi052/feroxbuster) | URL brute force discovery |
| [**Unfurl**](https://github.com/tomnomnom/unfurl) | Parse dan analisis URL untuk extraction komponen |
| [**urlcrazy**](https://github.com/urbanadventurer/urlcrazy) | Typosquatting dan URL fuzzing |
| [**URLChecker**](https://urlchecker.org) | Cek status dan redirect URL |
| [**LinkChecker**](https://linkchecker.github.io/linkchecker) | Validasi link dan URL analysis |
| [**WhereGoes**](https://wheregoes.com) | Track redirect chain URL |
| [**UntrustMe**](https://untrust.me) | Redirect tracker dan link safety checker |
| [**CheckShortURL**](https://checkshorturl.com) | Expand URL pendek untuk lihat tujuan asli |
| [**Unshorten.link**](https://unshorten.link) | URL shortener expander |
| [**GetLinkInfo**](https://getlinkinfo.com) | Analisis metadata dan tujuan link |

---

## 🗺 Geolocation

| Tool | Deskripsi |
|------|-----------|
| [**Wigle**](https://wigle.net) | Database SSID nirkabel global untuk geolokasi |
| [**CellMapper**](https://cellmapper.net) | Mapping tower seluler dan coverage |
| [**OpenCellID**](https://opencellid.org) | Database open cell tower location |
| [**BSSID Lookup**](https://bssid-lookup.com) | Cari lokasi berdasarkan MAC address WiFi |
| [**GPS Visualizer**](https://gpsvisualizer.com) | Visualisasi data GPS dan geolokasi |
| [**GeoSpy**](https://geospy.ai) | AI-based image geolocation intelligence |
| [**SunCalc**](https://suncalc.org) | Hitung posisi matahari untuk verifikasi waktu/foto |
| [**Google Earth**](https://earth.google.com) | Satellite imagery dan geospatial analysis |
| [**OpenStreetMap**](https://openstreetmap.org) | Open-source map data global |
| [**GeoLite2**](https://dev.maxmind.com/geoip) | MaxMind free IP geolocation database |
| [**IP2Location**](https://ip2location.com) | IP geolocation lookup |
| [**WhatIsMyIP**](https://whatismyip.com) | IP checker dengan info lokasi |
| [**IPLocation**](https://iplocation.com) | IP geolocation tools |
| [**GPS Coordinates**](https://gps-coordinates.net) | Converter dan lookup koordinat |
| [**LatLong.net**](https://latlong.net) | Find latitude dan longitude dari alamat |
| [**GeoNames**](https://geonames.org) | Geographical database dengan 10M+ entries |
| [**Nominatim**](https://nominatim.openstreetmap.org) | OpenStreetMap geocoding API |
| [**MapQuest**](https://mapquest.com) | Geocoding dan mapping tools |
| [**Here Maps**](https://here.com) | Location intelligence dan geocoding |
| [**Bing Maps**](https://bing.com/maps) | Geocoding dan spatial data services |
| [**ArcGIS**](https://arcgis.com) | Esri GIS platform untuk spatial analysis |
| [**QGIS**](https://qgis.org) | Open-source GIS desktop application |
| [**Google My Maps**](https://google.com/maps/d) | Custom map creation dan geodata visualization |
| [**GeoJSON.io**](https://geojson.io) | GeoJSON data viewer dan editor |
| [**What3Words**](https://what3words.com) | Location encoding dengan 3 kata unik |
| [**Plus Codes**](https://plus.codes) | Open Location Code oleh Google |
| [**OSMCha**](https://osmcha.org) | OpenStreetMap changeset analyzer |
| [**Overpass Turbo**](https://overpass-turbo.eu) | OSM query tool untuk geodata |
| [**SASPlanet**](https://sasplanet.org) | Satellite imagery viewer dan downloader |
| [**Sentinel Hub**](https://sentinel-hub.com) | EO (Earth Observation) browser |
| [**Google Maps**](https://maps.google.com) | Street view, maps, dan geolocation |

---

## 📸 Image Intelligence

| Tool | Deskripsi |
|------|-----------|
| [**ExifTool**](https://exiftool.org) | Baca/edit metadata EXIF dari foto |
| [**Exiv2**](https://exiv2.org) | Image metadata manipulation library dan CLI |
| [**TinEye**](https://tineye.com) | Reverse image search engine |
| [**Google Lens**](https://lens.google.com) | AI-based visual search dan object recognition |
| [**Yandex Images**](https://yandex.com/images) | Reverse image search via Yandex |
| [**PimEyes**](https://pimeyes.com) | Face search engine dengan AI facial recognition |
| [**FaceCheck.ID**](https://facecheck.id) | Reverse face search dan identity verification |
| [**Bing Visual Search**](https://bing.com/visualsearch) | Microsoft reverse image search |
| [**Metadata2Go**](https://metadata2go.com) | Online metadata extractor untuk file |
| [**Forensically**](https://29a.ch/photo-forensics) | Web-based image forensic analysis tool |
| [**FotoForensics**](https://fotoforensics.com) | Error level analysis (ELA) dan forensic imaging |
| [**JPEGsnoop**](https://github.com/ImpulseAdventure/JPEGsnoop) | JPEG decoder dan analisis compression |
| [**Ghiro**](https://github.com/GhiroTeam/ghiro) | Automated image forensics tool |
| [**ImageMagick**](https://imagemagick.org) | CLI tool untuk image manipulation dan identifikasi |
| [**StegExpose**](https://github.com/b3dk7/StegExpose) | Deteksi steganography di image |
| [**StegHide**](https://github.com/topics/steganography) | Tool steganography detection |
| [**zsteg**](https://github.com/zed-0xff/zsteg) | Deteksi data tersembunyi di PNG/BMP |
| [**StegSolve**](https://github.com/zardus/ctf-tools) | Steganography analysis tool |
| [**Outguess**](https://github.com/crorvick/outguess) | Steganography detection dan extraction |
| [**JPEGX**](https://jpegx.com) | JPEG corruption dan metadata analyzer |
| [**CamTrace**](https://camtrace.org) | Camera serial number lookup |
| [**Jeffreys Image Metadata**](https://exif.regex.info) | Online EXIF viewer |
| [**ImgOps**](https://imgops.com) | Operasi image processing via CLI dan web |
| [**ImageIdentify**](https://imageidentify.com) | Identifikasi objek di gambar dengan AI |
| [**DiffChecker**](https://diffchecker.com) | Image comparison tool |
| [**Search By Image**](https://github.com/dessant/search-by-image) | Chrome extension untuk image search |
| [**CamFind**](https://camfindapp.com) | Mobile visual search engine |

---

## 🎥 Video Intelligence

| Tool | Deskripsi |
|------|-----------|
| [**InVID**](https://www.invid-project.eu) | Verifikasi video dan screenshot analysis |
| [**YouTube DataViewer**](https://youtubedataviewer.com) | Ekstrak metadata dari YouTube video |
| [**Amnesty YouTube DataViewer**](https://citizenevidence.amnestyusa.org) | YouTube metadata extraction oleh Amnesty |
| [**FFmpeg Metadata**](https://ffmpeg.org) | Ekstrak dan analisis metadata video |
| [**MediaInfo**](https://mediaarea.net/en/MediaInfo) | Analisis file video dan audio |
| [**YouTube Geofind**](https://mattw.io/youtube-geofind) | Cari YouTube video berdasarkan lokasi |
| [**YouTube Transcript**](https://youtubetranscript.com) | Ekstrak transcript/subtitle dari video |
| [**YT-DLP**](https://github.com/yt-dlp/yt-dlp) | YouTube video downloader dengan metadata |
| [**FFprobe**](https://ffmpeg.org/ffprobe.html) | Media probing tool dari FFmpeg |
| [**ExifTool (Video)**](https://exiftool.org) | Ekstrak metadata dari video |
| [**Google Video Indexer**](https://videoindexer.ai) | Video indexing dan search |
| [**VLC Media Info**](https://videolan.org) | Media information viewer |
| [**Video Inspector**](https://video-inspector.com) | Video codec dan metadata inspector |
| [**Montage**](https://github.com/anthonymontagne/montage) | Screenshot otomatis dari video |
| [**Holmes**](https://github.com/HolmesOSINT) | Video forensic tool |
| [**MediaConch**](https://mediaarea.net/MediaConch) | Implementation checker untuk format media |

---

## 📄 Document & Metadata Intelligence

| Tool | Deskripsi |
|------|-----------|
| [**ExifTool**](https://exiftool.org) | Baca/tulis metadata berbagai format file |
| [**PDFiD**](https://blog.didierstevens.com/programs/pdf-tools) | Analisis PDF untuk malicious content |
| [**PDF-Parser**](https://github.com/smalot/pdfparser) | Ekstrak teks dan metadata dari PDF |
| [**pdfinfo**](https://poppler.freedesktop.org) | Info metadata dari PDF (poppler utils) |
| [**Didier Stevens Tools**](https://blog.didierstevens.com/programs) | Koleksi tools untuk analisis dokumen |
| [**Oletools**](https://github.com/decalage2/oletools) | Analisis OLE2 (Office documents) |
| [**DocScrubber**](https://github.com/robincornelius/docscrubber) | Bersihkan metadata dari dokumen |
| [**MetadataCleaner**](https://metadatacleaner.bleb.be) | Hapus metadata dari file |
| [**Mat2**](https://0xacab.org/jvoisin/mat2) | Metadata removal tool |
| [**Bleachbit**](https://bleachbit.org) | File shredder dan metadata cleaner |
| [**Foremost**](https://github.com/korczis/foremost) | File carving dan recovery |
| [**Binwalk**](https://github.com/ReFirmLabs/binwalk) | Firmware analysis dan file extraction |
| [**Strings**](https://github.com/topics/strings) | Ekstrak string dari binary/file |
| [**HxD**](https://mh-nexus.de/en/hxd) | Hex editor untuk analisis file |
| [**ImHex**](https://github.com/WerWolv/ImHex) | Pattern-based hex editor modern |
| [**010 Editor**](https://sweetscape.com/010editor) | Professional hex editor dengan templates |
| [**OfficeMalScanner**](https://github.com/ctxis/OfficeMalScanner) | Scan dokumen Office untuk malware |
| [**Riff**](https://github.com/sysopfb/RIFF) | Malformed file analysis tool |
| [**TrID**](https://mark0.net/soft-trid-e.html) | File type identifier berbasis signature |

---

## 📰 Archive & Search

| Tool | Deskripsi |
|------|-----------|
| [**Wayback Machine**](https://web.archive.org) | Internet Archive — akses versi historis website |
| [**Archive.today**](https://archive.ph) | Web page snapshot dan archiving |
| [**Common Crawl**](https://commoncrawl.org) | Open repository web crawl data |
| [**Google Dork**](https://google.com) | Advanced Google search queries |
| [**Google Dork Database**](https://exploit-db.com/google-hacking-database) | Koleksi dork queries untuk OSINT |
| [**PunkSPIDER**](https://punkspider.io) | Google dorking automation tool |
| [**Pagodo**](https://github.com/opsdisk/pagodo) | Automated Google dorking |
| [**Bing Dork**](https://bing.com) | Advanced Bing search operators |
| [**Yandex**](https://yandex.com) | Search engine dengan kemampuan unik |
| [**DuckDuckGo**](https://duckduckgo.com) | Privacy-focused search engine |
| [**Brave Search**](https://search.brave.com) | Independent search engine |
| [**Mojeek**](https://mojeek.com) | Independent search engine dengan index sendiri |
| [**PublicWWW**](https://publicwww.com) | Search engine untuk source code dan CSS/JS |
| [**SearchCode**](https://searchcode.com) | Source code search engine |
| [**grep.app**](https://grep.app) | Cari teks di repositori publik |
| [**SearX**](https://searx.org) | Self-hosted metasearch engine |
| [**Startpage**](https://startpage.com) | Private search engine yang menggunakan Google |
| [**Qwant**](https://qwant.com) | Privacy-focused search engine Eropa |
| [**Swisscows**](https://swisscows.com) | Family-friendly search engine dengan semantic |
| [**MetaGer**](https://metager.org) | German metasearch engine |
| [**Gigablast**](https://gigablast.com) | Open-source search engine |
| [**Million Short**](https://millionshort.com) | Search tanpa top million sites |
| [**Carrot2**](https://search.carrot2.org) | Clustering search results engine |
| [**CiteSeerX**](https://citeseerx.ist.psu.edu) | Scientific literature digital library |
| [**Refseek**](https://refseek.com) | Academic search engine |
| [**Base (Bielefeld)**](https://base-search.net) | Academic search engine untuk web resources |
| [**Semantic Scholar**](https://semanticscholar.org) | AI-powered scientific paper search |
| [**Google Scholar**](https://scholar.google.com) | Academic literature search |
| [**Crossref**](https://crossref.org) | DOI registration dan metadata pencarian |
| [**WorldCat**](https://worldcat.org) | Global library catalog search |
| [**LibGen**](https://libgen.is) | Library Genesis — scientific articles dan books |
| [**Z-Library**](https://z-lib.io) | Digital library untuk articles dan ebooks |
| [**Sci-Hub**](https://sci-hub.se) | Akses scientific papers |
| [**PubChem**](https://pubchem.ncbi.nlm.nih.gov) | Chemical compound database |
| [**PubMed**](https://pubmed.ncbi.nlm.nih.gov) | Biomedical literature database |
| [**Google Trends**](https://trends.google.com) | Search interest analysis |
| [**Google Alerts**](https://alerts.google.com) | Email notification untuk keyword |

---

## 🛡 Threat Intelligence

| Tool | Deskripsi |
|------|-----------|
| [**VirusTotal**](https://virustotal.com) | Multi-AV scanner dan file/URL/domain analysis |
| [**AlienVault OTX**](https://otx.alienvault.com) | Open Threat Exchange — threat intelligence sharing |
| [**MalwareBazaar**](https://bazaar.abuse.ch) | Malware sample sharing platform |
| [**URLHaus**](https://urlhaus.abuse.ch) | URL abuse database |
| [**ThreatFox**](https://threatfox.abuse.ch) | IOC (Indicator of Compromise) sharing platform |
| [**Hybrid Analysis**](https://hybrid-analysis.com) | Automated malware analysis sandbox |
| [**Any.Run**](https://any.run) | Interactive malware analysis sandbox |
| [**Joe Sandbox**](https://joesandbox.com) | Deep malware analysis platform |
| [**GreyNoise**](https://greynoise.io) | Internet noise filtering and threat intelligence |
| [**AbuseIPDB**](https://abuseipdb.com) | IP reputation database |
| [**URLScan.io**](https://urlscan.io) | Website screenshot dan URL analysis |
| [**Pulsedive**](https://pulsedive.com) | Threat intelligence feed dan IOC search |
| [**MISP**](https://misp-project.org) | Malware Information Sharing Platform |
| [**YARA**](https://virustotal.github.io/yara) | Malware identification pattern matching |
| [**YARA-Rules**](https://github.com/Yara-Rules/rules) | Koleksi YARA rules publik |
| [**CAPA**](https://github.com/mandiant/capa) | Malware capability analyzer |
| [**FLOSS**](https://github.com/mandiant/flare-floss) | FireEye Labs Obfuscated String Solver |
| [**Volatility**](https://volatilityfoundation.org) | Memory forensic framework |
| [**Rekall**](https://github.com/google/rekall) | Memory forensic analysis tool |
| [**Autopsy**](https://autopsy.com) | Digital forensic platform |
| [**Sleuth Kit**](https://sleuthkit.org) | File system forensic analysis toolkit |
| [**PhotoRec**](https://photorec.com) | File recovery dan digital forensic |
| [**Guymager**](https://guymager.com) | Disk imaging tool |
| [**dcfldd**](https://github.com/resurrecting-open-source-projects/dcfldd) | Forensically sound dd |
| [**Cuckoo Sandbox**](https://cuckoosandbox.org) | Open-source malware analysis system |
| [**CAPEv2**](https://github.com/kevoreilly/CAPEv2) | Malware sandbox automation (Cuckoo fork) |
| [**ThreatConnect**](https://threatconnect.com) | Threat intelligence platform |
| [**Recorded Future**](https://recordedfuture.com) | AI-powered threat intelligence |
| [**Anomali ThreatStream**](https://anomali.com) | Threat intelligence platform |
| [**IBM X-Force**](https://exchange.xforce.ibmcloud.com) | Threat intelligence dan incident response |
| [**Cisco Talos**](https://talosintelligence.com) | Threat intelligence group |
| [**OpenCTI**](https://github.com/OpenCTI-Platform/opencti) | Open Cyber Threat Intelligence platform |
| [**Cortex**](https://github.com/TheHive-Project/Cortex) | Observable analysis engine untuk MISP/Hive |
| [**TheHive**](https://thehive-project.org) | Incident response platform |
| [**DFIRTrack**](https://github.com/dfir-tracker/dfir-track) | Incident response tracking tool |
| [**Timesketch**](https://timesketch.org) | Collaborative forensic timeline analysis |
| [**Plaso**](https://github.com/log2timeline/plaso) | Super timeline tool untuk log2timeline |
| [**Log2Timeline**](https://github.com/log2timeline/log2timeline) | Tool untuk membuat timeline dari log |
| [**KAPE**](https://kape.com) | Kroll Artifact Parser and Extractor |
| [**ThreatMiner**](https://threatminer.org) | Threat intelligence data mining |
| [**RiskIQ**](https://riskiq.com) | Attack surface dan threat intelligence |
| [**InQuest**](https://inquest.net) | Threat intelligence dan malware detection |

---

## 🔒 Dark Web & Cryptocurrency

| Tool | Deskripsi |
|------|-----------|
| [**Tor Browser**](https://torproject.org) | Anonymized browsing ke .onion sites |
| [**Ahmia**](https://ahmia.fi) | Search engine untuk .onion services |
| [**DarkSearch**](https://darksearch.io) | Dark web search engine |
| [**OnionScan**](https://github.com/s-rah/onionscan) | Analisis keamanan layanan Tor |
| [**Tor2Web**](https://tor2web.org) | Akses .onion tanpa Tor Browser |
| [**Tails**](https://tails.net) | Privacy-focused OS untuk dark web access |
| [**Whonix**](https://whonix.org) | Debian-based OS untuk anonymity |
| [**TorBot**](https://github.com/DedSecInside/TorBot) | Dark web crawler OSINT |
| [**OnionIngestor**](https://github.com/danielpancake/OnionIngestor) | Dark web monitoring tool |
| [**Hunchly**](https://hunch.ly) | Web capture tool untuk investigasi dark web |
| [**Blockchain.com Explorer**](https://blockchain.com/explorer) | Blockchain transaction explorer |
| [**Etherscan**](https://etherscan.io) | Ethereum blockchain explorer |
| [**OXT**](https://oxt.me) | Blockchain forensic analysis |
| [**Chainalysis**](https://chainalysis.com) | Cryptocurrency investigation platform |
| [**CipherTrace**](https://ciphertrace.com) | Crypto AML dan investigation |
| [**Elliptic**](https://elliptic.co) | Crypto asset risk management |
| [**Walletexplorer**](https://walletexplorer.com) | Wallet clustering dan tracking |
| [**BitcoinAbuse**](https://bitcoinabuse.com) | Database Bitcoin addresses terkait abuse |
| [**Crystal Blockchain**](https://crystalblockchain.com) | Crypto transaction analytics |
| [**TokenView**](https://tokenview.com) | Multi-chain blockchain explorer |
| [**TRM Labs**](https://trmlabs.com) | Crypto risk intelligence |
| [**CoinDesk**](https://coindesk.com) | Crypto news dan market data |
| [**CoinMarketCap**](https://coinmarketcap.com) | Crypto market capitalization data |
| [**CryptoScamDB**](https://cryptoscamdb.org) | Cryptocurrency scam database |
| [**Ransomwhere**](https://ransomwhe.re) | Ransomware payment tracking |
| [**BitcoinWhosWho**](https://bitcoinwhoswho.com) | Bitcoin address reputation |
| [**Blockstream.info**](https://blockstream.info) | Bitcoin block explorer |
| [**Blockchair**](https://blockchair.com) | Multi-blockchain search engine |
| [**BTC.com**](https://btc.com) | Bitcoin dan crypto explorer |
| [**Mempool**](https://mempool.space) | Bitcoin transaction visualizer |

---

## 📡 Social Media Intelligence (SOCMINT)

| Tool | Deskripsi |
|------|-----------|
| [**Twint**](https://github.com/twintproject/twint) | Twitter scraping tanpa API (legacy) |
| [**Nitter**](https://nitter.net) | Twitter front-end alternatif untuk scraping |
| [**TweetBeaver**](https://tweetbeaver.com) | Twitter analitik dan data extraction |
| [**Twitter Advanced Search**](https://twitter.com/search-advanced) | Advanced search operators Twitter |
| [**ExportComments**](https://exportcomments.com) | Ekstrak komentar Instagram |
| [**Instagram Scraper**](https://github.com/realsirjoe/instagram-scraper) | Scraping data profil dan post Instagram |
| [**InstaLooter**](https://github.com/althonos/InstaLooter) | Instagram media downloader |
| [**OSINTgram**](https://github.com/Datalux/Osintgram) | Instagram OSINT tool |
| [**Facebook Graph Search**](https://developers.facebook.com/docs/graph-api) | Facebook data discovery via Graph API |
| [**Stalkscan**](https://stalkscan.com) | Facebook profile scanner |
| [**TikTok Scraper**](https://github.com/drawrowfly/tiktok-scraper) | Scraping data TikTok |
| [**TikTok Downloader**](https://snaptik.app) | Download video TikTok tanpa watermark |
| [**Snapchat Map**](https://map.snapchat.com) | Snap Map untuk geolokasi (via web) |
| [**Reddit Scraper**](https://github.com/datastacknet/reddit-scraper) | Scraping data Reddit |
| [**Pushshift**](https://pushshift.io) | Reddit API dataset lengkap |
| [**Reddit User Analyzer**](https://reddit-user-analyser.netlify.app) | Analisis aktivitas user Reddit |
| [**Telegram Scraper**](https://github.com/th3unkn0n/Telegram-Scraper) | Scraping data channel dan grup Telegram |
| [**TelegramDB**](https://telegramdb.org) | Telegram channel search engine |
| [**Telepathy**](https://github.com/jordanwildon/Telepathy) | Telegram intelligence tool |
| [**Discord Scraper**](https://github.com/A3M4/YouTube-Report) | Scraping data Discord |
| [**Discord History Tracker**](https://github.com/chylex/Discord-History-Tracker) | Track history chat Discord |
| [**Discord Lookup**](https://discordlookup.com) | Cari user dan server Discord |
| [**WhatsApp OSINT**](https://whatsapp-osint.com) | Tools untuk WhatsApp intelligence |
| [**LinkedIn Scraper**](https://github.com/joeyism/linkedin_scraper) | Scraping profil LinkedIn |
| [**LinkedIn X-Ray**](https://linkedin.com) | Google dorking untuk LinkedIn |
| [**CrossLinked**](https://github.com/m8sec/CrossLinked) | LinkedIn enumeration tool |
| [**Youtube Comment Scraper**](https://github.com/philbot9/youtube-comment-scraper) | Ekstrak komentar YouTube |
| [**Pinterest Scraper**](https://github.com/benedictevans/pinterest-scraper) | Scraping data Pinterest |
| [**Tumblr Scraper**](https://github.com/duyet/tumblr-scraper) | Scraping data Tumblr |
| [**SocialBearing**](https://socialbearing.com) | Social media sentiment analysis |
| [**Social Searcher**](https://social-searcher.com) | Free social search engine |
| [**Social Mention**](https://socialmention.com) | Social media monitoring |
| [**Brand24**](https://brand24.com) | Social listening platform |
| [**Talkwalker**](https://talkwalker.com) | Social media analytics |
| [**Brandwatch**](https://brandwatch.com) | Digital consumer intelligence |
| [**ExportData**](https://exportdata.io) | Export data dari social media |
| [**Followerwonk**](https://followerwonk.com) | Twitter bio analytics |
| [**TweetDeck**](https://tweetdeck.twitter.com) | Twitter power user dashboard |

---

## 🌍 News & Journalism

| Tool | Deskripsi |
|------|-----------|
| [**Google News**](https://news.google.com) | Aggregator berita global |
| [**Google Alerts**](https://alerts.google.com) | Email notification untuk keyword tertentu |
| [**NewsNow**](https://newsnow.co.uk) | UK news aggregator |
| [**Reuters**](https://reuters.com) | International news agency |
| [**AP News**](https://apnews.com) | Associated Press news |
| [**BBC Monitoring**](https://monitoring.bbc.co.uk) | Media monitoring global |
| [**GDELT Project**](https://gdeltproject.org) | Global event database dan analisis |
| [**EventRegistry**](https://eventregistry.org) | News event database |
| [**MediaCloud**](https://mediacloud.org) | Media analysis platform |
| [**LexisNexis**](https://lexisnexis.com) | Legal dan news database |
| [**Factiva**](https://factiva.com) | Dow Jones news database |
| [**NewspaperArchive**](https://newspaperarchive.com) | Arsip koran historis |
| [**Elephind**](https://elephind.com) | Search engine untuk koran historis |
| [**Chronicling America**](https://chroniclingamerica.loc.gov) | Historic American newspapers |
| [**Trove**](https://trove.nla.gov.au) | Australian newspaper archive |
| [**Europeana**](https://europeana.eu) | European digital library |
| [**ProQuest**](https://proquest.com) | Academic dan news database |
| [**RSSOwl**](https://rssowl.org) | RSS feed reader |
| [**Feedly**](https://feedly.com) | RSS aggregator dan reader |
| [**Inoreader**](https://inoreader.com) | RSS dan news monitoring |
| [**NewsBlur**](https://newsblur.com) | Personal news reader |
| [**Zotero**](https://zotero.org) | Reference management research tool |
| [**Mendeley**](https://mendeley.com) | Reference manager dan academic network |
| [**EndNote**](https://endnote.com) | Reference management software |
| [**CrowdTangle**](https://crowdtangle.com) | Social media content discovery |
| [**The Fact Checker**](https://washingtonpost.com/news/fact-checker) | Fact checking resource |

---

## 🕸️ Framework & Automation

| Tool | Deskripsi |
|------|-----------|
| [**SpiderFoot**](https://github.com/smicallef/spiderfoot) | OSINT automation framework dengan 200+ modules |
| [**Recon-ng**](https://github.com/lanmaster53/recon-ng) | Web reconnaissance framework modular |
| [**Maltego**](https://maltego.com) | Graph-based link analysis dan OSINT platform |
| [**BBOT**](https://github.com/blacklanternsecurity/bbot) | Modular OSINT automation framework |
| [**Datasploit**](https://github.com/DataSploit/datasploit) | OSINT framework untuk berbagai jenis data |
| [**sn0int**](https://github.com/kpcyrd/sn0int) | Semi-automatic OSINT framework |
| [**Osmedeus**](https://github.com/j3ssie/Osmedeus) | Automated reconnaissance framework |
| [**theHarvester**](https://github.com/laramies/theHarvester) | Email, subdomain, dan name enumeration |
| [**OSINT Framework**](https://osintframework.com) | Web-based directory of OSINT tools |
| [**IntelOwl**](https://github.com/intelowlproject/IntelOwl) | Open-source threat intelligence management |
| [**OWASP Amass**](https://github.com/owasp-amass/amass) | Network mapping dan attack surface discovery |
| [**Little Brother**](https://github.com/lulz3xploit/LittleBrother) | OSINT reconnaissance automation |
| [**ReconPi**](https://github.com/x1mdev/ReconPi) | Raspberry Pi-based recon toolkit |
| [**AutoRecon**](https://github.com/Tib3rius/AutoRecon) | Multi-threaded reconnaissance automation |
| [**R3con1z3r**](https://github.com/d4rkvib3z/R3con1z3r) | Lightweight multi-threaded recon |
| [**LazyRecon**](https://github.com/nahamsec/lazyrecon) | Automated recon script |
| [**TIDoS Framework**](https://github.com/0xInfection/TIDoS-Framework) | Offensive web application assessment framework |
| [**Striker**](https://github.com/s0md3v/Striker) | Multi-purpose offensive security suite |
| [**Sifter**](https://github.com/s1l3nt78/sifter) | OSINT, recon, dan vulnerability scanner |
| [**Graduality**](https://github.com/Gradualiz/Graduality) | Continuous attack surface monitoring |
| [**Maryam**](https://github.com/saeeddhqan/Maryam) | Open-source OSINT framework |
| [**Belati**](https://github.com/aancw/Belati) | OSINT Swiss Army Knife |
| [**OnionSearch**](https://github.com/mileson/onionsearch) | Dark web search engine scraper |
| [**Mr.Holmes**](https://github.com/Lucksi/Mr.Holmes) | Information gathering OSINT |
| [**Phoenix**](https://github.com/0xPheonix/Phoenix) | OSINT framework untuk social media |
| [**Owl**](https://github.com/n0tr00t/Owl) | User and account OSINT scanner |
| [**Skiptracer**](https://github.com/xillwillx/skiptracer) | OSINT scraping framework |
| [**Eyes**](https://github.com/nicedayzhu/Eyes) | OSINT automation tool |

### Web-Based OSINT Tools Platform

| Tool | Deskripsi |
|------|-----------|
| [**OSINT Framework**](https://osintframework.com) | Visual mind map tools OSINT |
| [**Bellingcat Toolkit**](https://bellingcat.com/resources) | Koleksi tools investigasi digital |
| [**Start.me OSINT**](https://start.me/p/DPYPMz/the-ultimate-osint-collection) | Portal OSINT tools dan resources |
| [**Awesome OSINT**](https://github.com/jivoi/awesome-osint) | GitHub curated list OSINT tools |
| [**IntelTechniques**](https://inteltechniques.com) | Michael Bazzell's OSINT tools list |
| [**TraceLabs**](https://tracelabs.org) | OSINT CTF platform |
| [**OSINT Combine**](https://osintcombine.com) | Integrated OSINT platform |
| [**Social Links**](https://sociallinks.io) | Professional OSINT software |
| [**Skopenow**](https://skopenow.com) | Automated people investigation platform |
| [**Pipl**](https://pipl.com) | People search engine (professional) |
| [**BeenVerified**](https://beenverified.com) | Background check platform |
| [**Spokeo**](https://spokeo.com) | People search directory |
| [**TruthFinder**](https://truthfinder.com) | Background check service |
| [**Intelius**](https://intelius.com) | People intelligence platform |

---

## 🧰 Utility & Helper Tools

| Tool | Deskripsi |
|------|-----------|
| [**jq**](https://jqlang.github.io/jq) | CLI JSON processor untuk parsing API responses |
| [**gron**](https://github.com/tomnomnom/gron) | JSON flattening untuk grep-friendliness |
| [**yq**](https://github.com/mikefarah/yq) | YAML/JSON/XML processor |
| [**HTTPie**](https://httpie.io) | Modern HTTP client untuk API testing |
| [**cURL**](https://curl.se) | CLI tool untuk transfer data via URL |
| [**Wget**](https://gnu.org/software/wget) | CLI file downloader |
| [**Netcat**](https://nc110.sourceforge.io) | Networking utility untuk port scanning dan banner grabbing |
| [**Socat**](https://github.com/3th1n/repo) | Networking relay tool |
| [**Proxychains**](https://github.com/rofl0r/proxychains-ng) | Force aplikasi melalui proxy/Tor |
| [**Tor**](https://torproject.org) | Anonymity network |
| [**OpenVPN**](https://openvpn.net) | VPN client/server |
| [**WireGuard**](https://wireguard.com) | Modern VPN protocol |
| [**nslookup**](https://network-tools.com) | DNS query tool |
| [**dig**](https://bind9.net) | DNS lookup utility |
| [**tcpdump**](https://tcpdump.org) | Network packet analyzer |
| [**Wireshark**](https://wireshark.org) | GUI network protocol analyzer |
| [**ngrep**](https://github.com/jpr5/ngrep) | Network grep |
| [**Tmux**](https://github.com/tmux/tmux) | Terminal multiplexer modern |
| [**GNU Parallel**](https://gnu.org/software/parallel) | Parallel task execution |
| [**fzf**](https://github.com/junegunn/fzf) | Fuzzy finder untuk CLI |
| [**ripgrep (rg)**](https://github.com/BurntSushi/ripgrep) | Super-fast grep alternative |
| [**fd**](https://github.com/sharkdp/fd) | Fast find alternative |
| [**bat**](https://github.com/sharkdp/bat) | Cat with syntax highlighting |
| [**csvkit**](https://csvkit.readthedocs.io) | CSV toolkit |
| [**Miller**](https://github.com/johnkerl/miller) | CSV/JSON processing tool |
| [**xsv**](https://github.com/BurntSushi/xsv) | Fast CSV command toolkit |
| [**pup**](https://github.com/ericchiang/pup) | HTML parsing CLI |
| [**htmlq**](https://github.com/mgdm/htmlq) | HTML query tool |
| [**Beautiful Soup**](https://crummy.com/software/BeautifulSoup) | Python HTML/XML parser |
| [**Scrapy**](https://scrapy.org) | Python web scraping framework |
| [**Selenium**](https://selenium.dev) | Browser automation |
| [**Playwright**](https://playwright.dev) | Browser automation modern |
| [**Puppeteer**](https://pptr.dev) | Headless Chrome Node API |
| [**wkhtmltoimage**](https://wkhtmltopdf.org) | HTML to image converter |
| [**wkhtmltopdf**](https://wkhtmltopdf.org) | HTML to PDF converter |
| [**Chrome Headless**](https://chromium.org/headless) | Automated browser testing |
| [**OCRMypdf**](https://github.com/ocrmypdf/OCRmyPDF) | OCR untuk scanned PDF |
| [**Tesseract OCR**](https://github.com/tesseract-ocr/tesseract) | Open-source OCR engine |
| [**EasyOCR**](https://github.com/JaidedAI/EasyOCR) | Python OCR library |
| [**PaddleOCR**](https://github.com/PaddlePaddle/PaddleOCR) | OCR toolkit berbasis deep learning |
| [**pdfplumber**](https://github.com/jsvine/pdfplumber) | PDF text extraction |
| [**Camelot**](https://github.com/camelot-dev/camelot) | PDF table extraction |
| [**Tabula**](https://tabula.technology) | PDF table extraction |
| [**PyMuPDF**](https://pymupdf.readthedocs.io) | PDF manipulation |
| [**Pandoc**](https://pandoc.org) | Document converter universal |
| [**ImageMagick**](https://imagemagick.org) | Image manipulation CLI |
| [**FFmpeg**](https://ffmpeg.org) | Audio/video converter dan processor |
| [**SoX**](https://sox.sourceforge.net) | Sound eXchange — audio editor CLI |
| [**Audacity**](https://audacityteam.org) | Audio editor GUI |
| [**GnuPG**](https://gnupg.org) | Encryption dan signing tools |
| [**HashCat**](https://hashcat.net/hashcat) | Password cracking tool |
| [**JohnTheRipper**](https://openwall.com/john) | Password security auditing |
| [**Hydra**](https://github.com/vanhauser-thc/thc-hydra) | Network login cracker |
| [**Medusa**](https://github.com/jmk-foofus/medusa) | Parallel network login auditor |
| [**Ncrack**](https://nmap.org/ncrack) | Network authentication cracking |
| [**Patator**](https://github.com/lanjelot/patator) | Multi-purpose brute-forcer |
| [**CrackMapExec**](https://github.com/byt3bl33d3r/CrackMapExec) | Active Directory exploitation |
| [**Impacket**](https://github.com/fortra/impacket) | Network protocols toolkit |
| [**Responder**](https://github.com/lgandx/Responder) | LLMNR/NBT-NS poisoning |
| [**Bettercap**](https://bettercap.org) | Network attack and monitoring framework |
| [**Aircrack-ng**](https://aircrack-ng.org) | Wireless security tools |
| [**Kismet**](https://kismetwireless.net) | Wireless network detector |
| [**Reaver**](https://github.com/t6x/reaver-wps-fork-t6x) | WPS brute force tool |

---

## 📖 OSINT Resources & Guides

| Resource | Deskripsi |
|----------|-----------|
| [**Bellingcat**](https://bellingcat.com) | Investigative journalism dan OSINT community |
| [**OSINT Curious**](https://osintcurio.us) | Blog dan podcast tentang OSINT |
| [**SANS OSINT**](https://sans.org/osint) | Training dan resources OSINT |
| [**TraceLabs CTF**](https://tracelabs.org) | OSINT Capture The Flag competitions |
| [**IntelTechniques Blog**](https://inteltechniques.com) | Michael Bazzell's OSINT blog |
| [**Sector035**](https://sector035.nl) | Weekly OSINT newsletter |
| [**OSINT Techniques**](https://osinttechniques.com) | Website dengan banyak how-to OSINT |
| [**The OSINTion**](https://theosintion.com) | Blog dan podcast OSINT community |
| [**OSINT Combine**](https://osintcombine.com) | OSINT training dan resources |
| [**WebBreacher**](https://webbreacher.com) | Blog OSINT oleh Micah Hoffman |
| [**Hatless1der**](https://hatless1der.com) | OSINT blog dan weekly links |
| [**Nixintel**](https://nixintel.info) | OSINT blog dan resources |
| [**Technisette**](https://technisette.com) | OSINT blog oleh Christie |
| [**OSINT Essentials**](https://osintessentials.com) | Essential OSINT tools dan techniques |
| [**Awesome OSINT**](https://github.com/jivoi/awesome-osint) | GitHub curated list OSINT |
| [**OSINT Framework**](https://osintframework.com) | Mind map OSINT tools |
| [**AutomatingOSINT**](https://automatingosint.com) | Blog tentang OSINT automation |
| [**IACD**](https://iacd.org) | Internet Analysis Center |
| [**Dark Web OSINT**](https://darkwebosint.com) | Resources untuk dark web investigation |
| [**Social Media OSINT**](https://socialmediaosint.com) | SOCMINT techniques dan tools |
| [**Forensic OSINT**](https://forensicosint.com) | Digital forensics OSINT resources |
| [**Reddit OSINT**](https://reddit.com/r/OSINT) | r/OSINT community |
| [**OSINT Discord**](https://discord.gg/osint) | Server komunitas OSINT |
| [**OSINT Jobs**](https://osintjobs.com) | Lowongan kerja di bidang OSINT |
| [**Healing OSINT**](https://healingosint.com) | OSINT blog oleh Annika |
| [**OSINT Dojo**](https://osintdojo.com) | OSINT training resources |

---

## 🏁 Catatan

- ✅ Semua tools di atas telah terverifikasi URL resminya dan berfungsi untuk kebutuhan OSINT
- ⚠️ Gunakan tools ini secara etis dan sesuai hukum yang berlaku
- 🔄 Beberapa tools mungkin memerlukan API key untuk fungsionalitas penuh
- 📌 Status tools dapat berubah sewaktu-waktu (beberapa mungkin di-deprecate)

---

*Last updated: July 2026*

---

### 🛠️ Tools by Wanz Xploit

| Tool | Kategori | Deskripsi |
|------|----------|-----------|
| [**Zero Eight**](https://github.com/wanzxploit/zero-eight) | Phone Intelligence | Identifikasi provider dan area registrasi nomor telepon Indonesia via CLI |
