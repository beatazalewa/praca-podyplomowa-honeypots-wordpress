# praca-podyplomowa-honeypots-wordpress
Repozytorium utworzone jako rozszerzenie pracy końcowej na kierunku Cyber Science - zarządzanie cyberbezpieczeństwem na Politechnice Śląskiej - [link do strony rekrutacji.](https://rekrutacja.polsl.pl/kierunek/spd-cybersc/)

Witaj w repozytorium towarzyszącym mojej pracy podyplomowej pt. "Zastosowanie honeypotów w ochronie witryn WordPress: Studium przypadku na podstawie strony dla rodzinnej pasieki".

Celem tego projektu było zbadanie, jak prosta i niewidoczna dla użytkownika technika honeypotów może skutecznie chronić strony oparte na WordPressie przed spamem i zautomatyzowanymi atakami, bez negatywnego wpływu na doświadczenia użytkowników. To repozytorium gromadzi zasoby, narzędzia i artykuły, które były częścią moich badań lub mogą być przydatne dla każdego, kto chce wzmocnić bezpieczeństwo swojej witryny.

Więcej informacji o pracy możesz znaleźć na moim [blogu.](https://zalnet.pl/pl/wpisy) 

Dodatkowe notatki i linki do zasobów znajdziesz w tym repozytorium.

[EN]

Repository created as an extension of the final thesis in the field of Cyber ​​Science - cybersecurity management at the Silesian University of Technology - [link to recruitment website(in polish).](https://rekrutacja.polsl.pl/kierunek/spd-cybersc/)

Welcome to the repository accompanying my postgraduate thesis entitled "Using honeypots to protect WordPress sites: A case study based on a site for a family apiary."

The goal of this project was to investigate how a simple and user-invisible honeypot technique could effectively protect WordPress sites from spam and automated attacks, without negatively impacting the user experience. This repository collects resources, tools, and articles that were part of my research or may be useful to anyone looking to strengthen their website's security.

You can find more information about work on my [blog.](https://zalnet.pl/blog)

You can find additional notes and links to resources in this repository.

<br>

**🍯 Wtyczki Honeypot dla WordPress**<br>
Poniżej znajdują się wtyczki, które były analizowane lub wykorzystane w ramach studium przypadku. Wszystkie wtyczki można znaleźć na oficjalnej stronie WordPressa.

| Wtyczka | Opis[PL] | Description[En] | Link |
|:--- | :--- | :--- | :---|
| `WP Armour - Honeypot Anti Spam` | Lekka i wysoce skuteczna wtyczka, która skupia się na jednym zadaniu: dodaniu pułapek honeypot do wszystkich formularzy na stronie (komentarze, rejestracja, formularze kontaktowe np. Contact Form 7). Jej największą zaletą jest prostota i brak potrzeby konfiguracji. Działa w tle, nie wymaga od użytkownika żadnej interakcji (np. rozwiązywania CAPTCHA). | This plugins block spam submissions using honeypot anti spam technic. No Captcha or extra verification field hassle to the users. Only lets spam bots to suffer using our anti spam filter. | [WP Armour](https://wordpress.com/plugins/honeypot) |
| `Wordfence Security – Firewall, Malware Scan, and Login Security` | To kompleksowy pakiet bezpieczeństwa, a nie tylko wtyczka honeypot. Jego główną siłą jest firewall aplikacyjny (WAF) i skaner malware. Funkcje takie jak ochrona przed atakami brute-force i zaawansowane blokowanie adresów IP doskonale uzupełniają strategię opartą na honeypotach, tworząc skuteczną obronę warstwową. |Wordfence Security includes an endpoint firewall, malware scanner, robust login security features, live traffic views, and more. Our Threat Defense Feed arms Wordfence with the newest firewall rules, malware signatures, and malicious IP addresses it needs to keep your website safe.|[Wordfence Security](https://wordpress.org/plugins/wordfence/) |
| `WP fail2ban – Advanced Security` | To kompleksowy pakiet bezpieczeństwa, a nie tylko wtyczka honeypot. Jego główną siłą jest firewall aplikacyjny (WAF) i skaner malware. Funkcje takie jak ochrona przed atakami brute-force i zaawansowane blokowanie adresów IP doskonale uzupełniają strategię opartą na honeypotach, tworząc skuteczną obronę warstwową. | fail2ban is one of the simplest and most effective security measures you can implement to protect your WordPress site. WPf2b comes with three fail2ban filters: wordpress-hard.conf, wordpress-soft.conf, and wordpress-extra.conf. These are designed to allow a split between immediate banning (hard) and the traditional more graceful approach (soft), with extra rules for custom configurations. | [WP fail2ban](https://wordpress.org/plugins/wp-fail2ban/) |
| `Honeypot for Contact Form 7 — Protect Contact Form 7 spam with ease! [100% FREE Anti-Spam Plugin]` | To kompleksowy pakiet bezpieczeństwa, a nie tylko wtyczka honeypot. Jego główną siłą jest firewall aplikacyjny (WAF) i skaner malware. Funkcje takie jak ochrona przed atakami brute-force i zaawansowane blokowanie adresów IP doskonale uzupełniają strategię opartą na honeypotach, tworząc skuteczną obronę warstwową. | In the Honeypot for Contact Form 7, the plugin adds an invisible field to your Contact Form 7 form. Human users will never see this field, but spambots will. When a bot tries to submit the form, it unknowingly fills out this field, triggering the honeypot spam trap. This is how the plugin efficiently filters out unwanted spam without bothering genuine users.| [Honeypot for Contact Form 7 ](https://wordpress.org/plugins/contact-form-7-honeypot/) |
| `Honeypot Anti-Spam` | Honeypot Anti-Spam to wtyczka antyspamowa dla WordPress, która pozwala chronić formuły komentarzy w mediach społecznościowych Honeypot. Używając tej wtyczki Honeypot Anti-Spam, nie ma potrzeby włączania funkcji CAPTCHA w WordPress. |Honeypot Anti-Spam is an anti-spam plugin for WordPress that helps protect comment forms on social media Honeypot. By using this Honeypot Anti-Spam plugin, there is no need to enable the CAPTCHA feature in WordPress. | [Honeypot Anti-Spam ](https://wordpress.org/plugins/honeypot-antispam/) |


<br>

**🛠️ Projekty Honeypot na GitHubie** <br>
Świat honeypotów jest znacznie szerszy niż tylko wtyczki do WordPressa. Poniżej kilka inspirujących projektów open-source dla tych, którzy chcą zagłębić się w temat.

| Project | Opis[PL]| Description[EN] | Link |
|:--- | :--- | :--- | :--- |
| `Awesome Honeypots` | Niesamowita lista zasobów honeypot. Z gwiazdkami w repozytorium⭐ i "forks"🍴. Oprócz tego powiązane komponenty i wiele więcej, podzielone na kategorie takie jak Web, usługi i inne, z naciskiem na projekty typu open source. | An awesome list of honeypot resources. With repository stars⭐ and forks🍴. Plus related components and much more, divided into categories such as Web, services, and others, with a focus on free and open source projects. | [Awesome Honeypots](https://github.com/Correia-jpv/fucking-awesome-honeypots) |
| `Honeypress` | Projekt ciekawy, ostatnia aktualixzacja sprzed 3 lat. | High interaction honeypot for WordPress 🐝. The HoneyPress projects adds high interaction honeypot features to an existing WordPress instance. The project can be installed as a regular plugin and wiill monitor given actions on the WordPress instance. HoneyPress can allow users to be created or being used by a defined username and password list. Activities will be logged on the logs/ directory inside the WordPress directory. The project heavily depends on WordPress hook and action, but can also monitor file modifications inside the Wordpress files itself. 🛑 Don't use this on a production environment 🛑 | [Honeypress](https://github.com/cmllr/honeypress) |
| `Wordpot` | Wordpot to pułapka dla Wordpressa, która wykrywa próby dostępu do wtyczek, motywów, timthumb i innych powszechnych plików używanych do identyfikacji instalacji Wordpress. |Wordpot is a Wordpress honeypot which detects probes for plugins, themes, timthumb and other common files used to fingerprint a wordpress installation.| [Wordpot](https://github.com/gbrindisi/wordpot) |
| `HoneyPress - WordPress honeypot`| Aktualizowana 9 lat temu. |Python based WordPress honeypot in a docker container| [HoneyPress - WordPress honeypot](https://github.com/kungfuguapo/HoneyPress) |

<br>

**📚 Literatura naukowa, raporty z dziedziny cyberbezpieczeństwa (np. OWASP, ENISA), dokumentacja technicznych oraz artykuły branżowe**<br>
Wiedza teoretyczna jest fundamentem dobrych praktyk. Poniższe linki to wartościowe źródła informacji.

[EN] **📚 Scientific literature, cybersecurity reports (e.g. OWASP, ENISA), technical documentation and industry articles**<br>
Theoretical knowledge is the foundation of good practices. The links below are valuable sources of information.

**Honeypoty/Honeypots** <br>
**a) Pozycje w języku polskim**
| Tytuł | Link |
|:--- | :--- |
| `Proactive detection of security incidents II – Honeypots` | [ENISA](https://www.enisa.europa.eu/publications/proactive-detection-of-security-incidents-II-honeypots) |
| `Honeypot - definicja, rodzaje, zastosowania, przykłady` | [Era Informatyki](https://www.erainformatyki.pl/honeypot.html) |
| `Honeypot – pułapka na cyberprzestępców` | [HackerU](https://hackeru.pl/honeypot-pulapka-na-cyberprzestepcow/) |
| `Honeypot, czyli jak oszukać hakera` | [AskKomputer](https://blog.askomputer.pl/honeypot-czyli-jak-oszukac-hakera/) |
| `Honeypot - ESET Glossary` | [ESET](https://help.eset.com/glossary/pl-PL/honeypot.html) |

**b) Positions in English**
| Title | Link |
|:--- | :--- |
| `Proactive detection of security incidents II – Honeypots` | [ENISA](https://www.enisa.europa.eu/publications/proactive-detection-of-security-incidents-II-honeypots) |
| `Production vs Research Honeypots: What’s the Difference?` | [LOGIX](https://logixconsulting.com/2020/06/22/production-vs-research-honeypots-whats-the-difference/) |
| `L. Spitzner, Honeypots: Tracking Hackers, Addison-Wesley Professional, 2003` | [GOOGLE](https://books.google.pl/books/about/Honeypots.html) |
| `Medium Interaction Honeypot Infrastructure on The Internet of Things` | [IEEE Xplore](https://ieeexplore.ieee.org/document/9359711) |
| `What is Honeypot?` | [Geeks for geeks](https://www.geeksforgeeks.org/what-is-honeypot/) |

<br>

**Wordpress** <br>
**a) Pozycje w języku polskim**
| Tytuł | Link |
|:--- | :--- |
| `WordPress` | [Wikipedia](https://pl.wikipedia.org/wiki/WordPress) |
| `Cyberprzestępcy atakują miliony witryn internetowych opartych na WordPressie poprzez znane luki w zabezpieczeniach.` | [Bitdefender](https://bitdefender.pl/cyberprzestepcy-atakuja-miliony-witryn-internetowych-opartych-na-wordpressie-poprzez-znane-luki-w-zabezpieczeniach/) |
| `Popularne rodzaje ataków na strony oparte o CMS WordPress` | [DHosting](https://dhosting.pl/pomoc/baza-wiedzy/popularne-rodzaje-atakow-na-strony-oparte-o-cms-wordpress/) |
| `3 sposoby na zabezpieczenie formularza przed spamem w WordPress` | [Woocado](https://woocado.pl/zabezpieczenie-przed-spamem/) |
| `Wyciek tytułów szkiców i prywatnych wpisów w silniku WordPress` | [Sekurak](https://sekurak.pl/wyciek-tytulow-szkicow-i-prywatnych-wpisow-w-silniku-wordpress/) |


**b) Positions in English**
| Title | Link |
|:--- | :--- |
| `2024 Annual WordPress Security Report by Wordfence` | [Wordfence](https://www.wordfence.com/wp-content/uploads/2025/04/2024-Annual-WordPress-Security-Report-by-Wordfence.pdf) |
| `Types of WordPress Attacks and How to Stop Them` | [MalCare](https://www.malcare.com/blog/wordpress-attacks/) |
| `Identifying WordPress Websites On Local Networks (behind Firewalls) and Bruteforcing the Login Pages` | [Invicti](https://www.invicti.com/blog/web-security/bruteforce-wordpress-local-networks-xshm-attack/) |
| `WordPress Security Threat Update (4 Trends in 2025)` | [Elegant Themes](https://www.elegantthemes.com/blog/wordpress/wordpress-security-threats) |
| `WordPress Plugin Vulnerability Exposes 90,000 Sites to Attack` | [Infosecurity Magazine](https://www.infosecurity-magazine.com/news/wordpress-plugin-flaw-exposes/) |
 <br>

**Honeypots + Wordpress** <br>
**a) Pozycje w języku polskim**

| Tytuł | Link |
|:--- | :--- |
| `Jak zabezpieczyć formularze kontaktowe w WordPress?` | [Cyberfolks](https://cyberfolks.pl/pomoc/jak-zabezpieczyc-formularze-kontaktowe-w-wordpress/) |
| `Jak zablokować spamerskie boty komentujące w WordPressie za pomocą Honeypota?` | [WP Beginner](https://www.wpbeginner.com/pl/plugins/how-to-block-spam-comment-bots-in-wordpress-with-honeypot/) |
| `Spam wysyłany przez formularz kontaktowy` | [Cyberfolks](https://cyberfolks.pl/pomoc/jak-zabezpieczyc-formularze-kontaktowe-w-wordpress/) |
| `Spam wysyłany przez formularz kontaktowy` | [WordPress Developer](https://bb24.pl/tag/honeypot/) |
| `Honeypot – trochę zapomniany sposób na intruza` | [WOpen Security](https://opensecurity.pl/honeypot-troche-zapomniany-sposob-na-intruza/) |


**b) Positions in English**
| Title | Link |
|:--- | :--- |
| `Honeypot – the best way to secure your forms` | [Webnomads](https://www.webnomads.com/resources/honeypot-the-best-way-to-secure-your-forms) |
| `5 WordPress Honeypot Plugins to Help You Fight Spam` | [WhiteWP](https://whitewp.com/wordpress-honeypot/) |
| `Honeypot – trochę zapomniany sposób na intruza` | [Open Security](https://opensecurity.pl/honeypot-troche-zapomniany-sposob-na-intruza/) |
| `Honeypot Protection in WordPress` | [Linkedin Article](https://www.linkedin.com/pulse/honeypot-protection-wordpress-enayetur-rahman-ysnac/) |
| `Wordpress Honeypot Module` | [IEEE Xplore](https://ieeexplore.ieee.org/document/8588842) |

 <br>

**Inne** <br>
**a) Pozycje w języku polskim**

| Tytuł | Link |
|:--- | :--- |
| `Parlament Europejski i Rada Unii Europejskiej, Rozporządzenie Parlamentu Europejskiego i Rady (UE) 2016/679 z dnia 27 kwietnia 2016 r. w sprawie ochrony osób fizycznych w związku z przetwarzaniem danych osobowych i w sprawie swobodnego przepływu takich danych (RODO)` | [EUR-Lex](hhttps://eur-lex.europa.eu/legal-content/PL/TXT/?uri=CELEX:32016R0679) |

**b) Positions in English**
| Title | Link |
|:--- | :--- |
| `Defense in Depth: A Critical Approach to Cybersecurity` | [laveti.wordpress.com](https://laveti.wordpress.com/2024/02/10/defense-in-depth-a-critical-approach-to-cybersecurity/) |
| `OWASP Top 10:2021` | [owasp.org](https://owasp.org/Top10/) |

<br>



