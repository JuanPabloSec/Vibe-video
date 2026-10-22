# Najlepsze repozytoria GitHub: tworzenie wideo z agentami AI
### Priorytet: *vibe-coded video making* (agent pisze kod, kod renderuje wideo)
Stan: **2026-10-23**. Liczby ★ z GitHub API z dnia 2026-10-23 (mogą się zmieniać).
Poprzednia wersja: `ai-video-agent-repos.md` (2026-10-21).

---

## 0. Meta-listy (zacznij od nich)
| Repo | ★ | Co daje |
|---|---|---|
| [zhuyansen/awesome-claude-video-skills](https://github.com/zhuyansen/awesome-claude-video-skills) | 819 | **180+ repo** z skillami do wideo, posegregowane wg tematu; część przetestowana end-to-end z realnymi renderami. Najlepsze źródło do researchu |
| [ZeroLu/awesome-seedance](https://github.com/ZeroLu/awesome-seedance) | 2.8k | Zbiór promptów i zasobów Seedance 2.0 (największy taki zbiór) |
| [LearnPrompt/awesome-seedance](https://github.com/LearnPrompt/awesome-seedance) | 2.2k | 840+ udokumentowanych promptów, weryfikacja krzyżowa między modelami |
| [YouMind-OpenLab/awesome-seedance-2-prompts](https://github.com/YouMind-OpenLab/awesome-seedance-2-prompts) | 2.2k | 2000+ promptów: kino, anime, UGC, reklamy, memy |
| [UnderleveledBuilder/awesome-short-drama-skills](https://github.com/UnderleveledBuilder/awesome-short-drama-skills) | 634 | Katalog skilli short-drama (skrypt, storyboard, prompty) |

---

## 1. REMOTION — silnik i ekosystem (dodane na życzenie)
### 1a._rdzeń_
| Repo | ★ | Co robi |
|---|---|---|
| [remotion-dev/remotion](https://github.com/remotion-dev/remotion) | **66.4k** | **„Make videos programmatically with React"** — React/TSX jako źródło prawdy wideo. Standard branżowy, ogromne API, rendering w chmurze (Lambda), Player do web. Uwaga: licencja komercyjna dla firm >3 os. |
| [remotion-dev/skills](https://github.com/remotion-dev/skills) | **5.5k** | **Oficjalne skille Remotion** dla agentów: best-practices, markup, captions, maps, render, studio, multimedia, upgrade. Punkt wejścia dla każdego agenta |

### 1b. Ekosystem / skille agentowe pod Remotion
| Repo | ★ | Co robi |
|---|---|---|
| [Remocn/remocn](https://github.com/Remocn/remocn) | 1.6k | Gotowe, produkcyjne animacje, przejścia, tła i sceny dla Remotion |
| [haidrrrry/claude-remotion-skill](https://github.com/haidrrrry/claude-remotion-skill) | 585 | Skill uczący Claude Code/Desktop tworzenia i edycji profesjonalnych wideo w Remotion |
| [av/remotion-bits](https://github.com/av/remotion-bits) | 496 | Komponenty animowane gotowe do użycia: wykresy, przejścia, text reveal |
| [wshuyi/remotion-video-skill](https://github.com/wshuyi/remotion-video-skill) | 426 | Claude Code Skill do tworzenia programatycznych wideo w Remotion |
| [t3knobox/klik-anim-skill-creation](https://github.com/t3knobox/klik-anim-skill-creation) | 77 | „klik-anim-bible" — prawa craftu animacji Remotion jako skille |

### 1c. Oficjalne szablony i przykłady (remotion-dev)
| Repo | ★ | Co robi |
|---|---|---|
| [remotion-dev/github-unwrapped](https://github.com/remotion-dev/github-unwrapped) | 1.3k | „Twój rok kodowania" — pokazowy produkt na Remotion |
| [remotion-dev/trailer](https://github.com/remotion-dev/trailer) | 1.1k | Oficjalny film promujący Remotion |
| [remotion-dev/template-tiktok](https://github.com/remotion-dev/template-tiktok) | 291 | Napisy TikTok-style generowane z Whisper.cpp |
| [remotion-dev/template-prompt-to-motion-graphics-saas](https://github.com/remotion-dev/template-prompt-to-motion-graphics-saas) | 281 | Prompt → motion graphics (SaaS-ready) |
| [remotion-dev/template-audiogram](https://github.com/remotion-dev/template-audiogram) | 274 | Klipy podcastowe z wizualizacją audio |
| [remotion-dev/template-code-hike](https://github.com/remotion-dev/template-code-hike) | 220 | Animowane snippet'y kodu |
| [remotion-dev/template-prompt-to-video](https://github.com/remotion-dev/template-prompt-to-video) | 160 | Prompt → historia z obrazami i lektorem |
| [remotion-dev/template-three](https://github.com/remotion-dev/template-three) | 116 | Remotion + React Three Fiber |
| [remotion-dev/template-helloworld](https://github.com/remotion-dev/template-helloworld) | 74 | Punkt startowy nowego projektu |

### 1d. Filmy/studia zbudowane na Remotion
| Repo | ★ | Co robi |
|---|---|---|
| [Vincentwei1021/video-shotcraft](https://github.com/Vincentwei1021/video-shotcraft) | **13.0k** | 152 karty receptur ujęć + 209 podglądów → cinematic product videos w Remotion |
| [openvideodev/react-video-editor](https://github.com/openvideodev/react-video-editor) | 1.8k | Open-source edytor wideo online (CapCut/Canva clone) na Remotion |
| [Agents365-ai/video-podcast-maker](https://github.com/Agents365-ai/video-podcast-maker) | 1.7k | Temat → 4K narracyjne wideo: lokalny TTS, Remotion, bramki kosztu |
| [wcandillon/remotion-fireship](https://github.com/wcandillon/remotion-fireship) | 493 | Film w stylu Fireship zrobiony w React/Remotion |
| [JonnyBurger/vibe-coded-video](https://github.com/JonnyBurger/vibe-coded-video) | 48 | „Video generated only using prompts" — od twórcy Remotion |

---

## 2. Silniki renderujące „kod = wideo" (poza Remotion)
| Repo | ★ | Co robi |
|---|---|---|
| [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | **70.0k** | „Write HTML. Render video." HTML+GSAP → deterministyczny MP4, seek-safe, MCP + skille. **Najpopularniejszy vibe-coded renderer.** |
| [motion-canvas/motion-canvas](https://github.com/motion-canvas/motion-canvas) | **19.4k** | Animacje w TypeScript + Canvas z podglądem na osi czasu |
| [nexu-io/html-video](https://github.com/nexu-io/html-video) | **4.7k** | HTML/CSS + dane → prawdziwe MP4 na Twoim laptopie, „built for coding agents" |
| [dmtrKovalenko/fframes](https://github.com/dmtrKovalenko/fframes) | **2.9k** | Framework renderingu programatycznego „który faktycznie jest szybki" |
| [openfilm/openfilm](https://github.com/openfilm/openfilm) | 2.1k | „Open source AI video agent" — zamienia dowolnego agenta w video agenta + edytor |
| [gatewai-dev/framefields](https://github.com/gatewai-dev/framefields) | 479 | Code-first video renderowane natywnie na **WebGPU** — bez headless Chrome |
| [LBEILC/Multiplane](https://github.com/LBEILC/Multiplane) | 106 | Lekki, headless renderer HTML→wideo dla agentów; ujęcia jako strony WWW z `render(t)` |
| [Vandit1604/vawe](https://github.com/Vandit1604/vawe) | 8 | Lekka alternatywa dla Remotion (HTML→video) |
| [heygen-com/hyperframes-community-skills](https://github.com/heygen-com/hyperframes-community-skills) | 226 | Oficjalne skille społeczności HyperFrames |
| [geekjourneyx/hyperframes-motion-director](https://github.com/geekjourneyx/hyperframes-motion-director) | 466 | HyperFrames „reżyserski" (CN/EN): artykuły/produkty → motion wideo |
| [nutllwhy/hyperframes-motion-library](https://github.com/nutllwhy/hyperframes-motion-library) | 299 | Biblioteka motion dla HyperFrames |

---

## 3. Pełne studia agentic video (all-in-one)
| Repo | ★ | Co robi |
|---|---|---|
| [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) | **70.9k** | 12 pipeline'ów produkcyjnych, 100+ narzędzi, 700+ skilli. Agent (Claude Code/Cursor/Codex) = studio |
| [hypit-ai/hypit](https://github.com/hypit-ai/hypit) | **24.8k** | „Clone any viral video" — podmiana twarzy, tekstu, B-rollu, 100 wariantów jedną komendą |
| [HBAI-Ltd/Toonflow-app](https://github.com/HBAI-Ltd/Toonflow-app) | **19.0k** | AI short drama / motion comic: infinite canvas, agenci, storyboard, MCP |
| [waooAI/waoowaoo](https://github.com/waooAI/waoowaoo) | **14.7k** | Przemysłowa platforma filmowa (Hollywood-style workflow) |
| [krillinai/OpenCreator](https://github.com/krillinai/OpenCreator) | **13.8k** | Workspace (dawniej KrillinAI): pobieranie, tłumaczenie, dubbing, awatary, edycja |
| [trykimu/videoeditor](https://github.com/trykimu/videoeditor) | 2.3k | „Creative Copilot for Video Editing" |
| [HITsz-TMG/VideoClaw](https://github.com/HITsz-TMG/VideoClaw) | 1.9k | „Chat an idea, get a film" — automatyczny pracownik AIGC do wideo |
| [veedstudio/open-edit](https://github.com/veedstudio/open-edit) | 1.7k | Agent-driven pipeline: napisy, motion graphics, slajdy, montaż i render |
| [gyoridavid/short-video-maker](https://github.com/gyoridavid/short-video-maker) | 1.4k | Shorty na TikTok/Reels/Shorts przez MCP |
| [first-fluke/oh-my-agent](https://github.com/first-fluke/oh-my-agent) | 1.4k | 12 ról, 21 workflowów, 33 skille dla Twojego agenta (plan/build/ship) |
| [lidge-ai/ima2-gen](https://github.com/lidge-ai/ima2-gen) | 885 | Lokalny runtime generatywny dla ludzi i agentów (obraz/wideo z powtarzalnością) |
| [receptron/mulmocast-cli](https://github.com/receptron/mulmocast-cli) | 475 | Podcast + wideo z CLI, klonowanie głosu, lip-sync |
| [Orkas-AI/Orkas-VideoStudio](https://github.com/Orkas-AI/Orkas-VideoStudio) | 326 | Agent pisze timeline jako czytelny `plan.json` (dyfowalny, re-renderowalny); CLI + MCP |
| [FavioVazquez/showtime](https://github.com/FavioVazquez/showtime) | 272 | Lokalne studio wideo dla agenta: „agent reżyseruje, maszyna renderuje". Zero kluczy API |
| [jinzijian/Mimie](https://github.com/jinzijian/Mimie) | — | AI Video Agent: planowanie → generacja → montaż → weryfikacja |
| [lang315/ArcReel](https://github.com/lang315/ArcReel) | — | Powieść → postaci → scenariusz → storyboard → klipy → film (Claude Agent SDK) |
| [abhinavshrivastava950/Montara](https://github.com/abhinavshrivastava950/Montara) | 22 | Autonomiczny „video production OS" niezależny od renderera |

---

## 4. Skille do vibe-coded video
### 4a. Zestawy ogólne i motion
| Repo | ★ | Co robi |
|---|---|---|
| [Jakubantalik/transitions.dev](https://github.com/Jakubantalik/transitions.dev) | **5.5k** | 43+ dopracowanych przejść UI/motion + pasujący do workflowu skill |
| [alchaincyf/huashu-art-motion](https://github.com/alchaincyf/huashu-art-motion) | **4.9k** | Skill „art motion": 35 stylów artystycznych, 9 gramatyk解说, animacja kodem |
| [oil-oil/oil-motion](https://github.com/oil-oil/oil-motion) | 2.7k | Animacje web reagujące na scroll i kursor (Claude Code/Codex) |
| [nolangz/pixel2motion](https://github.com/nolangz/pixel2motion) | 2.5k | Logo (raster) → gładka animacja SVG → GIF/wideo |
| [kylezantos/design-motion-principles](https://github.com/kylezantos/design-motion-principles) | 1.4k | Motion design w dwóch trybach: buduj komponenty albo audytuj istniejące |
| [vibe-motion/skills](https://github.com/vibe-motion/skills) | 1.4k | „Agent skills for vibe motion" — ~4 min do filmu z dźwiękiem, własny styl |
| [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | 1.4k | Komercyjne launch filmy: agent komponuje muzykę i wskazuje klatki palcem |
| [iart-ai/motion-skills](https://github.com/iart-ai/motion-skills) | 965 | **50 skillów**: kinetic typography, data-viz, explainery, TikTok/Reels, WebGL, Manim |
| [Barty-Bart/motion-graphics](https://github.com/Barty-Bart/motion-graphics) | 805 | Motion-graphics skille dla Claude Code i Codex |
| [bangtutorial/bang-motion](https://github.com/bangtutorial/bang-motion) | 682 | Openers, promos, bumpers, kinetic typography, 5 stylów explainera |
| [iart-ai/motion-design-skills](https://github.com/iart-ai/motion-design-skills) | 145 | Fundamenty motion design (timing, typografia, kolor) |
| [kangarooking/director-skills](https://github.com/kangarooking/director-skills) | 224 | „Director Skills" — reżyseria AI-video (CN/EN) |

### 4b. Wysoka jakość / jeden koncept
| Repo | ★ | Co robi |
|---|---|---|
| [lemomo-ai/lemo-opuscar](https://github.com/lemomo-ai/lemo-opuscar) | 4.8k | 51 stylów filmowych — każdy z demo w całości w kodzie (Canvas/WebGL/Three.js) |
| [feitangyuan/onetake](https://github.com/feitangyuan/onetake) | 2.8k | Film, który **nigdy nie robi cięcia na slajd** — jeden ciągły aparat |
| [Vincentwei1021/anything2explainer](https://github.com/Vincentwei1021/anything2explainer) | 2.7k | Temat → motion-graphics explainer z TTS, napisami i paskiem rozdziałów |
| [Vincentwei1021/video-talkcraft](https://github.com/Vincentwei1021/video-talkcraft) | 1.7k | 109 kart motion, sync voiceover co słowo, anty-slideshow system kamer |
| [Alexgreensh/anidoodle](https://github.com/alexgreensh/anidoodle) | 1.0k | Ilustracja i animacja **jako kod**: launch-video i filmy z oceną |
| [Tejashmakwana/motionmaxxing](https://github.com/Tejashmakwana/motionmaxxing) | 981 | „Looksmaxxing dla motion graphics" — zamienia slop w film motion designera |
| [digitalsamba/claude-code-video-toolkit](https://github.com/digitalsamba/claude-code-video-toolkit) | 2.3k | AI-native toolkit produkcyjny (dźwięk, rendering, QC) |
| [echris6/motion-video-kit](https://github.com/echris6/motion-video-kit) | 1.2k | Premium business videos: niezależny krytyk, zasady z 28 launch filmów, sound design |
| [howseen-ai/claude-motion-design](https://github.com/howseen-ai/claude-motion-design) | 636 | Motion design w czystym kodzie: HTML + Playwright + ffmpeg (bez AE, bez licencji Remotion) |
| [op7418/guizang-product-video-skill](https://github.com/op7418/guizang-product-video-skill) | 841 | Reużycie realnych komponentów produktu → film aktualizacji |
| [charlie947/motion-graphics-skills](https://github.com/charlie947/motion-graphics-skills) | 366 | 13 skilli, każda klatka to kod |
| [AbubakrChan/product-launch-motion](https://github.com/AbubakrChan/product-launch-motion) | 338 | Launch video „poziomu Dribbble": jedna forma, sprężyny, SFX w beacie |
| [Anil-matcha/vox-ai-motion-graphics-generator](https://github.com/Anil-matcha/vox-ai-motion-graphics-generator) | 280 | Styl Vox: papierowa kolaż → gotowy explainer (script + kolaż + TTS) |
| [norahe0304-art/30x-video](https://github.com/norahe0304-art/30x-video) | 64 | „16-law taste codex", 12 brandów, zero szablonów |
| [smwbev/framewright](https://github.com/smwbev/framewright) | 23 | Jeden plik HTML, każda klatka to czysta funkcja (frame, seed, width) |
| [illodev/drawn-by-code](https://github.com/illodev/drawn-by-code) | 25 | Animacja rysowana kodem (claymation, paper-cutout, raymarching) |
| [talsiach/take-one](https://github.com/talsiach/take-one) | 65 | Jedno zdanie → launch/ad/music video + „review room" sterujący ujęciami |
| [Kianzzz/xilo-opus-video](https://github.com/Kianzzz/xilo-opus-video) | 225 | 3 propozycje + podglądy → render klatka po klatce |
| [Hype-yolo/claude-motion-skill](https://github.com/Hype-yolo/claude-motion-skill) | 77 | 47 open-source case'ów, edytowalne sceny, MP4 |
| [ZLHad/OpenVideoHarness](https://github.com/ZLHad/OpenVideoHarness) | 20 | Agent pisze kod renderujący film, sam sprawdza klatki i storyboard |
| [Mort1d/motion-graphics-skills](https://github.com/Mort1d/motion-graphics-skills) | 60 | Showreel-grade motion z oryginalną ścieżką dźwiękową do każdego filmu |
| [farhan-syah/motion-video-skill](https://github.com/farhan-syah/motion-video-skill) | 46 | Brief/zrzuty/repo → wyreżyserowany motion-graphics MP4 |
| [liyupi/ai-promo-video-maker](https://github.com/liyupi/ai-promo-video-maker) | 363 | Jeden prompt → promo wideo: research produktu, makiety, 4K z realnej strony,卡点 (cut w beacie) |
| [apenasdouglas/ai-motion-library](https://github.com/apenasdouglas/ai-motion-library) | 73 | 24 efekty animacji (nazwy PL + prompt do AI) |
| [Sunwood-ai-labs/hyperframes-motion-reel-skill](https://github.com/Sunwood-ai-labs/hyperframes-motion-reel-skill) | 151 | Showreel-grade, beat-synced motion graphics na HyperFrames |

---

## 5. Edycja / post-produkcja (agent tnie, nie generuje)
| Repo | ★ | Co robi |
|---|---|---|
| [Agentchengfeng/chengfeng-videocut-skills](https://github.com/Agentchengfeng/chengfeng-videocut-skills) | **3.1k** | Agent edycji wideo zrobiony z Claude Code Skills |
| [0xsline/OpenChatCut](https://github.com/0xsline/OpenChatCut) | 2.6k | Lokalny konwersacyjny edytor: wielotorowa oś czasu, Agent Skills, MCP, render Remotion |
| [kajisho5/ffmpeg-skill](https://github.com/kajisho5/ffmpeg-skill) | 2.0k | 42 narzędzia FFmpeg + serwer MCP. Cięcie, napisy, reframe, loudness |
| [nateherkai/herk-edit-kit](https://github.com/nateherkai/herk-edit-kit) | 2.0k | 15 skilli edycji reel/Shorts dla Codex i Claude Code (transkrypcja, napisy…) |
| [renezander030/capcut-cli](https://github.com/renezander030/capcut-cli) | 936 | CLI do projektów CapCut/JianYing (剪映) |
| [MartinDelophy/ai-video-editor](https://github.com/MartinDelophy/ai-video-editor) | 878 | Lokalny edytor, twórca i agent na tej samej osi czasu |
| [linzzzzzz/openclip](https://github.com/linzzzzzz/openclip) | 576 | Automatyczne wycinanie highlightów z długich filmów |
| [hassancs91/claude-youtube-editor](https://github.com/hassancs91/claude-youtube-editor) | 340 | Talking head → cięcie, wizualia, głos, SFX, miniatura, upload |
| [Cassette-Editor/oh-my-cassette](https://github.com/Cassette-Editor/oh-my-cassette) | 122 | „Kieszonkowy współredaktor AI" — plugin + MCP |
| [kurbaitaev/ghost-editor](https://github.com/kurbaitaev/ghost-editor) | 76 | Reelsy talking-head: 7 stylów, napisy bezpieczne dla twarzy |
| [pycodebr/heditor](https://github.com/pycodebr/heditor) | 84 | Kreatywna edycja pionowa: style, tryb creative, HyperFrames + voice-first mix |
| [davidcervinka/vibe-editing](https://github.com/davidcervinka/vibe-editing) | 8 | „Vibe coding, ale dla wideo" — launch filmy, aftermovie, reelsy z Claude Code |
| [kmilo93sd/agent-video-editor](https://github.com/kmilo93sd/agent-video-editor) | 6 | Osąd edytora: pacing, cięcia, napisy, audio, kolor + 128 dźwięków CC0 |
| [WhiteTowerAI/cut-as-code](https://github.com/WhiteTowerAI/cut-as-code) | 17 | Agenticzna edycja — alternatywa dla Opus Clip i CapCut |

---

## 6. Generacja modelowa (agent jako reżyser, model generuje klatki)
| Repo | ★ | Co robi |
|---|---|---|
| [scenario-labs/skills](https://github.com/scenario-labs/skills) | 1.1k | Wybór modelu + wycena przed wydatkiem + spójność postaci/brandu |
| [artokun/comfyui-mcp](https://github.com/artokun/comfyui-mcp) | 855 | Control plane dla ComfyUI: narzędzia + skille, edycja grafu NL |
| [ffroliva/gflow-cli](https://github.com/ffroliva/gflow-cli) | 324 | Google Flow z CLI (Veo + Imagen), batch, MCP |
| [vericontext/vibeframe](https://github.com/vericontext/vibeframe) | 181 | Seedance/Runway/Veo/Kling na Twoich kluczach, twardy limit kosztu |
| [BarneyD66/clipmivo-tools](https://github.com/BarneyD66/clipmivo-tools) | 142 | Generacja wideo: REST API, CLI, lokalny MCP, Agent Skill |
| [black-forest-labs/skills](https://github.com/black-forest-labs/skills) | 136 | Oficjalne skille FLUX (obraz + wideo) |
| [MCKRUZ/ComfyUI-Expert](https://github.com/MCKRUZ/ComfyUI-Expert) | 92 | 12 skilli do produkcji wideo w ComfyUI (Wan, LoRA, klonowanie głosu) |
| [magichourhq/skills](https://github.com/magichourhq/skills) | 12 | Magic Hour MCP — obrazy/wideo/audio z poziomu agenta |
| [patraxo/ltx2-vidgen-skill](https://github.com/patraxo/ltx2-vidgen-skill) | 8 | LTX-2.3 self-hosted na własnym GPU, ~$0.02/klip |
| [utensils/mold](https://github.com/utensils/mold) | 54 | Lokalna generacja obraz/wideo dla skryptów i agentów (CUDA/Metal) |
| [robonuggets/seedance-skill](https://github.com/robonuggets/seedance-skill) | 107 | Seedance 2.0: liquid glass prompting + Fal AI |

---

## 7. Short drama / pionowe /解说 (rynek azjatycki — bardzo aktywny)
| Repo | ★ | Co robi |
|---|---|---|
| [darkzOGx/youtube-automation-agent](https://github.com/darkzOGx/youtube-automation-agent) | **4.5k** | Pełen kanał YouTube end-to-end: research → skrypt → lektor → wideo → SEO → publikacja |
| [zenstory-ai/drama-skills](https://github.com/zenstory-ai/drama-skills) | 3.2k | Skille do AI short drama/manju: skrypt, assets, storyboard, prompty, review |
| [NarratorAI-Studio/narrator-ai-cli-skill](https://github.com/NarratorAI-Studio/narrator-ai-cli-skill) | 3.1k | „AI 解说大师" — automatyczne komentarze/deklaracje wideo |
| [kaomei/stickman-video-director](https://github.com/kaomei/stickman-video-director) | 2.8k | Biblioteka stylu animacji „火柴人" + generator promptów |
| [Alisa0808/vox-director](https://github.com/Alisa0808/vox-director) | 2.4k | Styl Vox: papierowa kolaż z jednego tematu, end-to-end |
| [jaycheng/…/chatgpt-video-editing-skills](https://github.com/Jaycheng1103/chatgpt-video-editing-skills) | 599 | 8-krokowy, weryfikowalny montaż short-video przez Codex/ChatGPT |
| [zenstory-ai/video-recap-skills](https://github.com/zenstory-ai/video-recap-skills) | 584 | Wideo → chiński recyk + eksport projektu JianYing/CapCut |
| [zhaihao118/Micro-Drama-Skills](https://github.com/zhaihao118/Micro-Drama-Skills) | 325 | Pełny流程 short drama: skrypt → postacie → storyboard → submit wideo |
| [YvonneMovingon/short-drama-skills](https://github.com/YvonneMovingon/short-drama-skills) | 95 | Skille short-drama sprawdzone w produkcji (LuxReal) |
| [JuneYaooo/cheap-claude-video](https://github.com/JuneYaooo/cheap-claude-video) | 80 | „Distyluj" film zrobiony Claude → receptura do odtwarzania tanimi modelami |
| [Agent-Field/reels-af](https://github.com/Agent-Field/reels-af) | 119 | Autonomiczny multi-agent na reelsy/TikTok (~$0.1/reel) |

---

## 8. Inne warte uwagi
| Repo | ★ | Co robi |
|---|---|---|
| [solomondivyananth/aftereffects-mcp](https://github.com/solomondivyananth/aftereffects-mcp) | 70 | MCP do żywego projektu AE: compos, render klatek, keyframe'y, expressions |
| [mutonby/vibetube](https://github.com/mutonby/vibetube) | 87 | Multicam recorder (macOS) → agent montuje finalne wideo |
| [Avijit07x/cursorcam](https://github.com/Avijit07x/cursorcam) | 67 | Agent klika po Twojej aplikacji i oddaje polerowany MP4 z zoomami |
| [Arman-Luthra/aftr](https://github.com/Arman-Luthra/aftr) | 24 | **Puppeteer dla After Effects** — Claude Code steruje prawdziwym AE |
| [hraness/slopcamera](https://github.com/hraness/slopcamera) | 7 | Obrazy, diagramy, animacje, 3D, filmy Blender i edycja z jednego źródła |
| [narain-karti/Walkthrough](https://github.com/narain-karti/Walkthrough) | 0 | Agent eksploruje Twoją appkę webową → film instruktażowy z narracją |

---

## 9. Rekomendacja — co zainstalować najpierw

**Stack „Remotion-first" (React → wideo):**
1. Silnik: **remotion-dev/remotion** + szablon `template-prompt-to-motion-graphics-saas` albo `template-helloworld`
2. Skille: **remotion-dev/skills** (oficjalne) + **haidrrrry/claude-remotion-skill** + **av/remotion-bits** (gotowe komponenty) + **Remocn/remocn**
3. Receptury ujęć: **video-shotcraft** (152 karty) lub **wshuyi/remotion-video-skill**
4. Szablony napisów: `template-tiktok`; podcast: `template-audiogram`; kod: `template-code-hike`

**Stack „HTML-first" (bez licencji Remotion):**
1. Silnik: **hyperframes** (70k ★) albo **nexu-io/html-video** / **fframes** (szybki)
2. Skille: **iart-ai/motion-skills** (50 skillów) + **Tejashmakwana/motionmaxxing** (jakość) + **vibe-motion/skills**
3. Audio/TTS: Kokoro/edge-tts (jak w explainroo)
4. Post: **kajisho5/ffmpeg-skill** + **0xsline/OpenChatCut**

**Stack „agent jako reżyser, model generuje":**
1. **vibeframe** (Seedance/Veo/Kling z koszt-capa) albo **gflow-cli** (Veo)
2. Orkiestracja: **OpenMontage** albo **HITsz-TMG/VideoClaw** albo **hypit**
3. Prompty: **ZeroLu/awesome-seedance** + **LearnPrompt/awesome-seedance** + **YouMind-OpenLab/awesome-seedance-2-prompts**
4. Post: **ffmpeg-skill** + **capcut-cli**

**Uwagi praktyczne:**
- **Remotion ma licencję komercyjną** (darmowy dla osób fizycznych i firm ≤3 osób; większe firmy potrzebują licencji) — hyperframes/HTML+ffmpeg to ścieżka bez licencji.
- Licencje/„gwiazdki" w sekcjach skills: skill = wykonywalny kod — sprawdzaj repo przed instalacją (pomocne: `awesome-claude-video-skills` ma oceny bezpieczeństwa).
- HITsz-TMG/VideoClaw (1.9k ★) to inny projekt niż MindDock/videoclaw (5 ★) — w poprzedniej liście był pomylenie tym drugim.
- Największy przyrost od 2026-10-21: **nexu-io/html-video** (4.7k), **dmtrKovalenko/fframes** (2.9k), **Remocn/remocn** (1.6k), **nateherkai/herk-edit-kit** (2.0k) — wszystkie nowe na liście.
